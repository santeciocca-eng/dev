# Dev PWA

Progetto PWA installabile su Android e iPhone, predisposto anche per l'integrazione con Capacitor.

## Avvio

Aprire `index.html` tramite un web server HTTPS (necessario per service worker e installazione PWA).

## Struttura

- `index.html` - applicazione
- `manifest.webmanifest` - configurazione PWA
- `sw.js` - service worker/offline
- `.gitignore` - esclusioni Git

## Installazione

### Android
Aprire il sito in Chrome e scegliere **Installa app** / **Aggiungi a schermata Home**.

### iPhone/iPad
Aprire il sito in Safari, toccare **Condividi** e scegliere **Aggiungi alla schermata Home**.

## Capacitor
In una fase successiva il frontend può essere impacchettato con Capacitor per generare un progetto Android/iOS nativo.
