# Zen Learning Apps — iPhone/iPad setup

These are two standalone PWAs:
- `vocab/index.html` — Zen's Vocab Quest
- `times/index.html` — Zen's Times Tables

## Recommended free hosting: GitHub Pages

GitHub Pages can host static HTML/CSS/JavaScript files for free in a public repository.

1. Create a GitHub account if needed.
2. Create a new PUBLIC repository, e.g. `zen-learning`.
3. Upload the contents of this folder so the repository contains:
   - `index.html` (see note below)
   - `vocab/index.html`
   - `vocab/manifest.json`
   - `vocab/sw.js`
   - `times/index.html`
   - `times/manifest.json`
   - `times/sw.js`
4. To make the home page useful, copy either app to the repository root or create a simple `index.html` linking to the two apps.
5. In GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
6. Wait for GitHub Pages to publish.
7. Open the resulting HTTPS URL in Safari on iPhone/iPad.
8. Open the Vocab app URL, tap Share → Add to Home Screen.
9. Repeat for the Times Tables app.

The apps use browser local storage for progress, so progress is normally separate on each device.

Important: GitHub Pages sites are public. These apps contain only educational content and no private information.
