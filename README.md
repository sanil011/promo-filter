# Promo Filter website

Static site for the Promo Filter Chrome extension, served by GitHub Pages at
**https://promofree.fuel-up.in** (custom domain in `CNAME`; DNS is a Cloudflare CNAME
`promofree` → `sanil011.github.io`, DNS only).

| Page | Path |
|---|---|
| Landing page | `/` (`index.html`) |
| Privacy policy (Chrome Web Store + Google OAuth link) | `/privacy/` (`privacy/index.html`) → https://promofree.fuel-up.in/privacy/ |

No build step: plain HTML + one stylesheet (`assets/styles.css`, light and dark mode).
`.nojekyll` tells GitHub Pages to serve the files as they are.

## Updating

- **Privacy policy:** edit `privacy/index.html` and change the "Last updated" date. Keep it in sync with
  `PRIVACY.md` in the extension repo.
- **Store link:** the extension is live at
  https://chromewebstore.google.com/detail/promofree/gbgbiplhnfpgbeonnlkhojopkonmgaag. It's used by the
  hero's "Add to Chrome" button and step 1 of "How it works" in `index.html`.
- **Screenshots:** `assets/screenshot-*.png` are copies of `store-assets/` in the extension repo
  (1280×800, demo data only). Copy them over again when the store screenshots change.
