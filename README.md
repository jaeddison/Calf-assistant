# Calf Rearing Assistant

A mobile-first calf rearing app — births, feed forecasting, bobby pens, treatments, deaths, and a pushing list — built as a single HTML file with local storage, in the same style as Dairy Assistant.

## Files in this folder

| File | What it's for |
|---|---|
| `calf-assistant.html` | The app itself. This is the only file that needs opening in a browser. |
| `icon.png` | The app icon, pulled in directly by the HTML — same pattern as your other apps. |

Both files need to sit in the same folder for the icon to show up — the HTML references `icon.png` by name.

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `calf-assistant`) — same process as Dairy Assistant.
2. Upload all the files listed above into the root of that repository.
3. In the repo, go to **Settings → Pages**, set the source to the `main` branch (root folder), and save.
4. GitHub will give you a URL like `https://[username].github.io/calf-assistant/calf-assistant.html` — that's the link to share.

## Adding it to your wife's phone

1. Open the GitHub Pages link above in Edge on the iPhone.
2. Tap the **Share** button, then **Add to Home Screen**.
3. The milk bottle icon should appear on the home screen, and opening it will launch full-screen without the browser address bar — same as Dairy Assistant.

## A note on backups

All data lives in the phone's local storage — nothing is uploaded anywhere. The **Share** tab inside the app has a full backup export/import (the `CALF_IMPORT:` code) in case the phone needs restoring, plus one-tap clipboard summaries for milk requirements, calf totals, treatments, and deaths to send on to you or the GM.

---

© 2026 James Eddison. All rights reserved.
