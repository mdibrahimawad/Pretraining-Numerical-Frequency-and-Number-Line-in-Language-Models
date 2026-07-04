# Project Page — Pretraining Numerical Frequency and Number-Line in Language Models

Project webpage for the ICML 2026 Mechanistic Interpretability Workshop paper, built on the
[Nerfies project page template](https://github.com/nerfies/nerfies.github.io).

## Deploy on GitHub Pages (for the poster QR code)

1. Create a new public repo, e.g. `numberline-frequency` (or `<username>.github.io` for a root URL).
2. Copy everything in this folder to the repo root and push.
3. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)** → Save.
4. Your page will be live at `https://<username>.github.io/numberline-frequency/` within a minute or two.
5. Generate the QR code pointing to that URL (any QR generator works) and drop it on the poster.

## Before going live — fill in the placeholder links

In `index.html`, search for `href="#"` and replace with real URLs:
- **arXiv** button → your arXiv abstract page (once uploaded)
- **Code** button → your GitHub repo (or delete the button if the code isn't public)
- Footer GitHub icon → same

The **Paper** button already works: it points to the compiled PDF at
`static/paper/number_line_freq.pdf` (compiled from your Overleaf source).

## Structure

```
index.html              — the page
static/css, static/js   — Bulma + template assets (unchanged from Nerfies)
static/images/          — paper figures converted from the PDF figures
static/paper/           — compiled paper PDF
```
