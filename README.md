# BDBWin 5.0 — Landing Page

Marketing landing page for **BDBWin 5.0**, a complete rebuild of the BDBWin ERP platform. Built to introduce the product, explain what's new, and collect early-access signups.

🔗 **Live site:** <https://ahmmedtowfique.github.io/bdbwin-landing/>

## About BDBWin 5.0

BDBWin 5.0 is a full ERP rebuild — orders, finance, warehouse, procurement, POS — with a **Live Intelligence Layer** on top of operational data and an **AI Decision Layer** that gives the person running the business a plain-language morning briefing in 60 seconds.

The product is currently **in development**; this repo is the public-facing landing page used for early-access signups.

## Features

- Hero section with primary CTA ("Get Early Access")
- "The problem" — why current ERPs don't fit business operators
- Three-layer solution overview: **Full ERP Core**, **Live Intelligence Layer**, **AI Decision Layer**
- Module grid: Auftrag, Fibu, Lager, XmlMailer, Intelligence + AI
- 4-phase product roadmap
- Early-access CTA for existing clients
- **Bilingual** — 🇩🇪 German / English toggle
- **Theme toggle** — 🌙 dark / ☀️ light mode
- Smooth in-page anchor navigation

## Tech Stack

- Plain **HTML + CSS + vanilla JavaScript** — no framework, no build step
- Hosted on **GitHub Pages**

## Getting Started

### Run locally

```bash
git clone https://github.com/AhmmedTowfique/bdbwin-landing.git
cd bdbwin-landing
```

Then open `index.html` directly in a browser, or serve it with any static file server:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit <http://localhost:8000>.

## Deployment

The site is served via **GitHub Pages** at <https://ahmmedtowfique.github.io/bdbwin-landing/>. Pushes to `main` deploy automatically.

To configure / re-enable: **Repo → Settings → Pages → Source: `main` / root**.

## Project Structure

```
bdbwin-landing/
├── index.html   # The landing page — markup, styles, and scripts
└── README.md
```

## Status

In active development. The landing page reflects the current product narrative; copy, visuals, and modules may evolve as BDBWin 5.0 progresses.

## License

All rights reserved. No open-source license is granted; please do not reuse the code, copy, or assets without written permission.

## Author

Built by [@AhmmedTowfique](https://github.com/AhmmedTowfique).
