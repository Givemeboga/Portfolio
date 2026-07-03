# Gl1tch — Youssef Ben Chaouacha · Portfolio

A single-page cybersecurity portfolio with two project case-files (BioScan, Fortify).
Static site — no build step, no server. Works on any static host.

**Live:** https://givemeboga.github.io/Portfolio/

## Files that get deployed
- `index.html` — home (portfolio)
- `bioscan.html`, `fortify.html` — project case-files
- `support.js` — runtime (loads React from a CDN at runtime)
- `assets/` — images, logos, certificates
- `.nojekyll` — tells GitHub Pages to serve files as-is

> The `*.dc.html` files are the **editable source**. `index.html` / `bioscan.html` /
> `fortify.html` are generated deploy copies with the internal links rewritten to clean
> names. If you change a `.dc.html`, regenerate the matching deploy file.

## Deployed with GitHub Pages

Repo: [github.com/Givemeboga/Portfolio](https://github.com/Givemeboga/Portfolio)
(Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`)

### Pushing an update
```bash
cd "Portfolio creation project/deploy"
git add .
git commit -m "Update portfolio"
git push
```
Pages redeploys automatically — changes are live within ~1 minute.

### Redeploying from scratch (new repo)
```bash
git init
git add .
git commit -m "Portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then enable Pages as above.

## Custom domain (optional)
In *Settings → Pages → Custom domain*, add your domain and create a CNAME record at
your registrar pointing to `<your-username>.github.io`.

## Notes
- An internet connection is required on the visitor's side (React + Google Fonts load
  from CDNs).
- The footer visitor counter uses a free public counter API; it starts counting once
  the site is live on a real URL.
