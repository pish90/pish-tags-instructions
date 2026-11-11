# pish-tags-instructions

Installation guide for **Pish Tags** magnetic race-number fasteners.

- **Live:** https://pish-tags.pages.dev/
- **Hosting:** Cloudflare Pages (project `pish-tags`), auto-deploys from `main`. Other branches get preview URLs.

## ⚠ Do not break the URL

100+ printed QR stickers point at `https://pish-tags.pages.dev/`. To keep them working:

- Never rename or delete the Cloudflare Pages project `pish-tags`.
- Keep `index.html` at the repo root.
- Keep `main` as the production branch.

## Files

| Path | Purpose |
|---|---|
| `index.html` | The entire site (inline CSS + SVG, no build step) |
| `assets/pish-logo.jpg` | Brand logo (reference: `Tag cards.docx`) |
| `print/pish-tags-qr-code.png` | QR master, 1200×1200, decodes to `https://pish-tags.pages.dev/` |
| `print/pish-tags-qr-sticker-35mm.pdf` | Print-ready 35 × 35 mm QR sticker |

`TODO(photo)` comments in `index.html` mark the diagrams to replace with real product photos.
