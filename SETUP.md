# Generazione Android e iOS

## Requisiti

- Node.js LTS
- Android Studio per Android
- macOS + Xcode per compilare iOS

## Prima configurazione

```bash
npm install
npx cap add android
npx cap add ios
npx cap sync
```

## Android

```bash
npx cap open android
```

Da Android Studio è possibile eseguire l'app su telefono/emulatore e generare APK/AAB.

## iPhone/iPad

Su macOS:

```bash
npx cap open ios
```

Xcode permette di eseguire l'app su iPhone e prepararla per TestFlight/App Store.

## Modifiche al frontend

I file destinati all'app nativa sono nella cartella `www`. Dopo una modifica eseguire:

```bash
npx cap sync
```

Nota: il repository non contiene ancora le cartelle native `android` e `ios`; vengono generate con `npx cap add android` e `npx cap add ios` sulla macchina di sviluppo.
