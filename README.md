# Health Log

A two-person daily health tracker that runs entirely in the browser — no server, no accounts.
Log workouts, steps, sleep, meds and more with one tap; compare your day with your
accountability partner; exchange progress between phones with paste-able share codes.

All data lives in each device's browser storage (`localStorage`) and never leaves it.

- `index.html` — the whole app (self-contained)
- `health-log.html` — the app body without the page shell (source for the Claude artifact version)
- `sw.js` — service worker for offline use
- `manifest.webmanifest`, `icon.svg` — installable-app metadata

Open the GitHub Pages URL on your phone in Chrome and choose **Add to Home Screen**
to install it like an app.
