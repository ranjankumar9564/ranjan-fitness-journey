# Ranjan Fitness Journey

A mobile-first fitness PWA for tracking a six-day training split, hydration, nutrition, habits, body weight, measurements and personal records.

## Features
- Six-day workout plan with two leg days; exercise sets, reps, suggested starting loads, per-set load logging and completion checkboxes.
- Daily water tracker with quick-add buttons and undo.
- Food diary with manual calorie, protein, carbohydrate and fat entries.
- Editable calorie, macro, hydration and body-weight targets.
- Daily habit checklist, sleep hours, step count and personal notes.
- Weight trend chart, body measurements, workout history and personal records.
- Export personal data as JSON.
- Responsive iPhone-friendly interface, custom SVG brand mark, motion effects and offline PWA caching.
- Local-first storage. No login, server or paid service.

## Run locally
```bash
python3 -m http.server 8000
```
Open `http://localhost:8000`. PWA installation and offline caching require HTTP(S), not a `file://` URL.

## Publish on GitHub Pages
1. Open **Settings → Pages**.
2. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
3. After deployment, open `https://YOUR-USERNAME.github.io/ranjan-fitness-journey/`.

## Add to iPhone
1. Open the HTTPS GitHub Pages URL in Safari.
2. Tap Share → Add to Home Screen.
3. If shown, enable **Open as Web App**, then tap Add.

After the first successful load, the app caches its core files for offline use.

## Data and privacy
Logs are stored in browser localStorage on that device. They do not sync across devices and can be lost if Safari website data is cleared. Use Settings → Export my data regularly to keep a backup. No data is sent to a server.

## Fitness note
Starting weights are approximate examples, not prescribed loads. Select weights based on current ability, good technique and recovery. Targets for calories/macros/hydration are editable estimates; individual needs vary. Adjust based on progress and seek qualified advice where appropriate.
