# AITC — موقع مقترحات الشعار

Static, dependency-free Arabic (RTL) site built from the AITC logo-proposals deck.

- `index.html` — the whole site (inline CSS/JS/SVG)
- No external assets: the four logos are inlined as SVG (from the designer files), so the page is a single file

Open `index.html` directly, or serve the folder: `python3 -m http.server -d site 8000`.
Deploys as-is to any static host (GitHub Pages, Netlify, Vercel, S3).

Design (v2, built with the UI/UX Pro Max skill): dark "constellation" hero where brand-coloured
data points converge on the AI star; each proposal gets a stage where the symbol assembles piece by
piece, a light / dark / brand-colour background test, an "idea equation", lockup variants and a
small-size test; side-by-side comparison; interactive colour spectrum. Alexandria + IBM Plex Sans Arabic.
WCAG-AA text contrast, 44px targets, visible focus, prefers-reduced-motion respected, no horizontal scroll at 390px.

`logos/` holds the original designer SVGs. Note: proposal-4.svg embeds two low-res PNGs for its outer curves.
