# AITC — موقع مقترحات الشعار

Static, dependency-free Arabic (RTL) site built from the AITC logo-proposals deck.

- `index.html` — the whole site (inline CSS/JS; concept icons embedded as data URIs)
- `assets/` — logos cropped from the PDF (colour on transparent, plus white-on-dark and black-on-grey) and the hero image

Open `index.html` directly, or serve the folder: `python3 -m http.server -d site 8000`.
Deploys as-is to any static host (GitHub Pages, Netlify, Vercel, S3).

Design: built with the UI/UX Pro Max skill — Swiss/minimal style (full RTL support),
chapter-per-proposal storytelling, brand palette from the deck, IBM Plex Sans Arabic,
WCAG-AA text contrast (darker accent shades for text), 44px touch targets, visible focus,
`prefers-reduced-motion` respected, no horizontal scroll at 390px.
