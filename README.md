# Pratik Sarkar | Product Portfolio

A single-file interactive portfolio (no build step). Filter by company, search by product or tech, expand each card for details, and toggle dark mode.

## Publish on GitHub Pages

1. Create a new public repo on GitHub, e.g. `portfolio` (or `<your-username>.github.io` for a root URL).
2. Upload `index.html` and this `README.md` to the repo root.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After about a minute the site is live at `https://<your-username>.github.io/portfolio/`.

## Edit content

Everything lives in the `COMPANIES` and `PRODUCTS` arrays near the bottom of `index.html`. To add a link to a product, add `{label, url}` to its `links` array.
