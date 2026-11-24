# DARK LORD TOURNAMENTS — Phase 1 UI prototype

A responsive Free Fire BR Solo tournament interface with a separate admin preview.

## Design refresh
- Uses the supplied Dark Lords guild logo in player and admin branding.
- Refined black / deep-purple palette with restrained accent use.
- Replaced decorative Unicode navigation symbols with Lucide SVG icons.
- Simplified surfaces, typography, spacing, match cards and responsive navigation.
- No PUBG or other game modes; this project is Free Fire BR Solo only.

## Run locally

```bash
npx serve .
```

Open the local URL shown by the server:
- Player interface: `/index.html`
- Admin preview: `/admin.html`

Lucide icons and Google Fonts are loaded from external CDNs, so those visual assets require an internet connection.

## Android wrapper starter

```bash
npm install
npx cap add android
npx cap sync android
npx cap open android
```

Build the APK from Android Studio. A working Android build requires Android Studio and the Android SDK.

## Prototype limitations

This is still Phase 1. Demo data is held in JavaScript memory and resets on refresh. There is no real authentication, email verification, Supabase connection, persistent database, server-side slot locking, realtime updates, push notification service, secure admin authorization, or payment processing. Do not use this prototype for real tournaments or real balances.

## Project scope
- Game: Free Fire BR Solo only.
- Theme: black and purple.
- Logo: client-supplied Dark Lords guild logo at `assets/dark-lords-guild-logo.png`.
- Wallet: simulated demo credits only; no real-money transactions.
