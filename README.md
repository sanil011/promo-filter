# Promo Filter website

Static site for the Promo Filter Chrome extension, served by GitHub Pages.

| Page | Path |
|---|---|
| Landing page | `/` (`index.html`) |
| Privacy policy (Chrome Web Store + Google OAuth link) | `/privacy/` (`privacy/index.html`) |

No build step: plain HTML + one stylesheet (`assets/styles.css`, light and dark mode).
`.nojekyll` tells GitHub Pages to serve the files as they are.

## Updating

- **Privacy policy:** edit `privacy/index.html` and change the "Last updated" date. Keep it in sync with
  `PRIVACY.md` in the extension repo.
- **Store link:** once the extension is published, put its Chrome Web Store URL in the hero button in
  `index.html` and remove `aria-disabled="true"`.
