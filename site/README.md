# AITC — موقع مقترحات الشعار

Static, dependency-free Arabic (RTL) site built from the AITC logo-proposals deck.

- `index.html` — the whole site (inline CSS/JS/SVG)
- No external assets: the four logos are inlined as SVG (from the designer files), so the page is a single file

Open `index.html` directly, or serve the folder: `python3 -m http.server -d site 8000`.
Deploys as-is to any static host (GitHub Pages, Netlify, Vercel, S3).

Design (v3): a quiet presentation document for the committee choosing a logo. Neutral white/grey
interface so the only colour on the page is the brand's; the four symbols open the page and assemble
once on load (the only ambient motion); each proposal shows its idea, a colour / white / black switch,
and CSS mock-ups of the logo in use (business card, app icon, avatar, website header, entrance sign).
Noto Kufi Arabic for headings, IBM Plex Sans Arabic for text.

`logos/` holds the original designer SVGs. Note: proposal-4.svg embeds two low-res PNGs for its outer curves.
