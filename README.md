# Gl1tch — Youssef Ben Chaouacha · Portfolio

A single-page cybersecurity portfolio with two project case-files (BioScan, Fortify).
Static site — no build step, no server. Works on any static host.

## Files that get deployed
- `index.html` — home (portfolio)
- `bioscan.html`, `fortify.html` — project case-files
- `support.js` — runtime (loads React from a CDN at runtime)
- `assets/` — images, logos, certificates
- `.nojekyll` — tells GitHub Pages to serve files as-is

> The `*.dc.html` files are the **editable source**. `index.html` / `bioscan.html` /
> `fortify.html` are generated deploy copies with the internal links rewritten to clean
> names. If you change a `.dc.html`, regenerate the matching deploy file.

## Deploy free with GitHub Pages

1. **Create a repo** on github.com (e.g. `portfolio`). Public.
2. **Upload the files.** On the repo page → *Add file → Upload files* → drag in
   `index.html`, `bioscan.html`, `fortify.html`, `support.js`, `.nojekyll`, and the
   whole `assets/` folder → *Commit changes*.
   (Or via git — see below.)
3. **Enable Pages.** Repo *Settings → Pages* → *Source: Deploy from a branch* →
   Branch `main`, folder `/ (root)` → *Save*.
4. Wait ~1 minute. Your site is live at
   `https://<your-username>.github.io/<repo-name>/`.

### Git command-line alternative
```bash
git init
git add .
git commit -m "Portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then do step 3 above.

## Custom domain (optional)
In *Settings → Pages → Custom domain*, add your domain and create a CNAME record at
your registrar pointing to `<your-username>.github.io`.

## Notes
- An internet connection is required on the visitor's side (React + Google Fonts load
  from CDNs).
- The footer visitor counter uses a free public counter API; it starts counting once
  the site is live on a real URL.
