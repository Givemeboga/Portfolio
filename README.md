# Gl1tch — Youssef Ben Chaouacha · Portfolio

👋 Hi, I'm **Youssef** — a Cybersecurity & Cloud Engineering student from Tunisia,
online as **Gl1tch**. I'm on the offensive-security track (aspiring penetration
tester), working through the HTB Academy Penetration Tester path and playing CTFs
whenever I get the chance. I love building systems and then breaking them to
understand how they really tick. This is the repo behind my portfolio — a place
to share the projects I'm proud of and where I'm headed next.

**Live:** https://givemeboga.github.io/Portfolio/

---

Personal cybersecurity portfolio — a single-page static site with two project
case-files (BioScan, Fortify). No build step, no server; works on any static host.

## Structure
- `index.html` — home
- `bioscan.html`, `fortify.html` — project case-files
- `support.js` — runtime (loads React from a CDN)
- `assets/` — images, logos, certificates

## Run locally
Any static file server works, e.g.:
```bash
python -m http.server 8000
```
Then open http://localhost:8000.

## Deploy
Hosted on GitHub Pages from the `main` branch (root). Push to `main` and the site
redeploys automatically within about a minute:
```bash
git add .
git commit -m "Update portfolio"
git push
```
