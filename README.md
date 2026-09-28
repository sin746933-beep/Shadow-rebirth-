# Shadow Rebirth — Mobile Capacitor Edition

Android-only, single-player 2D action game. Designed to be built from a phone using Termux + Node.js/Capacitor or another mobile build environment.

## Build
1. Install Node.js/npm in your mobile environment.
2. In this folder run:
   npm install
   npx cap add android
   npx cap sync
3. Build the Android project using the Android build environment available on your phone.

The game itself is contained in `www/` and runs offline. Progress is saved with localStorage.
