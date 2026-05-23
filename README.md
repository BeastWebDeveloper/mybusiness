# TEKTONIC

Website for **TEKTONIC** — web architecture, SEO & playable web.
Static site (HTML / CSS / JS). Native NL · ES · EN.

## Files
- `index.html` — the full site (logo, styles and scripts are embedded)
- `favicon.svg` — browser tab icon (arch + keystone mark)
- `tektonic-logo.svg` — standalone logo asset (logo + wordmark)

## Run locally
Just open `index.html` in a browser. No build step.

## Deploy (Cloudflare Pages)
1. Push this repo to GitHub.
2. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → select this repo.
3. Build settings: Framework preset = None, Build command = (empty), Output directory = `/`.
4. Save and Deploy.

Every `git push` to `main` redeploys automatically.

---
© 2026 TEKTONIC — Nicholas Reich
