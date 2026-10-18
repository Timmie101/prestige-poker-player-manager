PRESTIGE POKER PLAYER MANAGER — iPad offline app package

This package is prepared as an installable Progressive Web App (PWA). It needs to be hosted at an HTTPS address once so Safari can install it and cache the app files. After the first successful load/install, it is designed to open offline. Tournament data is stored locally in Safari on this iPad; it does not sync to other devices.

IMPORTANT DATA SAFETY
- Before using it for a live event, test adding players, editing names, busting/restoring players, table moves, CSV export, closing/reopening the app, and Airplane Mode.
- Use Export CSV regularly as a backup. CSV backs up the player list, not every piece of tournament state.
- Do not clear Safari website data for the hosted app, as that can erase locally saved tournament data.

INSTALL ON iPAD (once hosted over HTTPS)
1. Open the hosted app URL in Safari (not an in-app browser).
2. Leave it open until the app has fully loaded and offline caching has completed.
3. Tap Share, then Add to Home Screen. If shown, enable Open as Web App, then tap Add.
4. Launch it from the new Home Screen icon while online once.
5. Test: turn on Airplane Mode and reopen the Home Screen app. Confirm it loads and saved test players remain.

HOSTING
Upload all files/folders in this package to a static HTTPS host (for example GitHub Pages, Netlify, or another static site host). Keep index.html, sw.js, manifest.webmanifest, and icons/ together in the same directory. Do not open index.html directly as a local file: iPad Safari cannot install service-worker offline support from file://.

Files: index.html, manifest.webmanifest, sw.js, icons/
