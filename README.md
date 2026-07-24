# Thiab R. Taha Academic Website

This folder contains a complete static website ready for GitHub Pages.

## Files

- `index.html` - website content
- `styles.css` - design and mobile layout
- `assets/Taha_CV_2026.pdf` - downloadable CV
- `CNAME` - connects GitHub Pages to `thiabtaha.com`
- `.nojekyll` - tells GitHub Pages to publish the files as a plain static site

## Upload to GitHub

1. Open your GitHub repository.
2. Choose **Add file > Upload files**.
3. Upload everything inside this folder, including the `assets` folder.
4. Commit the changes.
5. Open **Settings > Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Choose branch **main** and folder **/(root)**, then save.
8. Under **Custom domain**, enter `thiabtaha.com` and save.

## Customize

- Replace the `TRT` monogram with a photograph later if desired.
- Add your preferred professional email in the commented section near the bottom of `index.html`.
- Update text by editing `index.html`.
- Replace the PDF in `assets` whenever you update your CV, keeping the same filename.

## Cloudflare DNS records for GitHub Pages

Set the apex-domain records according to GitHub's current GitHub Pages documentation. Also create:

- Type: `CNAME`
- Name: `www`
- Target: `trtaha11.github.io`

Start with Cloudflare proxy status set to **DNS only** while GitHub verifies the domain. After HTTPS is working, the proxy can be reconsidered.
