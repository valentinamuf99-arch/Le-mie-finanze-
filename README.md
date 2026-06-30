# Le mie finanze — PWA

## Come pubblicare l'app su GitHub Pages (gratuito)

### 1. Crea un account GitHub
Se non ce l'hai, vai su https://github.com e registrati.

### 2. Crea un nuovo repository
- Clicca il pulsante verde **"New"** o vai su https://github.com/new
- Nome repository: `le-mie-finanze` (o quello che preferisci)
- Seleziona **Private** (così solo tu puoi vederlo)
- Clicca **Create repository**

### 3. Carica i file
- Nella pagina del repository clicca **"uploading an existing file"**
- Trascina TUTTI i file e cartelle di questa cartella:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icons/` (tutta la cartella)
- Scrivi un messaggio tipo "Prima versione" e clicca **Commit changes**

### 4. Attiva GitHub Pages
- Vai nelle **Settings** del repository (tab in alto)
- Nel menu a sinistra clicca **Pages**
- Sotto "Source" seleziona **Deploy from a branch**
- Branch: **main**, cartella: **/ (root)**
- Clicca **Save**
- Dopo 1-2 minuti l'app sarà online a:
  `https://TUO-USERNAME.github.io/le-mie-finanze/`

### 5. Installa l'app

**Su Mac (Chrome/Edge):**
- Apri l'URL della tua app nel browser
- Clicca l'icona di installazione nella barra degli indirizzi (↓ con quadrato)
- Oppure: menu ⋮ → "Installa Le mie finanze..."
- L'app appare nel Launchpad e nel Dock

**Su iPhone/iPad (Safari):**
- Apri l'URL in Safari
- Tocca il pulsante Condividi (quadrato con freccia)
- Scorri e tocca **"Aggiungi alla schermata Home"**
- L'app appare come un'icona nella home

**Su Android (Chrome):**
- Apri l'URL in Chrome
- Tocca il banner "Installa" oppure menu ⋮ → "Installa app"

## Come aggiornare l'app

1. Chiedimi le modifiche qui su Claude
2. Ti restituisco il file `index.html` aggiornato
3. Vai nel tuo repository su GitHub
4. Clicca su `index.html` → icona matita (Edit)
5. Sostituisci tutto il contenuto con quello nuovo
6. Clicca **Commit changes**
7. Dopo 1-2 minuti l'app si aggiorna automaticamente

Se l'app non si aggiorna subito, apri le impostazioni del browser
e svuota la cache, oppure apri l'app e fai un hard refresh (Cmd+Shift+R su Mac).

## I tuoi dati sono al sicuro?

Sì! I dati sono salvati nel **localStorage del tuo browser**, non su GitHub.
Il repository contiene solo il codice dell'app, non i tuoi dati finanziari.
Anche se il repository fosse pubblico, nessuno vedrebbe le tue spese.
