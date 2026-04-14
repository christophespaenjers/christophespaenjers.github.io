# Christophe Spaenjers — Personal Website

A clean, multi-page academic site. Pure HTML + CSS, no build step.

## Files
- `index.html` — Home (bio, contact, news)
- `research.html` — Working papers and publications
- `teaching.html` — Courses
- `cv.html` — CV summary (with link to PDF)
- `style.css` — Shared styles
- `profile.jpg` — Add your headshot here (referenced from index.html)
- `cv.pdf` — Add your CV here (referenced from index.html and cv.html)

## Edit
Open the `.html` files in any text editor and replace the placeholder content.
The navigation bar lives in each page (look for `<nav class="site-nav">`); update the `class="active"` to mark the current page.

## Deploy to GitHub Pages

1. Create a new repository on GitHub named **`christophespaenjers.github.io`**
   (the repo name must exactly match `<username>.github.io`).
2. Upload all files in this folder to that repository (drag & drop in the GitHub web UI works).
3. In the repo, go to **Settings → Pages** and confirm "Deploy from a branch" → `main` → `/ (root)`.
4. Within a minute, your site will be live at **https://christophespaenjers.github.io**.

### Custom domain (optional)
If you own e.g. `christophespaenjers.com`, add a file named `CNAME` containing just that domain to the repo root, then point the domain's DNS to GitHub Pages (`A` records for `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`).

## Local preview
Just double-click `index.html` to open it in your browser. No server needed.
