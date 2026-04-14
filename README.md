# Christophe Spaenjers — Personal Website

A clean, multi-page academic site. Pure HTML + CSS, no build step.

Live at **https://christophespaenjers.github.io**

## Files
- `index.html` — Home (bio, photo, contact links)
- `working-papers.html` — Working papers with SSRN links
- `publications.html` — Publications categorized by Real Estate, Art & Auctions, Households
- `discussions.html` — Recent conference discussions with slides
- `cv.pdf` — CV (linked directly from nav)
- `photo.jpg` — Profile photo
- `style.css` — Shared styles (Montserrat font via Google Fonts)

## Local preview
Run a local server from this folder:
```
python3 -m http.server 8000
```
Then open http://localhost:8000 in your browser.

## Deploy
Push to the `main` branch of `christophespaenjers/christophespaenjers.github.io` on GitHub. GitHub Pages deploys automatically.

### Custom domain (optional)
Add a file named `CNAME` containing your domain (e.g. `christophespaenjers.com`) to the repo root, then point the domain's DNS to GitHub Pages (`A` records for `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`).
