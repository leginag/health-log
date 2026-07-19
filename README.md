# Health Challenge

A two-player daily health challenge that runs entirely in the browser — no server, no accounts.
Four quests a day (push-ups, sit-ups, stretching, swim/gym), an anime-style character that
powers up as you complete them, a rank ladder for consistency, and a trends-first Compare
view so you and your accountability rival can see exactly where either of you is slipping.
Exchange progress between phones with paste-able share codes.

All data lives in each device's browser storage (`localStorage`) and never leaves it.

- `index.html` — the whole app (self-contained)
- `health-log.html` — the app body without the page shell (source for the Claude artifact version)
- `sw.js` — service worker for offline use
- `manifest.webmanifest`, `icon.svg` — installable-app metadata

Open the GitHub Pages URL on your phone in Chrome and choose **Add to Home Screen**
to install it like an app. Existing Health Log data is migrated automatically: push-ups,
sit-ups and gym history carry over; retired activities keep their logs and can be restored
from the Crew tab.
