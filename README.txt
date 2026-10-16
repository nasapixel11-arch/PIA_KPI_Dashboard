# Retail Expert KPI — PWA

## Deploy (free) with GitHub Pages
1. Create a GitHub repository named `retail-expert-kpi` (Public is simplest for Pages).
2. Upload **all files and folders in this ZIP** to the repository root. Keep `index.html`, `manifest.json`, `sw.js`, and the `icons` folder together.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait until GitHub Pages shows the published HTTPS website URL.

## Install on Android
1. Open the published HTTPS URL in Chrome on your Android phone.
2. Open Chrome's ⋮ menu.
3. Tap **Install app** or **Add to Home screen** (wording varies).
4. Confirm. The Retail KPI icon will appear on your Home Screen.

## Data
- Daily records are saved in the browser's local storage on that device/browser.
- Export CSV regularly and download a JSON backup from inside the app.
- Installing/opening the same PWA on a different device will not automatically transfer local records. Restore a JSON backup there.
- The service worker caches the app shell for offline opening after the first successful visit.

This is a static PWA; it does not sync data to a server or between devices.
