# Marian Díaz Romero — Portfolio Presentation

Static, dependency-free HTML/CSS/JS project. Open `index.html` directly in a browser, or serve it with VS Code's "Live Server" extension for local editing.

## Structure
- `index.html` — all 15 slides, as `<section>` children of `<deck-stage>`
- `css/styles.css` — shared styles (font import, resets, link colors). Most per-element styling lives inline on each slide's HTML for now — easy to find and edit slide by slide.
- `js/deck-stage.js` — the deck engine: keyboard (arrows/space/Home/End), touch swipe, thumbnail rail, speaker notes, print-to-PDF. No build step, no dependencies.
- `assets/` — images (currently just the About Me portrait).

## Editing
Each `<section data-label="...">` in `index.html` is one slide — edit the text/styles directly. The three "Selected Work" cards on the Portfolio slide are placeholder blocks (dashed pattern) — replace them with real `<img>` tags once you have project photos.

## Deploying
Push this folder to a GitHub repo and enable GitHub Pages (Settings → Pages → deploy from branch, root folder) — or drop it into Cloudflare Pages. No build step required.
