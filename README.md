# Earl of Derby — website

Static site for the Earl of Derby (Hotel, Wine Bar & Café), Castletown, Isle of Man.
Plain HTML/CSS — no build step. Just host the folder.

## Pages
- `index.html` — gateway / landing (Hotel · Wine Bar · Café)
- `hotel.html` — the Hotel (four suites, gallery, Preno booking)
- `wine-bar.html` — the Wine Bar (OpenTable reservations, menu, hours)
- `cafe.html` — the Café (hours, menu, gallery — info only, no booking)
- `assets/img/` — photography
- `assets/menus/` — menu PDFs (placeholders — replace with your own)

## Deploy

### Netlify (drag & drop)
1. Go to app.netlify.com → "Add new site" → "Deploy manually".
2. Drag this whole folder onto the page. Done.

### Netlify via GitHub
1. Create a new GitHub repo and push this folder.
2. In Netlify: "Add new site" → "Import from Git" → pick the repo.
3. Build command: (leave blank). Publish directory: `.`

### GitHub Pages
1. Push to a repo, then Settings → Pages → deploy from branch (root).

## Before you go live — replace these placeholders
- **Booking links**
  - Hotel uses your live Preno link (already wired).
  - Wine Bar "Reserve a table" links to your OpenTable page. To embed the
    inline OpenTable widget, paste your widget code into the marked spot in
    `wine-bar.html` (search for "EMBEDDED OPENTABLE WIDGET").
- **Menus** — swap `assets/menus/cafe-menu.pdf` and `wine-bar-menu.pdf`
  for your real PDFs (keep the filenames, or update the links).
- **Wine Bar photos** — the Wine Bar gallery + hero use labelled placeholders.
  Drop real photos into `assets/img/` and point the `wine-bar.html` slots at them.
- **Logo** — the stag + wordmark are placeholders (inline SVG / web fonts).
  Swap for your in-house logo when ready.

© Picaro Limited 2026
