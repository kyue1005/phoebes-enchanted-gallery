# Phoebe’s Enchanted Gallery

A responsive online gallery celebrating Phoebe’s artwork, with year filters and a full-screen artwork viewer.

**Live site:** https://phoebes-enchanted-gallery.pages.dev/

**Hosting:** Cloudflare Pages

## View locally

Open `index.html` in Safari, Chrome, or Firefox. No build step or web server is required.

## Project structure

- `index.html` — complete gallery interface and artwork metadata
- `photos/` — optimized images used by the public website
- `work/` — original source photographs, kept locally and excluded from Git

## Updating artwork

Add a web-optimized image to `photos/`, then add or update its entry in the `artworks` array in `index.html`. Commit and push the change to redeploy the Cloudflare Pages site.

## Privacy

Only optimized gallery images are published. Original photographs under `work/` remain local.
