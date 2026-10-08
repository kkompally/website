# krishnakompally.com

Personal academic portfolio of **Krishna Kompally** — Ph.D. candidate in Experimental
Fluid Dynamics, Arizona State University.

Pure static site (HTML + CSS + JS). No build step, no trackers, no dependencies.
Live at **https://www.krishnakompally.com** via GitHub Pages (custom domain on Squarespace).

## Layout

- `index.html` — all content: hero, about, research, toolkit, publications, experience, contact
- `styles.css` — theme (light/dark), layout, cards
- `script.js` — theme toggle, reveal-on-scroll, cite-button clipboard
- `images/` — portrait, research figures, diagrams, map
- `cv.pdf` — downloadable CV
- `favicon.svg` — "K" monogram favicon

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Pushes to `main` auto-deploy via GitHub Pages ("Deploy from a branch").
Custom domain `www.krishnakompally.com` is set in Settings → Pages;
DNS (Squarespace): apex A records → GitHub Pages IPs, www CNAME → kkompally.github.io.
