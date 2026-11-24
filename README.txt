MY LIFE TRACKER 3.0

CONTENTS
- index.html: the application
- manifest.webmanifest: installable PWA settings
- sw.js: offline caching service worker
- icons/: app icons

INSTALL ON ANDROID
1. Upload the contents of this folder to a static web host that serves HTTPS.
2. Open the HTTPS address in Google Chrome on your Android phone.
3. Open Chrome's menu and select Install app or Add to Home screen.
4. Confirm. Launch My Life Tracker from your home screen.

LOCAL DATA & BACKUPS
- Data is stored in localStorage in the browser profile on this device.
- Export a backup from Settings before changing phones or clearing browser data.
- Import a previously exported JSON backup from Settings.
- No account, cloud sync, or external service is required.

NOTES
- This is an installable Progressive Web App (PWA), not a native Android APK.
- Service workers and offline installation require HTTPS (except localhost for development).
- Browser storage may be cleared by device/browser settings. Export backups regularly.
- If an earlier My Life Tracker v1 database exists in the same browser, v3 attempts a one-time import of its habits, expenses, time logs, tasks, and daily plans.
