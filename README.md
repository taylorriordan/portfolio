# Bootstrap Portfolio Starter

A simple, production-friendly starting point for a designer portfolio built with **HTML, CSS, and Bootstrap 5**.

## Quick start (VS Code)

1. Open this folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` → **Open with Live Server**.

## Customize theme

- Edit `css/custom.css`. For quick theming, adjust CSS variables like `--bs-primary` and font family in `:root`.
- Replace images in `img/` with your own screenshots and thumbnails.

## Build pages

- `index.html` lists projects.
- Add case studies in `case-studies/` (a starter `revamping-the-content-editing-experience-for-nwea-org.html` is included).
- Update nav links in each page.

## Keep sensitive data safe

- Use generalized metrics (e.g., “+35% conversions”) rather than exact revenue or internal counts.
- Pages include `<meta name="robots" content="noindex, nofollow">` by default.
- To make the site discoverable, **remove** the meta robots tags and update `robots.txt` to allow indexing.

## Accessibility checklist

- Provide descriptive alt text for images.
- Use a single H1 per page; keep heading order logical.
- Ensure sufficient color contrast.
- Make interactive elements keyboard accessible.

## Deploy options

- **GitHub Pages**: Push to a public repo, enable Pages, and serve from the root.
- **Netlify/Vercel**: Drag-and-drop this folder or connect your repo; add password protection if needed.

