# Individuatio — Percorso Junghiano

App per la crescita psicologica basata sulla psicologia analitica di Jung.

---

## Come pubblicarla su GitHub Pages e installarla su iPhone

### 1. Crea un account GitHub
Vai su [github.com](https://github.com) e registrati (è gratuito).

### 2. Crea un nuovo repository
- Clicca sul `+` in alto a destra → **New repository**
- Nome: `individuatio` (o qualsiasi nome)
- Lascia tutto il resto com'è
- Clicca **Create repository**

### 3. Carica i file
Nella pagina del repository appena creato:
- Clicca **uploading an existing file** (o "Add file" → "Upload files")
- Trascina tutti questi file:
  - `index.html`
  - `app.jsx`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Clicca **Commit changes**

### 4. Attiva GitHub Pages
- Vai su **Settings** (in alto nel repository)
- Nel menu a sinistra clicca **Pages**
- Sotto "Source" seleziona **Deploy from a branch**
- Branch: **main**, cartella: **/ (root)**
- Clicca **Save**

Dopo 1-2 minuti l'app sarà disponibile su:
`https://[tuo-username].github.io/individuatio/`

### 5. Installa sul iPhone
- Apri **Safari** sull'iPhone (deve essere Safari, non Chrome)
- Vai all'indirizzo sopra
- Tocca l'icona **Condividi** (il quadrato con la freccia in su)
- Scorri e tocca **"Aggiungi alla schermata Home"**
- Dai un nome (es. "Individuatio") e tocca **Aggiungi**

L'app apparirà sulla home screen come un'app normale, senza barra del browser.

---

## Note importanti

- **I dati sono salvati localmente** sul tuo dispositivo (localStorage) — non vengono inviati a nessun server esterno tranne le chiamate all'API di Claude per le analisi.
- **Funziona offline** per la navigazione, ma le analisi AI richiedono connessione internet.
- **L'API di Claude** è integrata direttamente nell'app — funziona solo quando l'app è aperta tramite browser/Safari, non tramite app nativa iOS.
