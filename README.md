# Your Support Genie (YSG) — Website

Static marketing site for Your Support Genie (YSG IT Service (OPC) Pvt. Ltd), hosted on GitHub Pages.

## Live pages

| Page | File |
|---|---|
| Home | `index.html` |
| Training | `training.html` |
| Careers | `careers.html` |
| News | `news.html` |
| 404 (not found) | `404.html` |

## Structure

- `support.js` — page runtime. **Do not edit.**
- `components/image-slot.js` — drag-and-drop image placeholder component used across pages.
- `uploads/` — all images, the logo, and other media assets.
- `sitemap.xml`, `robots.txt` — SEO files, already pointing at `https://www.yoursupportgenie.com/`.
- `CNAME` — created automatically by GitHub when you set the custom domain in Settings → Pages; do not delete it once present, or the custom domain will stop working.

## Updating content

These pages are plain HTML/JS — open any `.html` file in a text editor and edit the text directly, or drag a new image onto any image placeholder in a browser to replace it (changes there are local to that browser session only; for a permanent change, replace the file in `uploads/` and update the `src` in the HTML).

For structural changes (new sections, layout, new pages), this site was built and is best maintained through the original design tool project — re-export from there and re-upload the changed files here.

## Deployment

This repo is served directly by GitHub Pages from the root of the `main` branch (Settings → Pages → Source: Deploy from a branch → `main` / `/root`). Pushing changes to `main` redeploys automatically within a minute or two.

## Contact form

The contact form on `index.html` submits via [Web3Forms](https://web3forms.com) to `contact@yoursupportgenie.com`. No backend/server code is needed — submissions are handled entirely by Web3Forms.
