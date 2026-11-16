# ALNUR ARAF Portfolio

A responsive static portfolio website for GitHub Pages.

## Files
- `index.html` — page structure and metadata
- `style.css` — responsive visual design
- `script.js` — artwork data, category filters and lightbox
- `CNAME` — custom domain: portfolio.alnuraraf.eu.org

## Deploy with GitHub Pages
1. Create a GitHub repository named `alnur-araf-portfolio`.
2. Upload the contents of this folder to the repository root.
3. In repository Settings → Pages, choose Deploy from a branch, select `main` and `/ (root)`.
4. Keep the `CNAME` file in the repository root.
5. In your domain DNS settings, create a CNAME record:
   - Name/Host: `portfolio`
   - Target: `<your-github-username>.github.io`
6. Enable HTTPS in GitHub Pages after DNS verification.

## Artwork hosting
The initial version uses the image URLs supplied by the portfolio owner. For better long-term reliability, download the original images and store them in the repository under `assets/images/`, then update the `image` values in `script.js` to local paths.

## Before publishing
- Verify you have the rights to display every image.
- Confirm each image URL loads.
- Replace the contact email if needed.
- Add your Creative Fabrica profile link when the shop is approved.
- Do not describe raster previews as editable SVG or untested tiles as seamless patterns.
