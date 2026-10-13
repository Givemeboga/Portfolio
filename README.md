# Gl1tch — Youssef Ben Chaouacha

**Cybersecurity & Cloud Engineering · Offensive-Security Track · 🇹🇳 Tunisia**

[![Portfolio](https://img.shields.io/badge/Portfolio-givemeboga.github.io-5ee29a?style=flat-square)](https://givemeboga.github.io/Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Youssef%20Ben%20Chaouacha-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/youssef-ben-chaouacha-646715270/)
[![GitHub](https://img.shields.io/badge/GitHub-Givemeboga-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Givemeboga)
![eJPT](https://img.shields.io/badge/eJPT-in%20progress-f0c04a?style=flat-square)

Hi, I'm **Youssef Ben Chaouacha**, a final-year Cybersecurity & Cloud Engineering student, known online as **Gl1tch**.

I work across the full security lifecycle — **penetration testing, web & network security, SOC analysis, and cloud security** — with a focus on hands-on labs, security research, and building practical tools. Currently on the offensive-security track (HTB Academy Penetration Tester path, eJPT in progress) and an active CTF player.

---

## 🚀 Featured Projects

### 🧬 BioScan — 🏆 1st Prize, Bal des Projets 2026
A secure medical-document platform built end-to-end by a team of 5. A hardened, segmented hospital network in GNS3 (dual pfSense, 7 VLANs, BIND9, Samba AD, Grafana + Loki SIEM) sits under a FastAPI + React app with JWT + 2FA, AES-256, ClamAV scanning, OCR anonymization, and a reference-range analysis engine.

`pfSense` `GNS3` `FastAPI` `React` `PostgreSQL` `SIEM`
[📄 Case file](https://givemeboga.github.io/Portfolio/bioscan.html) · [💻 Repo](https://github.com/Givemeboga/BioScan)

### 🏰 Fortify — open source · v1.2.0
An open-source web-application security scanner with AI-assisted analysis. Passive **and** active scanning (TLS, security headers, sensitive paths, plus opt-in SQLi / XSS / path-traversal), a grounded AI analyzer that runs on a local LLM by default so scan data never leaves your machine, and a React operator console. One-command Docker run.

`Python` `FastAPI` `React` `Ollama` `SQLite` `Docker`
[📄 Case file](https://givemeboga.github.io/Portfolio/fortify.html) · [💻 Repo](https://github.com/Givemeboga/Fortify)

### 🎣 BaitWay — v1.0.1
A SOC analyst platform that unifies the two most repetitive triage tasks — phishing-email analysis and multi-source IOC lookup — behind one dashboard, each returning an explainable 0–100 risk score. Built with a teammate during a VadaSoft internship; I designed and built the phishing-analysis module.

`FastAPI` `React` `PostgreSQL` `Docker` `Threat Intel`
[📄 Case file](https://givemeboga.github.io/Portfolio/baitway.html) · [💻 Repo](https://github.com/Givemeboga/Baitway)

### 🔮 A.D.A — local AI · in development
A private, local, agentic voice assistant — say her name and she listens, thinks and acts. Speech-to-text, a local LLM (Ollama) and TTS run across your own devices, with a CPU fallback when the GPU laptop is away and no audio ever leaving your machines. Security-first by design: tools are allowlisted, every action is confirmation-gated, and web content is treated as data, never instructions.

`Python` `Pipecat` `Ollama` `FastMCP` `Three.js`
[📄 Case file](https://givemeboga.github.io/Portfolio/ada.html) · [💻 Repo](https://github.com/Givemeboga/A.D.A)

---

## 🏅 Certifications & Achievements

- 🏆 **1st Prize — Bal des Projets 2026** (ESPRIM) — Cloud & Security integrated project (BioScan)
- 🎖️ **4th place — Polytechnique Sousse CTF** (team Hunters) — cryptography, web & reverse engineering
- 📜 **Network Security** — Cisco Networking Academy *(verified)*
- 🎯 **eJPT** — eLearnSecurity Junior Penetration Tester *(in progress)*
- 🗣️ **Languages** — Arabic (native) · French C1 (TCF) · English C1 (EnglishScore) · Spanish A2

---

## 🛠️ Technologies & Tools

**Offensive Security**
`Penetration Testing` · `Web App Security` · `OWASP Top 10` · `Nmap` · `Burp Suite` · `Metasploit`

**SOC / Blue Team**
`Phishing & Email Analysis` · `IOC Lookup` · `SIEM` · `Grafana + Loki` · `Threat Intel`

**Development**
`Python` · `FastAPI` · `React` · `.NET` · `SQL`

**Cloud & Infrastructure**
`Docker` · `Azure` · `Linux` · `Git` · `CI/CD` · `Ollama`

**Networking**
`Cisco` · `pfSense` · `GNS3` · `TCP/IP` · `Firewalls` · `VLANs`

---

## 🎯 What I Build

**Build → Understand → Break → Secure**

From developing applications and cloud infrastructure, to testing their security, investigating vulnerabilities, and building defensive tooling. I care about tools that are practical, private by default, and secure in their design — not just in theory.

---

## 💻 Run Locally

This portfolio is a static site — no build step, no server-side code.

```bash
git clone https://github.com/Givemeboga/Portfolio.git
cd Portfolio
python -m http.server 8000
```

Then open **http://localhost:8000**.

---

## 📫 Connect

[GitHub](https://github.com/Givemeboga) · [LinkedIn](https://www.linkedin.com/in/youssef-ben-chaouacha-646715270/) · youssef.ben.chaouacha@gmail.com

---

> **Build it. Understand it. Break it. Secure it.**
>
> — **Gl1tch**
