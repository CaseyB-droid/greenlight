GreenLight — IRONMAN Texas 2027
A personal, HRV-guided adaptive training cockpit for the road to IRONMAN Texas (Apr 24, 2027). Each morning it reads recovery (HRV, resting HR, sleep, wellness) and training load, then adapts the day's prescribed swim/bike/run/strength sessions accordingly.
Live app: https://caseyb-droid.github.io/greenlight/
What's in here
`index.html` — the entire app in one self-contained file (React + charts, bundled and minified). No build step, no server, no dependencies to install.
Data & privacy
All training data — readiness, workouts, the log — lives only in this browser's local storage on your device. Nothing is uploaded to GitHub or anywhere else. This repository contains the app code only; it holds none of your personal numbers, which is why a public repo is fine.
Installing it as a phone app
Open the live URL in Safari (iOS) or Chrome (Android) → Share / menu → Add to Home Screen. It then launches full-screen with its own icon.
Updating
Replace `index.html` with a new version and commit. Because the data is tied to the URL (not the file), your history carries over automatically — no re-import or restore needed. After updating, fully close and reopen the home-screen app so it loads past the cache.
Backups
Use Data → Export / back up in the app to save a JSON snapshot. Restore loads it back (and is how you move data to another device, since storage is per-device). Exporting before each update is cheap insurance.
---
Built iteratively with Claude. Training guidance only — not medical advice.
