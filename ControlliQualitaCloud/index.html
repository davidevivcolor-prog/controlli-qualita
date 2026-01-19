<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Registro Controlli (Cloud)</title>
  <style>
    *{ box-sizing:border-box; }
    :root{
      --b:#e7e7e7;
      --t:#0f172a;
      --m:#64748b;
      --bg:#f6f7fb;
      --card:#ffffff;
      --shadow: 0 6px 18px rgba(15,23,42,.06);
      --radius:16px;
      --accent:#111827;
      --accent2:#0ea5e9;
      --danger:#b00020;
      --okbg:#effaf2;
      --okbd:#bfe7c8;
      --kobg:#fff2f2;
      --kobd:#ffcccc;
      --mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
    }
    body{
      margin:0;
      font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial;
      background:var(--bg);
      color:var(--t);
    }
    header{
      position:sticky; top:0; z-index:10;
      background:rgba(255,255,255,.9);
      backdrop-filter:saturate(140%) blur(10px);
      border-bottom:1px solid var(--b);
      padding:14px 16px;
    }
    header .row{
      max-width:1200px; margin:0 auto;
      display:flex; gap:10px; align-items:center; justify-content:space-between; flex-wrap:wrap;
    }
    header h1{ font-size:14px; margin:0; font-weight:900; letter-spacing:.2px; }
    header .sub{ color:var(--m); font-size:12px; }

    .wrap{ max-width:1200px; margin:0 auto; padding:16px; }
    .grid{ display:grid; gap:14px; grid-template-columns:1fr; }
    @media(min-width:980px){ .grid{ grid-template-columns: 360px 1fr; } }

    .card{
      background:var(--card);
      border:1px solid var(--b);
      border-radius:var(--radius);
      padding:14px;
      box-shadow:var(--shadow);
      max-width:100%;
      overflow:hidden;
    }

    .topline{
      display:flex; gap:10px; align-items:flex-start; justify-content:space-between; flex-wrap:wrap;
    }
    .title{ font-size:16px; font-weight:950; margin:0; }
    .muted{ color:var(--m); font-size:12px; }
    .mono{ font-family:var(--mono); }

    label{ display:block; font-size:12px; color:var(--m); margin:10px 0 6px; }
    input, select, textarea{
      width:100%;
      padding:10px 11px;
      border:1px solid var(--b);
      border-radius:12px;
      background:#fff;
      font-size:14px;
      outline:none;
    }
    input:focus, textarea:focus, select:focus{
      border-color:rgba(14,165,233,.55);
      box-shadow:0 0 0 4px rgba(14,165,233,.12);
    }
    textarea{ min-height:90px; resize:vertical; }

    .btns{ display:flex; gap:10px; flex-wrap:wrap; margin-top:12px; }
    button{
      border:1px solid var(--b);
      background:#fff;
      padding:10px 12px;
      border-radius:12px;
      cursor:pointer;
      font-weight:900;
      font-size:13px;
    }
    button.primary{ background:var(--accent); color:#fff; border-color:var(--accent); }
    button.secondary{
      background:rgba(14,165,233,.08);
      border-color:rgba(14,165,233,.35);
      color:#075985;
    }
    button.danger{ background:#fff; border-color:rgba(176,0,32,.2); color:var(--danger); }
    button:disabled{ opacity:.55; cursor:not-allowed; }

    .hr{ height:1px; background:var(--b); margin:14px 0; }

    .kpi{ display:flex; gap:10px; flex-wrap:wrap; margin-top:10px; }
    .kpi .box{
      border:1px solid var(--b);
      border-radius:14px;
      padding:10px 12px;
      background:linear-gradient(180deg,#fff, #fbfbfe);
      min-width:140px;
    }
    .kpi .box b{ display:block; font-size:18px; }

    .hide{ display:none !important; }
    .row2{ display:flex; gap:10px; flex-wrap:wrap; }
    .row2 > *{ flex:1 1 260px; min-width:260px; }

    .pill{
      display:inline-block; padding:3px 10px;
      border-radius:999px;
      font-size:12px;
      border:1px solid var(--b);
      font-weight:950;
    }
    .ok{ border-color:var(--okbd); background:var(--okbg); }
    .ko{ border-color:var(--kobd); background:var(--kobg); }

    .tag{
      display:inline-block;
      padding:3px 10px;
      border:1px solid var(--b);
      border-radius:999px;
      font-size:12px;
      color:var(--m);
      background:#fff;
      font-weight:800;
    }

    .right{ text-align:right; }

    .controlCard{
      border:1px solid var(--b);
      border-radius:16px;
      padding:12px;
      background:#fff;
      margin-top:10px;
    }
    .controlTitle{
      display:flex; align-items:center; justify-content:space-between;
      gap:10px; flex-wrap:wrap;
    }
    .controlTitle b{ font-size:14px; font-weight:950; }

    .smallbtn{ padding:7px 10px; border-radius:10px; font-size:12px; }

    .tableWrap{
      overflow:auto;
      border:1px solid var(--b);
      border-radius:14px;
      background:#fff;
      max-width:100%;
    }
    table{
      border-collapse:separate;
      border-spacing:0;
      font-size:13px;
      width:max-content;
      min-width:100%;
    }
    th, td{
      border-bottom:1px solid var(--b);
      padding:10px 10px;
      text-align:left;
      vertical-align:top;
      white-space:nowrap;
    }
    th{
      position:sticky;
      top:0;
      background:#fff;
      z-index:2;
      font-size:12px;
      color:var(--m);
      font-weight:950;
    }
    tr:hover td{ background:#fafaff; }

    .cellWrap{
      max-width:320px;
      white-space:normal;
      line-height:1.25;
    }
    .aster{
      color:var(--accent2);
      font-weight:950;
      margin-left:6px;
    }
    .noteBox{
      margin-top:8px;
      padding:10px 12px;
      border:1px dashed rgba(14,165,233,.35);
      background:rgba(14,165,233,.06);
      border-radius:14px;
      color:#075985;
      font-size:12px;
      line-height:1.35;
    }
  </style>
</head>

<body>
<header>
  <div class="row">
    <div>
      <h1>Registro Controlli (Cloud)</h1>
      <div class="sub">Dati salvati nel cloud (Firestore). Versione prototipo.</div>
    </div>
    <div class="muted" id="dbStatus">DB: pronto</div>
  </div>
</header>

<div class="wrap">
  <div class="grid">

    <!-- LEFT -->
    <div class="card">
      <div class="topline">
        <div>
          <div class="muted">Apri scheda prodotto</div>
          <div class="title">Ricerca codice</div>
        </div>
      </div>

      <label>Codice prodotto (maiuscole/minuscole indifferenti)</label>
      <input id="codeInput" placeholder="Es. 2ag1c / 2AG1C" autocomplete="off" />

      <div class="btns">
        <button class="primary" id="openBtn">Apri</button>
        <button id="homeBtn">Home</button>
        <button class="secondary" id="allProductsBtn">Tutti i prodotti</button>
      </div>

      <div class="hr"></div>

      <div class="topline">
        <b>Export / Backup</b>
        <span class="tag">Consigliato</span>
      </div>
      <div class="muted">Backup JSON per sicurezza. Export CSV apribile in Excel.</div>

      <div class="btns">
        <button id="exportProdCsvBtnLeft" class="secondary">Export prodotto (CSV)</button>
        <button id="exportAllCsvBtn">Esporta TUTTO (CSV)</button>
        <button id="backupJsonBtn">Backup (JSON)</button>
        <label style="margin:0">
          <input type="file" id="restoreJsonFile" accept=".json" style="display:none" />
          <button id="restoreJsonBtn">Ripristina (JSON)</button>
        </label>
      </div>

      <div class="hr"></div>

      <div class="topline">
        <b>Admin</b>
        <span class="tag">Cloud</span>
      </div>

      <div class="btns">
        <button class="danger" id="wipeBtn">Svuota database cloud</button>
      </div>

      <div class="kpi">
        <div class="box"><b id="kpiProducts">0</b><span class="muted">Prodotti</span></div>
        <div class="box"><b id="kpiChecks">0</b><span class="muted">Controlli</span></div>
      </div>
    </div>

    <!-- RIGHT MAIN -->
    <div class="card">

      <!-- HOME -->
      <div id="viewHome">
        <div class="topline">
          <div>
            <div class="muted">Start</div>
            <div class="title">Home</div>
          </div>
        </div>
        <div class="muted" style="margin-top:10px; line-height:1.5;">
          Scrivi un codice e premi <b>Apri</b>. Se registri un lotto già usato, il sistema ti chiede conferma.
        </div>

        <!-- MOVED HERE -->
        <div class="hr"></div>

        <div class="topline">
          <div>
            <div class="muted">Panoramica</div>
            <div class="title">Ultimi 5 prodotti controllati</div>
          </div>
          <span class="tag">Rapido</span>
        </div>

        <div class="muted">
          Lotto e firma dell’ultimo controllo. Clicca per aprire la scheda prodotto.
        </div>

        <div id="homeRecentProducts" style="margin-top:12px"></div>
      </div>

      <!-- ALL PRODUCTS -->
      <div id="viewAllProducts" class="hide">
        <div class="topline">
          <div>
            <div class="muted">Elenco</div>
            <div class="title">Tutti i prodotti</div>
          </div>
          <div class="btns" style="margin-top:0">
            <button id="backFromAllProductsBtn">Home</button>
          </div>
        </div>

        <div class="tableWrap" style="margin-top:12px;">
          <table>
            <thead>
              <tr>
                <th>Codice</th>
                <th>Nome</th>
                <th class="right">N° controlli</th>
                <th>Ultimo controllo</th>
                <th>Lotto</th>
                <th>Effettuato da</th>
                <th class="right">Apri</th>
              </tr>
            </thead>
            <tbody id="allProductsBody"></tbody>
          </table>
        </div>
      </div>

      <!-- PRODUCT -->
      <div id="viewProduct" class="hide">
        <div class="topline">
          <div>
            <div class="muted">Scheda prodotto</div>
            <div class="title" id="prodTitle">—</div>
            <div class="muted" id="prodMeta">—</div>
          </div>
          <div class="btns" style="margin-top:0">
            <button id="editSetupBtn">Setup controlli</button>
            <button class="primary" id="newCheckBtn">Nuovo controllo</button>
            <button id="historyBtn">Storico</button>
          </div>
        </div>

        <div class="hr"></div>

        <div class="topline">
          <b>NOTE (operative fisse)</b>
          <span class="tag">Sempre visibili</span>
        </div>
        <div class="controlCard">
          <div class="muted" id="noteHint">—</div>
          <div id="noteText" style="white-space:pre-wrap; margin-top:6px;"></div>
        </div>

        <div class="hr"></div>

        <div class="topline">
          <b>Standard attuali</b>
          <span class="tag">Setup</span>
        </div>
        <div class="tableWrap" style="margin-top:10px;">
          <table id="stdTable">
            <thead>
              <tr>
                <th>Controllo</th>
                <th>Tipo</th>
                <th>Spec</th>
                <th>Unità</th>
                <th class="right">Stato</th>
              </tr>
            </thead>
            <tbody></tbody>
          </table>
        </div>

        <div class="hr"></div>

        <div class="topline">
          <b>Ultimi 5 controlli (vista rapida)</b>
          <span class="tag">Confronto veloce</span>
        </div>

        <div class="tableWrap" style="margin-top:10px;">
          <table id="lastChecksTable">
            <thead id="lastChecksHead"></thead>
            <tbody id="lastChecksBody"></tbody>
          </table>
        </div>
      </div>

      <!-- NEW PRODUCT -->
      <div id="viewNewProduct" class="hide">
        <div class="topline">
          <div>
            <div class="muted">Nuovo prodotto</div>
            <div class="title" id="newProdCode">—</div>
          </div>
          <button id="cancelNewProdBtn">Annulla</button>
        </div>

        <label>Nome prodotto</label>
        <input id="newProdName" placeholder="Nome prodotto..." />

        <label>NOTE (operative fisse)</label>
        <textarea id="newProdNOTE" placeholder="Note operative fisse (visibili sempre)"></textarea>

        <div class="hr"></div>

        <div class="topline">
          <b>Setup controlli</b>
          <span class="tag">Puoi eliminare</span>
        </div>
        <div class="muted">Se lo standard resta vuoto, quel controllo non viene richiesto durante il controllo.</div>

        <div id="setupControlsNew"></div>

        <div class="btns">
          <button id="addCustomControlBtnNew" class="secondary">+ Aggiungi nuovo controllo</button>
          <button class="primary" id="saveNewProdBtn">Salva prodotto</button>
        </div>
      </div>

      <!-- SETUP -->
      <div id="viewSetup" class="hide">
        <div class="topline">
          <div>
            <div class="muted">Setup controlli</div>
            <div class="title" id="setupTitle">—</div>
          </div>
          <div class="btns" style="margin-top:0">
            <button id="setupBackBtn">Torna a scheda</button>
            <button class="primary" id="setupSaveBtn">Salva setup</button>
          </div>
        </div>

        <label>NOTE (operative fisse)</label>
        <textarea id="setupNOTE"></textarea>

        <div class="hr"></div>

        <div class="topline">
          <b>Controlli</b>
          <span class="tag">Attiva / Elimina</span>
        </div>
        <div id="setupControlsEdit"></div>

        <div class="btns">
          <button id="addCustomControlBtnEdit" class="secondary">+ Aggiungi nuovo controllo</button>
        </div>
      </div>

      <!-- NEW CHECK -->
      <div id="viewNewCheck" class="hide">
        <div class="topline">
          <div>
            <div class="muted">Nuovo controllo</div>
            <div class="title" id="checkProdTitle">—</div>
          </div>
          <button id="cancelCheckBtn">Annulla</button>
        </div>

        <!-- NOTE fisse prima voce -->
        <div class="hr"></div>
        <div class="topline">
          <b>NOTE (operative fisse)</b>
          <span class="tag">Prima voce</span>
        </div>
        <div class="controlCard">
          <div class="muted">Note fisse prodotto:</div>
          <div id="checkNOTEfixed" style="white-space:pre-wrap; margin-top:6px;"></div>
        </div>

        <div class="hr"></div>

        <div class="row2">
          <div>
            <label>Data/ora (automatica)</label>
            <input id="checkDate" type="datetime-local" disabled />
          </div>
          <div>
            <label>Lotto (obbligatorio)</label>
            <input id="checkLotto" placeholder="Inserisci lotto..." />
          </div>
        </div>

        <div class="hr"></div>

        <div class="topline">
          <b>Controlli</b>
          <span class="tag">OK / Fuori STD</span>
        </div>
        <div class="muted">Mostro solo i controlli che hanno uno standard compilato.</div>

        <div id="checkRows" style="margin-top:10px"></div>

        <div class="hr"></div>

        <div class="topline">
          <b>Campi sempre presenti</b>
          <span class="tag">Meta</span>
        </div>

        <label>Aggiunte</label>
        <textarea id="checkAggiunte" placeholder="Aggiunte / correzioni fatte..."></textarea>

        <label>Note</label>
        <textarea id="checkNote" placeholder="Note generali..."></textarea>

        <div class="row2">
          <div>
            <label>Prodotto da</label>
            <input id="checkProdottoDa" placeholder="Sigla / cognome" />
          </div>
          <div>
            <label>Effettuato da</label>
            <input id="checkEffettuatoDa" placeholder="Sigla / cognome" />
          </div>
        </div>

        <div class="btns">
          <button class="primary" id="saveCheckBtn">Salva controllo</button>
        </div>
      </div>

      <!-- HISTORY -->
      <div id="viewHistory" class="hide">
        <div class="topline">
          <div>
            <div class="muted">Storico controlli</div>
            <div class="title" id="histTitle">—</div>
          </div>
          <div class="btns" style="margin-top:0">
            <button id="backToProdBtn">Torna a scheda</button>
            <button id="exportHistCsvBtn" class="secondary">Esporta (CSV)</button>
          </div>
        </div>

        <div class="row2">
          <div>
            <label>Filtro esito</label>
            <select id="filterOutcome">
              <option value="all">Tutti</option>
              <option value="OK">OK</option>
              <option value="FUORI_STD">Fuori STD</option>
            </select>
          </div>
          <div>
            <label>Da (data)</label>
            <input id="filterFrom" type="date" />
          </div>
          <div>
            <label>A (data)</label>
            <input id="filterTo" type="date" />
          </div>
        </div>

        <div class="tableWrap" style="margin-top:12px;">
          <table id="histTable">
            <thead id="histHead"></thead>
            <tbody id="histBody"></tbody>
          </table>
        </div>
      </div>

      <!-- CHECK DETAIL (dedicated page) -->
      <div id="viewCheckDetail" class="hide">
        <div class="topline">
          <div>
            <div class="muted">Dettaglio controllo</div>
            <div class="title" id="detailTitle">—</div>
            <div class="muted" id="detailMeta">—</div>
          </div>
          <div class="btns" style="margin-top:0">
            <button id="detailBackBtn">Indietro</button>
            <button class="primary" id="detailSaveBtn">Salva modifiche</button>
          </div>
        </div>

        <div class="hr"></div>

        <div class="topline">
          <b>NOTE (operative fisse)</b>
          <span class="tag">Riferimento</span>
        </div>
        <div class="controlCard">
          <div class="muted">Note fisse prodotto:</div>
          <div id="detailNOTEfixed" style="white-space:pre-wrap; margin-top:6px;"></div>
        </div>

        <div class="hr"></div>

        <div class="row2">
          <div>
            <label>Data/ora</label>
            <input id="detailDate" type="datetime-local" disabled />
          </div>
          <div>
            <label>Lotto</label>
            <input id="detailLotto" />
          </div>
        </div>

        <div class="hr"></div>

        <div class="topline">
          <b>Valori controlli</b>
          <span class="tag">Modificabili (tutti attivi)</span>
        </div>

        <div id="detailControls"></div>

        <div class="hr"></div>

        <div class="topline">
          <b>Meta</b>
          <span class="tag">Aggiunte / Note / Firme</span>
        </div>

        <label>Aggiunte</label>
        <textarea id="detailAggiunte"></textarea>

        <label>Note</label>
        <textarea id="detailNote"></textarea>

        <div class="row2">
          <div>
            <label>Prodotto da</label>
            <input id="detailProdottoDa" />
          </div>
          <div>
            <label>Effettuato da</label>
            <input id="detailEffettuatoDa" />
          </div>
        </div>

        <div class="muted" style="margin-top:10px">
          Campi modificati → indicati con <b>*</b>. Ogni controllo tiene traccia della modifica (quando + valore precedente).
        </div>
      </div>

    </div>
  </div>
</div>

<script type="module">

/* =========================
   DEFAULT CONTROLS
========================= */
const DEFAULT_CONTROLS = [
  { key:"viscosita",     name:"Viscosità",      type:"num_minmax", unit:"cP",       enabled:true, spec:{min:null,max:null}, extra:{} },
  { key:"macinazione",   name:"Macinazione",    type:"num_max",    unit:"µm",       enabled:true, spec:{max:null},          extra:{} },
  { key:"brillantezza",  name:"Brillantezza",   type:"num_minmax", unit:"gloss",    enabled:true, spec:{min:null,max:null}, extra:{ thickness_um:null } },
  { key:"peso_spec",     name:"Peso specifico", type:"num_minmax", unit:"Kg/L",     enabled:true, spec:{min:null,max:null}, extra:{} },
  { key:"conducibilita", name:"Conducibilità",  type:"num_minmax", unit:"MOhm*cm",  enabled:true, spec:{min:null,max:null}, extra:{} },
  { key:"ph",            name:"pH",             type:"num_minmax", unit:"",         enabled:true, spec:{min:null,max:null}, extra:{} }
];
const CHECK_ENTRY_ORDER = ["viscosita","macinazione","brillantezza","peso_spec","conducibilita","ph"];

/* =========================
   Firebase (Firestore)
========================= */
// IMPORTANT:
// - This file must be opened via HTTP(S) (e.g., Netlify/GitHub Pages), NOT via file://
//   because ES Modules (Firebase CDN imports) are blocked by browsers on file://.

import { initializeApp } from "https://www.gstatic.com/firebasejs/10.12.4/firebase-app.js";
import {
  getFirestore,
  collection, doc,
  getDoc, setDoc, deleteDoc,
  getDocs,
  query, where, orderBy, limit,
  enableIndexedDbPersistence
} from "https://www.gstatic.com/firebasejs/10.12.4/firebase-firestore.js";

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyA9C__WCy6O0MXFcAvsZE9ffrlgL-LwS6E",
  authDomain: "controlli-qualita.firebaseapp.com",
  projectId: "controlli-qualita",
  storageBucket: "controlli-qualita.firebasestorage.app",
  messagingSenderId: "1051668384383",
  appId: "1:1051668384383:web:bfaf1d99f9c9b7f8c74d4a",
  measurementId: "G-B40QTFGQFH"
};
// Initialize Firebase
const app = initializeApp(firebaseConfig);
const fs = getFirestore(app);

// Make writes feel instant: enable local persistence (IndexedDB).
// If multiple tabs are open, Firestore may refuse persistence (safe to ignore).
enableIndexedDbPersistence(fs).catch(() => {});

// Collections
const COL_PRODUCTS = "products";
const COL_CHECKS = "checks";

// Store names (legacy-compatible)
const STORES = { products: 'products', checks: 'checks' };

// Global UI state (modules are strict: declare everything)
let currentCode = null;
let cachedProduct = null;
let workingControlsNew = null;
let workingControlsEdit = null;
let lastReturnView = 'home';

// Compat layer (keeps most of your code unchanged)
function tx(storeNames, mode="readonly"){
  return {
    objectStore: (name) => ({ __name: name }),
    mode
  };
}

async function put(store, value){
  if(store.__name === STORES.products){
    await setDoc(doc(fs, COL_PRODUCTS, value.code), value);
    return true;
  }
  if(store.__name === STORES.checks){
    await setDoc(doc(fs, COL_CHECKS, value.id), value);
    return true;
  }
  throw new Error("Store non valido: " + store.__name);
}

async function get(store, key){
  if(store.__name === STORES.products){
    const snap = await getDoc(doc(fs, COL_PRODUCTS, key));
    return snap.exists() ? snap.data() : null;
  }
  if(store.__name === STORES.checks){
    const snap = await getDoc(doc(fs, COL_CHECKS, key));
    return snap.exists() ? snap.data() : null;
  }
  throw new Error("Store non valido: " + store.__name);
}

async function getAll(store){
  if(store.__name === STORES.products){
    const snap = await getDocs(collection(fs, COL_PRODUCTS));
    return snap.docs.map(d => d.data());
  }
  if(store.__name === STORES.checks){
    const snap = await getDocs(collection(fs, COL_CHECKS));
    return snap.docs.map(d => d.data());
  }
  throw new Error("Store non valido: " + store.__name);
}

// Used by: getChecks(code) and findChecksByLotto(lotto)
async function getAllByIndex(store, indexName, value){
  if(store.__name !== STORES.checks) throw new Error("Index su store non supportato: " + store.__name);

  if(indexName === "by_code"){
    // Avoid composite indexes: filter only, then sort client-side.
    const qy = query(
      collection(fs, COL_CHECKS),
      where("code", "==", value)
    );
    const snap = await getDocs(qy);
    const list = snap.docs.map(d => d.data());
    list.sort((a,b)=> (b.dateISO||"").localeCompare(a.dateISO||""));
    return list;
  }

  if(indexName === "by_lotto"){
    // Avoid composite indexes: filter only, then sort client-side.
    const qy = query(
      collection(fs, COL_CHECKS),
      where("lotto", "==", value)
    );
    const snap = await getDocs(qy);
    const list = snap.docs.map(d => d.data());
    list.sort((a,b)=> (b.dateISO||"").localeCompare(a.dateISO||""));
    return list;
  }

  if(indexName === "by_date"){
    const qy = query(collection(fs, COL_CHECKS), orderBy("dateISO", "desc"), limit(50));
    const snap = await getDocs(qy);
    return snap.docs.map(d => d.data());
  }

  throw new Error("Index non supportato: " + indexName);
}

async function wipeAllFirestore(){
  // Deletes everything in products + checks (safe for small datasets)
  const ps = await getDocs(collection(fs, COL_PRODUCTS));
  for (const d of ps.docs) {
    await deleteDoc(doc(fs, COL_PRODUCTS, d.id));
  }
  
  const cs = await getDocs(collection(fs, COL_CHECKS));
  for (const d of cs.docs) {
    await deleteDoc(doc(fs, COL_CHECKS, d.id));
  }
}

/* =========================
   Utils
========================= */
function deepClone(o){ return JSON.parse(JSON.stringify(o)); }
function uuid(){ return "id-" + Math.random().toString(16).slice(2) + "-" + Date.now().toString(16); }
function normalizeCode(s){ return String(s ?? "").trim().toUpperCase(); }
function nowLocalDatetimeValue(){ const d=new Date(); d.setMinutes(d.getMinutes()-d.getTimezoneOffset()); return d.toISOString().slice(0,16); }
function fmtDateTime(iso){
  try{ const d=new Date(iso); return d.toLocaleString("it-IT",{year:"numeric",month:"2-digit",day:"2-digit",hour:"2-digit",minute:"2-digit"}); }
  catch{ return iso; }
}
function esc(s){ return String(s ?? "").replaceAll("&","&amp;").replaceAll("<","&lt;").replaceAll(">","&gt;"); }
function toNumber(v){ if(v===""||v===null||v===undefined) return null; const n=Number(v); return Number.isFinite(n)?n:null; }
function csvEscape(v){ const s=String(v ?? ""); if(/[",\n;]/.test(s)) return '"' + s.replaceAll('"','""') + '"'; return s; }
function downloadText(filename, text){
  const blob=new Blob([text],{type:"text/plain;charset=utf-8"});
  const a=document.createElement("a");
  a.href=URL.createObjectURL(blob); a.download=filename;
  document.body.appendChild(a); a.click(); a.remove();
  URL.revokeObjectURL(a.href);
}

/* =========================
   Views
========================= */
const views = {
  home: document.getElementById("viewHome"),
  allProducts: document.getElementById("viewAllProducts"),
  product: document.getElementById("viewProduct"),
  newProduct: document.getElementById("viewNewProduct"),
  setup: document.getElementById("viewSetup"),
  newCheck: document.getElementById("viewNewCheck"),
  history: document.getElementById("viewHistory"),
  detail: document.getElementById("viewCheckDetail"),
};
function showView(name){
  Object.values(views).forEach(v=>v.classList.add("hide"));
  views[name].classList.remove("hide");
}

/* =========================
   KPI + Home Widgets
========================= */
async function refreshKPIs(){
  const t = tx([STORES.products, STORES.checks]);
  const products = await getAll(t.objectStore(STORES.products));
  const checks = await getAll(t.objectStore(STORES.checks));
  document.getElementById("kpiProducts").textContent = products.length;
  document.getElementById("kpiChecks").textContent = checks.length;
}

async function renderHomeRecentProducts(){
  const box = document.getElementById("homeRecentProducts");
  box.innerHTML = "";

  const t = tx([STORES.products, STORES.checks]);
  const products = await getAll(t.objectStore(STORES.products));
  const checks = await getAllByIndex(t.objectStore(STORES.checks), "by_date", null);


  const seen = new Set();
  const rows = [];
  for(const c of checks){
    if(seen.has(c.code)) continue;
    seen.add(c.code);
    const p = products.find(x=>x.code===c.code);
    rows.push({
      code: c.code,
      name: p?.name ?? "",
      dateISO: c.dateISO,
      lotto: c.lotto ?? "",
      by: c.meta?.effettuatoDa ?? ""
    });
    if(rows.length>=5) break;
  }

  if(rows.length===0){
    box.innerHTML = `<div class="muted">Nessun controllo registrato.</div>`;
    return;
  }

  for(const r of rows){
    const card = document.createElement("div");
    card.className = "controlCard";
    card.innerHTML = `
      <div class="topline" style="align-items:center">
        <div>
          <div style="font-weight:950">${esc(r.code)} — ${esc(r.name)}</div>
          <div class="muted">Ultimo: ${esc(fmtDateTime(r.dateISO))} • Lotto: <span class="mono">${esc(r.lotto)}</span> • Da: <span class="mono">${esc(r.by)}</span></div>
        </div>
        <button class="smallbtn secondary" data-openprod="${esc(r.code)}">Apri</button>
      </div>
    `;
    box.appendChild(card);
  }

  box.querySelectorAll("button[data-openprod]").forEach(btn=>{
    btn.addEventListener("click", async ()=>{
      const code = btn.getAttribute("data-openprod");
      await loadProduct(code);
    });
  });
}

async function renderAllProducts(){
  const body = document.getElementById("allProductsBody");
  body.innerHTML = "";

  const t = tx([STORES.products, STORES.checks]);
  const products = await getAll(t.objectStore(STORES.products));
  const checks = await getAll(t.objectStore(STORES.checks));

  const map = new Map();
  for(const c of checks){
    if(!map.has(c.code)) map.set(c.code, []);
    map.get(c.code).push(c);
  }
  for(const [k, list] of map.entries()){
    list.sort((a,b)=> (b.dateISO||"").localeCompare(a.dateISO||""));
  }

  products.sort((a,b)=> a.code.localeCompare(b.code));

  for(const p of products){
    const list = map.get(p.code) || [];
    const last = list[0] || null;

    const tr = document.createElement("tr");
    tr.innerHTML = `
      <td class="mono"><b>${esc(p.code)}</b></td>
      <td>${esc(p.name)}</td>
      <td class="right">${list.length}</td>
      <td>${last ? esc(fmtDateTime(last.dateISO)) : ""}</td>
      <td class="mono">${last ? esc(last.lotto ?? "") : ""}</td>
      <td class="mono">${last ? esc(last.meta?.effettuatoDa ?? "") : ""}</td>
      <td class="right"><button class="smallbtn secondary" data-openprod="${esc(p.code)}">Apri</button></td>
    `;
    body.appendChild(tr);
  }

  body.querySelectorAll("button[data-openprod]").forEach(btn=>{
    btn.addEventListener("click", async ()=>{
      const code = btn.getAttribute("data-openprod");
      await loadProduct(code);
    });
  });
}

/* =========================
   Product / checks helpers
========================= */
function controlTypeLabel(c){
  if(c.type==="num_minmax") return "Numerico (min/max)";
  if(c.type==="num_max") return "Numerico (solo max)";
  if(c.type==="text") return "Testo";
  return "—";
}
function describeSpec(c){
  if(!c.enabled) return "—";
  if(c.type === "text") return "Testo";
  if(c.type === "num_max"){
    const mx = c.spec?.max;
    return (mx==null) ? "(vuoto)" : `≤ ${mx}`;
  }
  if(c.type === "num_minmax"){
    const mn=c.spec?.min, mx=c.spec?.max;
    if(mn==null && mx==null) return "(vuoto)";
    if(mn!=null && mx!=null) return `${mn} → ${mx}`;
    if(mn!=null) return `≥ ${mn}`;
    return `≤ ${mx}`;
  }
  return "—";
}
function getControlByKey(controls, key){ return (controls||[]).find(c=>c.key===key) || null; }
function hasSpecToRequest(c){
  if(!c || !c.enabled) return false;
  if(c.type==="num_max") return c.spec?.max != null;
  if(c.type==="num_minmax") return (c.spec?.min != null) || (c.spec?.max != null);
  return false;
}
function specText(c){
  if(c.type==="num_max"){
    return c.spec?.max==null ? "" : `≤ ${c.spec.max}`;
  }
  if(c.type==="num_minmax"){
    const mn=c.spec?.min, mx=c.spec?.max;
    if(mn==null && mx==null) return "";
    if(mn!=null && mx!=null) return `${mn} → ${mx}`;
    if(mn!=null) return `≥ ${mn}`;
    return `≤ ${mx}`;
  }
  return "";
}
function evaluateValueAgainstSpec(c, v){
  if(c.type==="num_max"){
    if(c.spec?.max==null) return true;
    return v <= c.spec.max;
  }
  if(c.type==="num_minmax"){
    const mn=c.spec?.min, mx=c.spec?.max;
    if(mn!=null && v < mn) return false;
    if(mx!=null && v > mx) return false;
    return true;
  }
  return true;
}
async function getChecks(code, limitN=null){
  const t = tx([STORES.checks]);
  const list = await getAllByIndex(t.objectStore(STORES.checks), "by_code", code);
  return (limitN && list.length>limitN) ? list.slice(0, limitN) : list;
}
async function findChecksByLotto(lotto){
  const t = tx([STORES.checks]);
  const list = await getAllByIndex(t.objectStore(STORES.checks), "by_lotto", lotto);
  list.sort((a,b)=> (b.dateISO||"").localeCompare(a.dateISO||""));
  return list;
}
function buildControlsDisplayOrder(product){
  const keys = [...CHECK_ENTRY_ORDER];
  const rest = (product.controls||[])
    .filter(c=>c.enabled && !keys.includes(c.key))
    .map(c=>c.key);
  return [...keys, ...rest];
}
function buildEnabledControlsForColumns(product){
  const keyOrder = buildControlsDisplayOrder(product);
  return keyOrder
    .map(k => (product.controls||[]).find(c=>c.key===k))
    .filter(Boolean)
    .filter(c=>c.enabled);
}
function mapResults(check){
  const m = new Map();
  for(const r of (check.results||[])) m.set(r.key, r);
  return m;
}
function hasModFor(check, key){
  const mods = check.modifications?.[key];
  return Array.isArray(mods) && mods.length>0;
}
function lastModText(check, key){
  const mods = check.modifications?.[key];
  if(!Array.isArray(mods) || mods.length===0) return "";
  const last = mods[mods.length-1];
  return `Modificato il ${fmtDateTime(last.at)} — prima: ${last.old ?? ""} → ora: ${last.new ?? ""}`;
}

/* =========================
   Render product
========================= */
function renderStdTable(controls){
  const body = document.querySelector("#stdTable tbody");
  body.innerHTML = "";
  const list = (controls || []).slice().sort((a,b)=> a.name.localeCompare(b.name));
  for(const c of list){
    const tr = document.createElement("tr");
    const status = c.enabled ? "Attivo" : "Disattivato";
    tr.innerHTML = `
      <td><b>${esc(c.name)}</b></td>
      <td>${esc(controlTypeLabel(c))}</td>
      <td>${esc(describeSpec(c))}${c.key==="brillantezza" && c.enabled ? (c.extra?.thickness_um ? ` • a ${esc(c.extra.thickness_um)} µm` : " • a (vuoto) µm") : ""}</td>
      <td>${esc(c.unit ?? "")}</td>
      <td class="right"><span class="tag">${esc(status)}</span></td>
    `;
    body.appendChild(tr);
  }
}

function renderLastChecks5(product, checks){
  const headEl = document.getElementById("lastChecksHead");
  const body = document.getElementById("lastChecksBody");
  headEl.innerHTML = "";
  body.innerHTML = "";

  const controls = buildEnabledControlsForColumns(product);

  const trh = document.createElement("tr");
  trh.innerHTML = `
    <th>Data</th>
    <th>Lotto</th>
    <th>Esito</th>
    ${controls.map(c=>`<th>${esc(c.name)}</th>`).join("")}
    <th>Note visc.</th>
    <th>Aggiunte</th>
    <th>Note</th>
    <th>Prodotto da</th>
    <th>Effettuato da</th>
    <th class="right">Apri</th>
  `;
  headEl.appendChild(trh);

  if(checks.length===0){
    const tr = document.createElement("tr");
    tr.innerHTML = `<td colspan="${9 + controls.length}" class="muted">Nessun controllo registrato.</td>`;
    body.appendChild(tr);
    return;
  }

  for(const chk of checks.slice(0,5)){
    const resMap = mapResults(chk);
    const pillClass = (chk.outcome==="OK") ? "pill ok" : "pill ko";
    const label = (chk.outcome==="OK") ? "OK" : "Fuori STD";

    const tr = document.createElement("tr");
    tr.innerHTML = `
      <td>${esc(fmtDateTime(chk.dateISO))}</td>
      <td class="mono">${esc(chk.lotto ?? "")}</td>
      <td><span class="${pillClass}">${esc(label)}</span></td>
      ${controls.map(c=>{
        const r = resMap.get(c.key);
        const val = (r && r.value!=null) ? `${r.value}` : "";
        const mark = hasModFor(chk, c.key) ? ` <span class="aster">*</span>` : "";
        return `<td class="mono">${esc(val)}${mark}</td>`;
      }).join("")}
      <td class="cellWrap">${esc(chk.meta?.viscositaNote ?? "")}</td>
      <td class="cellWrap">${esc(chk.meta?.aggiunte ?? "")}</td>
      <td class="cellWrap">${esc(chk.meta?.note ?? "")}</td>
      <td class="mono">${esc(chk.meta?.prodottoDa ?? "")}</td>
      <td class="mono">${esc(chk.meta?.effettuatoDa ?? "")}</td>
      <td class="right"><button class="smallbtn secondary" data-open="${esc(chk.id)}">Apri</button></td>
    `;
    body.appendChild(tr);
  }

  body.querySelectorAll("button[data-open]").forEach(btn=>{
    btn.addEventListener("click", async ()=>{
      lastReturnView = "product";
      await openCheckDetailPage(btn.getAttribute("data-open"));
    });
  });
}

async function loadProduct(rawCode){
  const code = normalizeCode(rawCode);
  if(!code) return;

  const t = tx([STORES.products]);
  const p = await get(t.objectStore(STORES.products), code);

  if(!p){
    workingControlsNew = deepClone(DEFAULT_CONTROLS);
    document.getElementById("newProdCode").textContent = code;
    document.getElementById("newProdName").value = "";
    document.getElementById("newProdNOTE").value = "";
    renderSetupControls("new");
    showView("newProduct");
    return;
  }

  currentCode = code;
  cachedProduct = p;

  document.getElementById("prodTitle").textContent = `${p.code} — ${p.name}`;
  document.getElementById("prodMeta").textContent = `Creato: ${fmtDateTime(p.createdAtISO)}`;

  document.getElementById("noteHint").textContent = p.noteOperative?.trim() ? "" : "Nessuna nota impostata.";
  document.getElementById("noteText").textContent = p.noteOperative ?? "";

  renderStdTable(p.controls || []);

  const checks = await getChecks(code, 5);
  renderLastChecks5(p, checks);

  showView("product");
}

/* =========================
   Setup controls
========================= */
function controlTypeFromKey(key){
  const c = DEFAULT_CONTROLS.find(x=>x.key===key);
  return c?.type ?? "num_minmax";
}
function buildSpecEditorHtml(c){
  const k = esc(c.key);
  if(c.type === "text"){
    return `<div class="muted" style="margin-top:10px">Testo: nessuno standard.</div>`;
  }
  if(c.type === "num_max"){
    return `
      <div class="row2" style="margin-top:10px">
        <div>
          <label>Max</label>
          <input data-spec="${k}|max" type="number" step="any" value="${c.spec?.max ?? ""}" placeholder="(vuoto = non richiesto)" />
        </div>
      </div>
    `;
  }
  const extra = (c.key==="brillantezza") ? `
    <div class="row2" style="margin-top:10px">
      <div>
        <label>Brillantezza misurata a (µm)</label>
        <input data-extra="${k}|thickness_um" type="number" step="any" value="${c.extra?.thickness_um ?? ""}" placeholder="Es. 60" />
      </div>
    </div>
  ` : ``;

  return `
    <div class="row2" style="margin-top:10px">
      <div>
        <label>Min</label>
        <input data-spec="${k}|min" type="number" step="any" value="${c.spec?.min ?? ""}" placeholder="(vuoto = nessun min)" />
      </div>
      <div>
        <label>Max</label>
        <input data-spec="${k}|max" type="number" step="any" value="${c.spec?.max ?? ""}" placeholder="(vuoto = nessun max)" />
      </div>
    </div>
    ${extra}
  `;
}

function renderSetupControls(mode){
  const container = (mode==="new") ? document.getElementById("setupControlsNew") : document.getElementById("setupControlsEdit");
  const working = (mode==="new") ? workingControlsNew : workingControlsEdit;
  container.innerHTML = "";

  const keys = [...new Set(buildControlsDisplayOrder({controls:working}).concat(working.map(c=>c.key)))];

  for(const key of keys){
    const c = working.find(x=>x.key===key);
    if(!c) continue;

    const card = document.createElement("div");
    card.className = "controlCard";

    const enabledChecked = c.enabled ? "checked" : "";

    card.innerHTML = `
      <div class="controlTitle">
        <div>
          <b>${esc(c.name)}</b> <span class="tag">${esc(c.type==="num_max"?"Solo max":c.type==="num_minmax"?"Min/Max":"Testo")}</span>
        </div>
        <div class="btns" style="margin:0">
          <label class="muted" style="margin:0; display:flex; align-items:center; gap:8px;">
            <input type="checkbox" data-enable="${esc(c.key)}" ${enabledChecked} />
            Attivo
          </label>
          <button class="smallbtn danger" data-delete="${esc(c.key)}">Elimina</button>
        </div>
      </div>

      <div class="row2" style="margin-top:10px">
        <div>
          <label>Unità di misura</label>
          <input data-unit="${esc(c.key)}" value="${esc(c.unit ?? "")}" ${c.key==="macinazione" ? "disabled" : ""} />
          <div class="muted">${c.key==="macinazione" ? "Macinazione: unità fissa µm." : ""}</div>
        </div>
      </div>

      ${buildSpecEditorHtml(c)}
    `;
    container.appendChild(card);
  }

  container.querySelectorAll("input[data-enable]").forEach(cb=>{
    cb.addEventListener("change", ()=>{
      const k = cb.getAttribute("data-enable");
      const c = working.find(x=>x.key===k);
      if(!c) return;
      c.enabled = cb.checked;
      renderSetupControls(mode);
    });
  });

  container.querySelectorAll("button[data-delete]").forEach(btn=>{
    btn.addEventListener("click", ()=>{
      const k = btn.getAttribute("data-delete");
      const idx = working.findIndex(x=>x.key===k);
      if(idx<0) return;
      if(!confirm(`Eliminare il controllo "${working[idx].name}"? Non comparirà più per questo prodotto.`)) return;
      working.splice(idx,1);
      renderSetupControls(mode);
    });
  });

  container.querySelectorAll("input[data-unit]").forEach(inp=>{
    inp.addEventListener("input", ()=>{
      const k = inp.getAttribute("data-unit");
      const c = working.find(x=>x.key===k);
      if(!c) return;
      c.unit = inp.value;
    });
  });

  container.querySelectorAll("input[data-spec]").forEach(inp=>{
    inp.addEventListener("input", ()=>{
      const [k, field] = inp.getAttribute("data-spec").split("|");
      const c = working.find(x=>x.key===k);
      if(!c) return;
      const raw = inp.value.trim();
      const num = raw==="" ? null : toNumber(raw);
      if(raw!=="" && num===null) return;
      if(c.type==="num_max") c.spec.max = num;
      else if(c.type==="num_minmax"){
        if(field==="min") c.spec.min = num;
        if(field==="max") c.spec.max = num;
      }
    });
  });

  container.querySelectorAll("input[data-extra]").forEach(inp=>{
    inp.addEventListener("input", ()=>{
      const [k, field] = inp.getAttribute("data-extra").split("|");
      const c = working.find(x=>x.key===k);
      if(!c) return;
      const raw = inp.value.trim();
      const num = raw==="" ? null : toNumber(raw);
      if(raw!=="" && num===null) return;
      c.extra = c.extra || {};
      c.extra[field] = num;
    });
  });
}

function addCustomControl(mode){
  const working = (mode==="new") ? workingControlsNew : workingControlsEdit;
  const name = prompt("Nome nuovo controllo (es. Temperatura, Umidità, ecc.)");
  if(!name) return;
  const type = prompt('Tipo controllo:\n1 = Numerico (min/max)\n2 = Numerico (solo max)\n3 = Testo\n\nScrivi 1/2/3');
  if(!type) return;
  let t = null;
  if(type.trim()==="1") t="num_minmax";
  else if(type.trim()==="2") t="num_max";
  else if(type.trim()==="3") t="text";
  else return alert("Valore non valido.");
  const unit = (t==="text") ? "" : (prompt("Unità di misura (opz.)") ?? "");
  const key = "custom_" + uuid().slice(3).replaceAll("-","");
  working.push({
    key, name: name.trim(), type: t, unit: unit.trim(),
    enabled: true,
    spec: (t==="num_max") ? {max:null} : (t==="num_minmax" ? {min:null,max:null} : {}),
    extra: {}
  });
  renderSetupControls(mode);
}

/* =========================
   Save new product / setup
========================= */
async function saveNewProduct(){
  const code = normalizeCode(document.getElementById("newProdCode").textContent);
  const name = document.getElementById("newProdName").value.trim();
  if(!name) return alert("Inserisci il nome prodotto.");
  const noteOperative = document.getElementById("newProdNOTE").value ?? "";

  for(const c of workingControlsNew){
    if(c.key==="macinazione"){ c.unit="µm"; c.type="num_max"; c.spec = {max: c.spec?.max ?? null}; }
    if(c.key==="ph"){ c.unit=""; }
    if(c.key==="brillantezza"){ c.unit="gloss"; }
    if(c.key==="conducibilita"){ c.unit="MOhm*cm"; }
    if(c.key==="peso_spec"){ c.unit="Kg/L"; }
  }

  const p = { code, name, createdAtISO: new Date().toISOString(), noteOperative, controls: workingControlsNew };
  const t = tx([STORES.products], "readwrite");
  await put(t.objectStore(STORES.products), p);

  await refreshKPIs();
  await renderHomeRecentProducts();
  await loadProduct(code);
}

async function openSetup(){
  const p = cachedProduct;
  workingControlsEdit = deepClone(p.controls || deepClone(DEFAULT_CONTROLS));
  document.getElementById("setupTitle").textContent = `${p.code} — ${p.name}`;
  document.getElementById("setupNOTE").value = p.noteOperative ?? "";
  renderSetupControls("edit");
  showView("setup");
}

async function saveSetup(){
  const p = cachedProduct;
  if(!p) return;

  for(const c of workingControlsEdit){
    if(c.key==="macinazione"){ c.unit="µm"; c.type="num_max"; c.spec = {max: c.spec?.max ?? null}; }
    if(c.key==="ph"){ c.unit=""; }
    if(c.key==="brillantezza"){ c.unit="gloss"; }
    if(c.key==="conducibilita"){ c.unit="MOhm*cm"; }
    if(c.key==="peso_spec"){ c.unit="Kg/L"; }
  }

  p.noteOperative = document.getElementById("setupNOTE").value ?? "";
  p.controls = workingControlsEdit;

  const t = tx([STORES.products], "readwrite");
  await put(t.objectStore(STORES.products), p);

  await loadProduct(p.code);
}

/* =========================
   New check + duplicate lotto check
========================= */
async function startNewCheck(){
  const p = cachedProduct;
  if(!p) return;

  document.getElementById("checkProdTitle").textContent = `${p.code} — ${p.name}`;
  document.getElementById("checkDate").value = nowLocalDatetimeValue();
  document.getElementById("checkLotto").value = "";

  document.getElementById("checkNOTEfixed").textContent = p.noteOperative ?? "";
  document.getElementById("checkAggiunte").value = "";
  document.getElementById("checkNote").value = "";
  document.getElementById("checkProdottoDa").value = "";
  document.getElementById("checkEffettuatoDa").value = "";

  const container = document.getElementById("checkRows");
  container.innerHTML = "";

  const orderKeys = buildControlsDisplayOrder(p);
  let anyShown = false;

  for(const key of orderKeys){
    const c = getControlByKey(p.controls || [], key);
    if(!c) continue;
    if(!hasSpecToRequest(c)) continue;

    anyShown = true;

    const card = document.createElement("div");
    card.className = "controlCard";

    const spec = specText(c);
    const extraLine = (c.key==="brillantezza")
      ? `<div class="muted">Misurata a: <b>${esc(c.extra?.thickness_um ?? "(vuoto)")}</b> µm</div>`
      : "";

    const viscosityNoteField = (c.key==="viscosita")
      ? `
        <div class="row2" style="margin-top:10px">
          <div>
            <label>Note viscosità (es. 20/30°C, R4...)</label>
            <input data-viscnote="1" placeholder="Scrivi note viscosità..." />
          </div>
        </div>
      ` : "";

    card.innerHTML = `
      <div class="controlTitle">
        <div><b>${esc(c.name)}</b> <span class="tag">${esc(c.unit || "-")}</span></div>
        <div class="muted">Spec: <b>${esc(spec)}</b></div>
      </div>
      ${extraLine}
      <div class="row2" style="margin-top:10px">
        <div>
          <label>Valore</label>
          <input data-val="${esc(c.key)}" type="number" step="any" placeholder="Inserisci valore..." />
        </div>
        <div>
          <label>Esito</label>
          <input data-out="${esc(c.key)}" value="—" disabled />
        </div>
      </div>
      ${viscosityNoteField}
    `;
    container.appendChild(card);

    const inp = card.querySelector(`input[data-val="${CSS.escape(c.key)}"]`);
    const out = card.querySelector(`input[data-out="${CSS.escape(c.key)}"]`);

    inp.addEventListener("input", ()=>{
      const v = toNumber(inp.value);
      if(v===null){ out.value="—"; return; }
      const ok = evaluateValueAgainstSpec(c, v);
      out.value = ok ? "OK" : "Fuori STD";
    });
  }

  if(!anyShown){
    const warn = document.createElement("div");
    warn.className = "controlCard";
    warn.innerHTML = `<b>Nessun controllo con standard compilato.</b><div class="muted" style="margin-top:6px;">Puoi comunque salvare lotto + meta (aggiunte/note/firme).</div>`;
    container.appendChild(warn);
  }

  showView("newCheck");
}

async function confirmDuplicateLottoIfNeeded(lotto, ignoreCheckId=null){
  const used = await findChecksByLotto(lotto);
  const filtered = ignoreCheckId ? used.filter(x=>x.id!==ignoreCheckId) : used;
  if(filtered.length===0) return true;

  const preview = filtered.slice(0,5).map(c=> `- ${c.code} • ${fmtDateTime(c.dateISO)} • da ${c.meta?.effettuatoDa ?? ""}`).join("\n");
  return confirm(
`ATTENZIONE: lotto "${lotto}" già usato in ${filtered.length} controllo/i.\n\nEsempi:\n${preview}\n\nVuoi salvare comunque?`
  );
}

async function saveCheck(){
  const p = cachedProduct;
  if(!p) return;

  const dateLocal = document.getElementById("checkDate").value;
  const dateISO = new Date(dateLocal).toISOString();

  const lotto = document.getElementById("checkLotto").value.trim();
  if(!lotto) return alert("Il lotto è obbligatorio.");

  const okDup = await confirmDuplicateLottoIfNeeded(lotto);
  if(!okDup) return;

  const meta = {
    viscositaNote: (document.querySelector('input[data-viscnote="1"]')?.value ?? "").trim(),
    aggiunte: document.getElementById("checkAggiunte").value.trim(),
    note: document.getElementById("checkNote").value.trim(),
    prodottoDa: document.getElementById("checkProdottoDa").value.trim(),
    effettuatoDa: document.getElementById("checkEffettuatoDa").value.trim()
  };

  const results = [];
  let anyOut = false;

  const orderKeys = buildControlsDisplayOrder(p);
  for(const key of orderKeys){
    const c = getControlByKey(p.controls || [], key);
    if(!c) continue;
    if(!hasSpecToRequest(c)) continue;

    const inp = document.querySelector(`#checkRows input[data-val="${CSS.escape(c.key)}"]`);
    const v = toNumber(inp?.value ?? "");
    if(v===null) return alert(`Valore mancante per: ${c.name}`);

    const ok = evaluateValueAgainstSpec(c, v);
    if(!ok) anyOut = true;

    results.push({ key:c.key, name:c.name, value:v, unit:c.unit ?? "", ok, specText: specText(c) });
  }

  const check = {
    id: uuid(),
    code: p.code,
    dateISO,
    lotto,
    outcome: anyOut ? "FUORI_STD" : "OK",
    results,
    meta,
    modifications: {}
  };

  const btn = document.getElementById("saveCheckBtn");
  const prev = btn.textContent;
  btn.disabled = true;
  btn.textContent = "Salvataggio...";
  try{
    const t = tx([STORES.checks], "readwrite");
    await put(t.objectStore(STORES.checks), check);
  } finally {
    btn.disabled = false;
    btn.textContent = prev;
  }

  // Reload only what is needed (fast)
  await loadProduct(p.code);
}

/* =========================
   History table with asterisks
========================= */
async function renderHistory(){
  const head = document.getElementById("histHead");
  const body = document.getElementById("histBody");
  head.innerHTML = "";
  body.innerHTML = "";

  const p = cachedProduct;
  const controls = buildEnabledControlsForColumns(p);

  const trh = document.createElement("tr");
  trh.innerHTML = `
    <th>Data</th>
    <th>Lotto</th>
    <th>Esito</th>
    ${controls.map(c=>`<th>${esc(c.name)}</th>`).join("")}
    <th>Note visc.</th>
    <th>Aggiunte</th>
    <th>Note</th>
    <th>Prodotto da</th>
    <th>Effettuato da</th>
    <th class="right">Apri</th>
  `;
  head.appendChild(trh);

  const outcome = document.getElementById("filterOutcome").value;
  const from = document.getElementById("filterFrom").value;
  const to = document.getElementById("filterTo").value;

  let checks = await getChecks(currentCode);

  if(outcome !== "all") checks = checks.filter(c => c.outcome === outcome);
  if(from){
    const f = new Date(from + "T00:00:00").toISOString();
    checks = checks.filter(c => c.dateISO >= f);
  }
  if(to){
    const t2 = new Date(to + "T23:59:59").toISOString();
    checks = checks.filter(c => c.dateISO <= t2);
  }

  if(checks.length===0){
    const tr = document.createElement("tr");
    tr.innerHTML = `<td colspan="${9 + controls.length}" class="muted">Nessun risultato con questi filtri.</td>`;
    body.appendChild(tr);
    return;
  }

  for(const chk of checks){
    const resMap = mapResults(chk);
    const pillClass = (chk.outcome==="OK") ? "pill ok" : "pill ko";
    const label = (chk.outcome==="OK") ? "OK" : "Fuori STD";

    const tr = document.createElement("tr");
    tr.innerHTML = `
      <td>${esc(fmtDateTime(chk.dateISO))}</td>
      <td class="mono">${esc(chk.lotto ?? "")}</td>
      <td><span class="${pillClass}">${esc(label)}</span></td>
      ${controls.map(c=>{
        const r = resMap.get(c.key);
        const val = (r && r.value!=null) ? `${r.value}` : "";
        const mark = hasModFor(chk, c.key) ? ` <span class="aster">*</span>` : "";
        return `<td class="mono">${esc(val)}${mark}</td>`;
      }).join("")}
      <td class="cellWrap">${esc(chk.meta?.viscositaNote ?? "")}</td>
      <td class="cellWrap">${esc(chk.meta?.aggiunte ?? "")}</td>
      <td class="cellWrap">${esc(chk.meta?.note ?? "")}</td>
      <td class="mono">${esc(chk.meta?.prodottoDa ?? "")}</td>
      <td class="mono">${esc(chk.meta?.effettuatoDa ?? "")}</td>
      <td class="right"><button class="smallbtn secondary" data-open="${esc(chk.id)}">Apri</button></td>
    `;
    body.appendChild(tr);
  }

  body.querySelectorAll("button[data-open]").forEach(btn=>{
    btn.addEventListener("click", async ()=>{
      lastReturnView = "history";
      await openCheckDetailPage(btn.getAttribute("data-open"));
    });
  });
}

/* =========================
   Detail page (edit ALL enabled controls + per-control log)
========================= */
function setStar(el, on){
  let star = el.parentElement.querySelector(".aster");
  if(on){
    if(!star){
      star = document.createElement("span");
      star.className = "aster";
      star.textContent = "*";
      el.parentElement.appendChild(star);
    }
  } else {
    if(star) star.remove();
  }
}
function computeChanged(){
  return JSON.stringify(detailCheck) !== JSON.stringify(detailOriginal);
}
function updateDetailTitle(){
  const base = `${detailCheck.code} — controllo`;
  document.getElementById("detailTitle").textContent = computeChanged() ? (base + " *") : base;
}

function ensureResultForKey(checkObj, ctrl){
  checkObj.results = checkObj.results || [];
  const idx = checkObj.results.findIndex(x=>x.key===ctrl.key);
  if(idx>=0) return idx;

  checkObj.results.push({
    key: ctrl.key,
    name: ctrl.name,
    value: null,
    unit: ctrl.unit ?? "",
    ok: null,
    specText: specText(ctrl)
  });
  return checkObj.results.length-1;
}

async function openCheckDetailPage(checkId){
  const t = tx([STORES.checks]);
  const chk = await get(t.objectStore(STORES.checks), checkId);
  if(!chk) return alert("Controllo non trovato.");

  detailCheck = deepClone(chk);
  detailOriginal = deepClone(chk);

  detailCheck.modifications = detailCheck.modifications || {};
  detailOriginal.modifications = detailOriginal.modifications || {};

  const p = cachedProduct;
  document.getElementById("detailNOTEfixed").textContent = p?.noteOperative ?? "";

  document.getElementById("detailMeta").textContent =
    `${fmtDateTime(chk.dateISO)} • Lotto: ${chk.lotto ?? ""} • Esito: ${chk.outcome==="OK" ? "OK" : "Fuori STD"}`;

  const d = new Date(chk.dateISO);
  d.setMinutes(d.getMinutes()-d.getTimezoneOffset());
  document.getElementById("detailDate").value = d.toISOString().slice(0,16);

  const lottoEl = document.getElementById("detailLotto");
  lottoEl.value = chk.lotto ?? "";
  lottoEl.oninput = () => { detailCheck.lotto = lottoEl.value; setStar(lottoEl, detailCheck.lotto !== detailOriginal.lotto); updateDetailTitle(); };
  setStar(lottoEl, false);

  const wrap = document.getElementById("detailControls");
  wrap.innerHTML = "";

  const controls = buildEnabledControlsForColumns(p);
  for(const ctrl of controls){
    const idx = ensureResultForKey(detailCheck, ctrl);
    ensureResultForKey(detailOriginal, ctrl);

    const r = detailCheck.results[idx];

    const card = document.createElement("div");
    card.className = "controlCard";

    const modText = lastModText(detailCheck, ctrl.key);

    card.innerHTML = `
      <div class="controlTitle">
        <div><b>${esc(ctrl.name)}</b> <span class="tag">${esc(ctrl.unit || "-")}</span></div>
        <div class="muted">Spec: <b>${esc(specText(ctrl))}</b></div>
      </div>

      ${modText ? `<div class="noteBox">${esc(modText)}</div>` : ``}

      <div class="row2" style="margin-top:10px">
        <div>
          <label>Valore</label>
          <input data-k="${esc(ctrl.key)}" type="number" step="any" />
        </div>
        <div>
          <label>Esito</label>
          <input data-o="${esc(ctrl.key)}" disabled />
        </div>
      </div>

      ${ctrl.key==="viscosita" ? `
        <div class="row2" style="margin-top:10px">
          <div>
            <label>Note viscosità</label>
            <input id="detailViscNote" placeholder="Es. 20/30°C, R4..." />
          </div>
        </div>
      ` : ``}
    `;
    wrap.appendChild(card);

    const valEl = card.querySelector(`input[data-k="${CSS.escape(ctrl.key)}"]`);
    const outEl = card.querySelector(`input[data-o="${CSS.escape(ctrl.key)}"]`);

    const orig = detailOriginal.results.find(x=>x.key===ctrl.key);
    valEl.value = (r.value ?? "");
    outEl.value = (r.ok===true) ? "OK" : (r.ok===false ? "Fuori STD" : "—");

    valEl.oninput = () => {
      const v = toNumber(valEl.value);
      if(v===null){
        r.value = null;
        r.ok = null;
        outEl.value = "—";
        setStar(valEl, String(valEl.value) !== String(orig?.value ?? ""));
        updateDetailTitle();
        return;
      }

      const ok = evaluateValueAgainstSpec(ctrl, v);
      r.value = v;
      r.ok = ok;
      r.specText = specText(ctrl);
      outEl.value = ok ? "OK" : "Fuori STD";

      detailCheck.outcome = detailCheck.results.some(x=>x.ok===false) ? "FUORI_STD" : "OK";

      setStar(valEl, String(v) !== String(orig?.value ?? ""));
      updateDetailTitle();
    };

    setStar(valEl, false);
  }

  const aEl = document.getElementById("detailAggiunte");
  const nEl = document.getElementById("detailNote");
  const pdEl = document.getElementById("detailProdottoDa");
  const edEl = document.getElementById("detailEffettuatoDa");

  detailCheck.meta = detailCheck.meta || {};
  detailOriginal.meta = detailOriginal.meta || {};

  aEl.value = detailCheck.meta.aggiunte ?? "";
  nEl.value = detailCheck.meta.note ?? "";
  pdEl.value = detailCheck.meta.prodottoDa ?? "";
  edEl.value = detailCheck.meta.effettuatoDa ?? "";

  const bindMeta = (el, key) => {
    el.oninput = () => { detailCheck.meta[key] = el.value; setStar(el, (detailCheck.meta[key] ?? "") !== (detailOriginal.meta[key] ?? "")); updateDetailTitle(); };
    setStar(el, false);
  };
  bindMeta(aEl, "aggiunte");
  bindMeta(nEl, "note");
  bindMeta(pdEl, "prodottoDa");
  bindMeta(edEl, "effettuatoDa");

  const vn = document.getElementById("detailViscNote");
  if(vn){
    vn.value = detailCheck.meta.viscositaNote ?? "";
    vn.oninput = () => { detailCheck.meta.viscositaNote = vn.value; setStar(vn, (detailCheck.meta.viscositaNote ?? "") !== (detailOriginal.meta.viscositaNote ?? "")); updateDetailTitle(); };
    setStar(vn, false);
  }

  updateDetailTitle();
  showView("detail");
}

async function saveDetail(){
  if(!detailCheck) return;

  const lotto = String(detailCheck.lotto ?? "").trim();
  if(!lotto) return alert("Il lotto è obbligatorio.");

  const okDup = await confirmDuplicateLottoIfNeeded(lotto, detailCheck.id);
  if(!okDup) return;

  const nowISO = new Date().toISOString();
  detailCheck.modifications = detailCheck.modifications || {};

  const origMap = new Map((detailOriginal.results||[]).map(r=>[r.key, r]));
  for(const r of (detailCheck.results||[])){
    const o = origMap.get(r.key);
    const oldV = (o?.value ?? null);
    const newV = (r.value ?? null);

    if(String(oldV) !== String(newV)){
      detailCheck.modifications[r.key] = detailCheck.modifications[r.key] || [];
      detailCheck.modifications[r.key].push({ at: nowISO, old: oldV, new: newV });
    }
  }

  detailCheck.outcome = (detailCheck.results||[]).some(x=>x.ok===false) ? "FUORI_STD" : "OK";

  const t = tx([STORES.checks], "readwrite");
  await put(t.objectStore(STORES.checks), detailCheck);

  detailOriginal = deepClone(detailCheck);
  updateDetailTitle();

  const checks = await getChecks(currentCode);
  renderLastChecks5(cachedProduct, checks);
  if(lastReturnView === "history") await renderHistory();

  await renderHomeRecentProducts();
  alert("Modifiche salvate.");
}

/* =========================
   Export / backup
========================= */
async function exportChecksCSV(checks, filename){
  const p = cachedProduct;
  if(!p) return alert("Apri prima un prodotto.");

  const controls = buildEnabledControlsForColumns(p);

  const baseCols = ["Codice","Data","Lotto","Esito"];
  const ctrlValCols = controls.map(c=>`VAL_${c.name}`);
  const ctrlModCols = controls.map(c=>`MOD_${c.name}`);
  const metaCols = ["Note viscosità","Aggiunte","Note","Prodotto da","Effettuato da"];

  const cols = [...baseCols, ...ctrlValCols, ...ctrlModCols, ...metaCols];
  let csv = cols.map(csvEscape).join(";") + "\n";

  for(const chk of checks){
    const resMap = mapResults(chk);
    const row = [
      chk.code,
      fmtDateTime(chk.dateISO),
      chk.lotto ?? "",
      (chk.outcome==="OK" ? "OK" : "Fuori STD"),
      ...controls.map(c=>{
        const r = resMap.get(c.key);
        return (r && r.value!=null) ? r.value : "";
      }),
      ...controls.map(c=>{
        return hasModFor(chk, c.key) ? "*" : "";
      }),
      chk.meta?.viscositaNote ?? "",
      chk.meta?.aggiunte ?? "",
      chk.meta?.note ?? "",
      chk.meta?.prodottoDa ?? "",
      chk.meta?.effettuatoDa ?? ""
    ];
    csv += row.map(csvEscape).join(";") + "\n";
  }

  downloadText(filename, csv);
}

async function makeBackup(){
  const t=tx([STORES.products,STORES.checks]);
  const products=await getAll(t.objectStore(STORES.products));
  const checks=await getAll(t.objectStore(STORES.checks));
  return { version: 6, createdAtISO: new Date().toISOString(), products, checks };
}
async function restoreBackup(obj){
  if(!obj || !Array.isArray(obj.products) || !Array.isArray(obj.checks)){
    throw new Error("Formato backup non valido.");
  }
  const t=tx([STORES.products,STORES.checks],"readwrite");
  await new Promise((res,rej)=>{ const r=t.objectStore(STORES.products).clear(); r.onsuccess=res; r.onerror=()=>rej(r.error); });
  await new Promise((res,rej)=>{ const r=t.objectStore(STORES.checks).clear(); r.onsuccess=res; r.onerror=()=>rej(r.error); });
  for(const p of obj.products) await put(t.objectStore(STORES.products), p);
  for(const c of obj.checks) await put(t.objectStore(STORES.checks), c);
}

/* =========================
   Handlers
========================= */
document.getElementById("codeInput").addEventListener("input", (e)=>{
  e.target.value = e.target.value.toUpperCase();
});

document.getElementById("openBtn").addEventListener("click", async ()=>{
  const code = normalizeCode(document.getElementById("codeInput").value);
  if(!code) return alert("Inserisci un codice.");
  await loadProduct(code);
});

document.getElementById("homeBtn").addEventListener("click", async ()=>{
  currentCode=null;
  cachedProduct=null;
  document.getElementById("codeInput").value = "";
  showView("home");
  await refreshKPIs();
  await renderHomeRecentProducts();
});

document.getElementById("allProductsBtn").addEventListener("click", async ()=>{
  await renderAllProducts();
  showView("allProducts");
});

document.getElementById("backFromAllProductsBtn").addEventListener("click", async ()=>{
  showView("home");
  await renderHomeRecentProducts();
});

document.getElementById("cancelNewProdBtn").addEventListener("click", ()=> showView("home"));
document.getElementById("saveNewProdBtn").addEventListener("click", saveNewProduct);

document.getElementById("editSetupBtn").addEventListener("click", openSetup);
document.getElementById("setupBackBtn").addEventListener("click", async ()=> loadProduct(currentCode));
document.getElementById("setupSaveBtn").addEventListener("click", saveSetup);

document.getElementById("addCustomControlBtnNew").addEventListener("click", ()=> addCustomControl("new"));
document.getElementById("addCustomControlBtnEdit").addEventListener("click", ()=> addCustomControl("edit"));

document.getElementById("newCheckBtn").addEventListener("click", startNewCheck);
document.getElementById("cancelCheckBtn").addEventListener("click", async ()=> loadProduct(currentCode));
document.getElementById("saveCheckBtn").addEventListener("click", saveCheck);

document.getElementById("historyBtn").addEventListener("click", async ()=>{
  if(!cachedProduct) return;
  document.getElementById("histTitle").textContent = `${cachedProduct.code} — ${cachedProduct.name}`;
  document.getElementById("filterOutcome").value = "all";
  document.getElementById("filterFrom").value = "";
  document.getElementById("filterTo").value = "";
  await renderHistory();
  showView("history");
});
document.getElementById("backToProdBtn").addEventListener("click", async ()=> loadProduct(currentCode));
document.getElementById("filterOutcome").addEventListener("change", renderHistory);
document.getElementById("filterFrom").addEventListener("change", renderHistory);
document.getElementById("filterTo").addEventListener("change", renderHistory);

document.getElementById("detailBackBtn").addEventListener("click", async ()=>{
  if(lastReturnView === "history"){
    showView("history");
  } else {
    await loadProduct(currentCode);
  }
});
document.getElementById("detailSaveBtn").addEventListener("click", saveDetail);

document.getElementById("exportHistCsvBtn").addEventListener("click", async ()=>{
  const checks = await getChecks(currentCode);
  await exportChecksCSV(checks, `storico_${currentCode}.csv`);
});
document.getElementById("exportProdCsvBtnLeft").addEventListener("click", async ()=>{
  if(!cachedProduct) return alert("Apri prima un prodotto.");
  const checks = await getChecks(currentCode);
  await exportChecksCSV(checks, `storico_${currentCode}.csv`);
});
document.getElementById("exportAllCsvBtn").addEventListener("click", async ()=>{
  if(!cachedProduct) return alert("Apri prima un prodotto (serve per colonne e ordine).");
  const t = tx([STORES.checks]);
  const all = await getAll(t.objectStore(STORES.checks));
  all.sort((a,b)=> (b.dateISO||"").localeCompare(a.dateISO||""));
  await exportChecksCSV(all, `storico_TUTTO.csv`);
});

document.getElementById("backupJsonBtn").addEventListener("click", async ()=>{
  const b=await makeBackup();
  downloadText(`backup_qc_${new Date().toISOString().slice(0,10)}.json`, JSON.stringify(b,null,2));
});
document.getElementById("restoreJsonBtn").addEventListener("click", ()=> document.getElementById("restoreJsonFile").click());
document.getElementById("restoreJsonFile").addEventListener("change", async (e)=>{
  const f=e.target.files?.[0]; if(!f) return;
  const txt=await f.text();
  try{
    const obj=JSON.parse(txt);
    if(!confirm("Ripristinare il backup? Sovrascrive i dati attuali.")) return;
    await restoreBackup(obj);
    alert("Ripristino completato.");
    showView("home");
    await refreshKPIs();
    await renderHomeRecentProducts();
  }catch(err){
    alert("Errore ripristino: " + err.message);
  }finally{
    e.target.value="";
  }
});
document.getElementById("wipeBtn").addEventListener("click", async ()=>{
  if(!confirm("Sicuro? Elimina TUTTO il database (cloud).")) return;
  await wipeAllFirestore();
  currentCode=null; cachedProduct=null;
  document.getElementById("codeInput").value = "";
  showView("home");
  await refreshKPIs();
  await renderHomeRecentProducts();
  alert("Database (cloud) svuotato.");
});

/* =========================
   Init
========================= */
(async function init(){
  try{
    // Quick sanity check
    document.getElementById("dbStatus").textContent = "DB: connesso";
    showView("home");
    await refreshKPIs();
    await renderHomeRecentProducts();
  }catch(err){
    document.getElementById("dbStatus").textContent = "DB: ERRORE";
    alert("Errore DB: " + err.message);
  }
})();
</script>
</body>
</html>
