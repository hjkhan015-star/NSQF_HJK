# NSQF Planner – PWA Wrapper

This repository hosts the static PWA wrapper for the NSQF Planner.

- The actual application is loaded from Google Apps Script via an iframe.
- All updates to the planner are done in the Apps Script project; this repository remains unchanged.
- The Web App URL used in `index.html` points to the deployed Apps Script.

## Files

- `index.html` – PWA wrapper with iframe
- `manifest.json` – PWA manifest
- `sw.js` – Service worker (offline shell)
- `Icon.png` – App icon (512×512)