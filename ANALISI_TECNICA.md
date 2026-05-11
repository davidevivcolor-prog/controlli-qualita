# Analisi tecnica del progetto (single-file HTML/JS + Firestore)

## Scope analizzato
- `index.html` (UI, logica applicativa, query Firestore, rendering e gestione stato).
- Nessuna riscrittura architetturale proposta; solo miglioramenti incrementali compatibili con l’impianto attuale.

## Miglioramenti concreti trovati

### 1) Letture complete Firestore in più flussi (`getAll`) 
**Problema**  
Il codice usa `getAll()` che esegue `getDocs(collection(...))` senza limiti né paginazione su `products` e `checks` in diversi punti (backup, export globale, fallback, KPI, operator history fallback).  

**Impatto UX/performance**  
Con crescita dati, tempi di caricamento e costi Firestore aumentano rapidamente; su mobile si percepiscono freeze UI e consumo rete/batteria.

**Soluzione concreta**  
- Tenere `getAll()` solo per backup/export admin.
- Per schermate operative usare query limitate + range (`where`, `orderBy`, `limit`, `startAfter`) e pre-aggregati già presenti in `products.stats`.
- Inserire soglia di sicurezza: oltre N record mostrare “raffina filtri” invece di caricare tutto.

**Priorità**: alta  
**Difficoltà**: media

---

### 2) Report statistici basati su scansione completa del periodo
**Problema**  
`runStats()` richiama `fetchChecksInRange()` che scarica fino a tutto il periodo (batch da 800) e poi aggrega lato client.

**Impatto UX/performance**  
Periodi lunghi (es. annuale) possono bloccare interfaccia, aumentare latenza e costi lettura; su connessioni mobili peggiora molto.

**Soluzione concreta**  
- Mantenere la struttura attuale ma aggiungere cache in memoria keyed by `mode+periodo`.
- Limitare default a periodo mensile; per annuale mostrare avviso con “caricamento pesante”.
- Valutare pre-aggregazione incrementale giornaliera/mensile in documenti `meta` (senza cambiare collezioni principali).

**Priorità**: alta  
**Difficoltà**: media

---

### 3) Eliminazione/rinomina prodotto non batch (N roundtrip)
**Problema**  
`deleteProductAndChecks()` e `renameProductAndChecks()` ciclano i documenti ed eseguono una write per documento.

**Impatto UX/performance**  
Operazioni lunghe, fragili su rete intermittente; rischio stato parziale in caso di errore a metà.

**Soluzione concreta**  
- Usare `writeBatch` (o chunk da 400/450 write) lato client mantenendo stessa struttura dati.
- Mostrare progress UI (“X/Y documenti”).

**Priorità**: alta  
**Difficoltà**: media

---

### 4) Rendering archivio prodotti completo ad ogni filtro/sort
**Problema**  
`applyAllProductsUI()` rigenera sia tabella sia cards ad ogni input, anche quando una vista è nascosta.

**Impatto UX/performance**  
Render inutili + garbage collection; percezione di lag in digitazione ricerca e su device meno potenti.

**Soluzione concreta**  
- Renderizzare solo la vista attiva (`wantCards` *oppure* `wantTable`).
- Debounce ricerca da 120ms a 180-220ms su mobile.
- Se lista > N elementi, usare “progressive render” (chunk con `requestAnimationFrame`).

**Priorità**: media  
**Difficoltà**: facile

---

### 5) Possibile duplicazione lavoro iniziale operatori
**Problema**  
`syncOperatorsFromCloud()` viene chiamata sia in `init()` sia su evento `window.load`.

**Impatto UX/performance**  
Doppio traffico e doppio merge iniziale evitabile; possibile jitter della UI pickers all’avvio.

**Soluzione concreta**  
- Tenere una sola chiamata bootstrap con flag `__operatorsSyncStarted`.

**Priorità**: media  
**Difficoltà**: facile

---

### 6) Fallback pesanti che degradano male con dataset grande
**Problema**  
In caso errore query, alcuni flussi fanno fallback a `getAll(checks)` e sort client (es. home recenti).

**Impatto UX/performance**  
Quando la query fallisce (indice/regole/rete), il fallback può diventare ancora più costoso del percorso normale.

**Soluzione concreta**  
- Fallback “degradato” con `limit` e messaggio esplicito (“mostro dati parziali”).
- Logging più mirato per distinguere errore indice vs rete.

**Priorità**: media  
**Difficoltà**: facile

---

### 7) Allegati PDF in base64 su Firestore
**Problema**  
Se Storage è disattivato/errore, i PDF finiscono in `attachmentB64` dentro documento check.

**Impatto UX/performance**  
Aumenta dimensione documenti, latenza lettura/scrittura e rischio di raggiungere limiti documento; peggiora scalabilità.

**Soluzione concreta**  
- Mantenere fallback ma ridurre limite bytes e forzare warning più esplicito.
- Pulizia periodica allegati base64 storici (script manuale admin).

**Priorità**: alta  
**Difficoltà**: media

---

### 8) Accessibilità: modal e feedback non pienamente ARIA
**Problema**  
Modal CoA non ha gestione focus-trap/ESC completa; molti aggiornamenti dinamici usano `innerHTML` senza `aria-live`.

**Impatto UX/performance**  
Utenti tastiera/screen reader faticano a capire stato caricamenti, errori e cambi vista.

**Soluzione concreta**  
- Aggiungere `role="dialog"`, `aria-modal="true"`, focus iniziale e ritorno focus.
- Area `aria-live="polite"` per stato DB/notifiche operazioni.

**Priorità**: media  
**Difficoltà**: facile

---

### 9) Feedback utente: molte `alert/confirm` bloccanti
**Problema**  
Uso esteso di `alert()`/`confirm()` per errori e flussi frequenti.

**Impatto UX/performance**  
Esperienza “a scatti”, soprattutto mobile; interrompe compilazione e navigazione.

**Soluzione concreta**  
- Sostituire progressivamente con toast inline non bloccanti (div dedicato) mantenendo confirm solo per operazioni distruttive.

**Priorità**: media  
**Difficoltà**: facile

---

### 10) Ordinamenti/ricalcoli ripetuti lato client
**Problema**  
Diversi punti fanno `sort/filter/map` ripetuti su array completi (`checks`, `ops`, storico).

**Impatto UX/performance**  
CPU inutile al crescere dati; lag su device entry-level.

**Soluzione concreta**  
- Memoization leggera per risultati derivati (es. chiave: `code + lastUpdated`).
- Evitare sort duplicati quando la query Firestore ha già ordering corretto.

**Priorità**: bassa  
**Difficoltà**: facile

---

## Classifica miglioramenti più importanti (ordine consigliato)
1. Ridurre/isolare i percorsi con `getAll()` su `checks` e `products` fuori da backup/export.  
2. Ottimizzare `runStats()` (cache + limiti periodo + pre-aggregati incrementali leggeri).  
3. Batch write per rename/delete massivi.  
4. Gestione allegati: minimizzare fallback base64.  
5. Ottimizzare rendering archivio (render solo vista attiva).

## Quick wins (facili e veloci)
- Evitare doppia `syncOperatorsFromCloud()` all’avvio.  
- Renderizzare solo cards o table in archivio, non entrambe.  
- Aggiungere `aria-live` e migliorare feedback stato DB.  
- Debounce ricerca archivio più conservativo su mobile.  
- Fallback query con dataset parziale anziché `getAll` completo.

## Miglioramenti ad alto impatto
- Strategia “no full scan” per statistiche e viste operative principali.  
- Batch/chunk per operazioni massive su checks.  
- Riduzione payload documento check (allegati).

## Modifiche che conviene NON fare ora
- Riscrittura completa SPA/framework migration: costo alto, beneficio non proporzionato nel breve.  
- Cambiare radicalmente struttura Firestore: non necessario per ottenere i primi miglioramenti reali.  
- Virtual DOM/custom state manager complesso: overengineering per un single-file app.
