# Chalk Sprint

A fast chalkboard math game. Each round shows an equation like `5 + 6 = ?` and four answers; pick the right one before the chalk line runs out.

- Tap or click an answer, or press 1–4. P pauses, R restarts, M toggles sound.
- Streaks raise a score multiplier up to x5. Three misses ends the run.
- High scores are saved in the player's own browser.

It is a single static page (`index.html`) with a web app manifest and a service worker, so it installs to a phone home screen and works offline. Host the folder on any static host (GitHub Pages, Netlify), then use https://www.pwabuilder.com with the hosted URL to generate a Google Play package.
