# Personal site — Hangxi Guo

Single-page academic homepage. Plain HTML + one CSS file, no build step, no dependencies.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | All content |
| `style.css` | Design tokens, layout, light + dark palettes |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Edit

- Text lives directly in `index.html`, one `<section>` per topic.
- Colours are CSS variables at the top of `style.css` (`--bg`, `--ink`, `--teal`,
  `--line`). The design is dark by default — there is no light palette.
- `assets/argus-teaser.jpg` is the Argus figure from the technical report
  (CC BY 4.0).
- Preview locally: `python3 -m http.server 8000`, then open
  <http://localhost:8000>.

## Deploy

Push to `main`. Pages serves from the branch root (Settings → Pages → Deploy from
a branch → `main` / `/ (root)`).
