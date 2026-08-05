# Brian King'ori Murage — Portfolio

Personal portfolio site showcasing my background in IT infrastructure and systems administration, and my ongoing transition toward networking and cybersecurity.

**Live site:** https://brian-murage.github.io

## About

I'm an IT Assistant at English Press Limited, working within a two-person IT team supporting Active Directory, Microsoft 365, network infrastructure, disaster recovery, and end-user support. I'm currently pursuing the Cisco CCNA through Cisco Networking Academy, building toward a career in networking and cybersecurity.

This site tracks where I actually am in that journey — completed work, in-progress certifications, and skills I'm still building — rather than overstating experience I don't yet have.

## Site structure

```
.
├── index.html              # Home page (must stay at repo root for GitHub Pages)
├── css/
│   └── styles.css          # Shared stylesheet for every page
├── pages/
│   ├── about.html
│   ├── skills.html
│   ├── projects.html
│   ├── writeups.html
│   ├── certifications.html
│   ├── cv.html
│   └── contact.html
├── assets/
│   └── Brian_Murage_CV.pdf # Downloadable CV
└── README.md
```

> **Note:** `index.html` has to remain at the repository root — GitHub Pages only serves the root `index.html` as the site's home page at `https://brian-murage.github.io/`. Every other page lives one level down in `pages/`, and references the stylesheet and CV via relative paths (`../css/styles.css`, `../assets/Brian_Murage_CV.pdf`).

## Tech

Plain HTML5 and CSS3 — no frameworks, no build step. Fonts (Inter, JetBrains Mono) loaded from Google Fonts.

## Running locally

No build tools required. Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Hosted via **GitHub Pages**, deploying from the `main` branch, `/ (root)` folder. Any push to `main` updates the live site within a minute or two.

## Status

This portfolio is actively updated as I complete more of the CCNA program and add hands-on lab writeups. Sections still filling in are labeled **In Progress**.
