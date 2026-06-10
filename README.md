# Paul Mollies — Portfolio

Personal portfolio of **Paul Mollies**, fluid mechanics & CFD engineer (aeronautical and space propulsion).

A single self-contained, bilingual (FR/EN) static page — no build step, no dependencies, no tracking.

🔗 **Live:** https://<your-username>.github.io/<repo-name>/

---

## Overview

The whole site is one `index.html` file. Fonts and images are embedded as base64, so the page is fully portable and works offline once loaded — open the file directly in a browser and it renders as-is.

## Features

- **Bilingual FR/EN** with an in-page toggle (French is the default content; English lives in `data-en` attributes).
- **Self-contained:** the Outfit typeface and the profile photo are inlined, so there are no external requests.
- **Animated hero:** an SVG turbine and an orbital path, plus reveal-on-scroll transitions.
- **Expandable cards** for experience, projects and interests, with detail modals.
- **Responsive** layout with breakpoints down to mobile widths.

## Tech

Plain HTML, CSS and vanilla JavaScript. No framework, no package manager, no build pipeline.

## Run locally

Either open `index.html` in a browser, or serve it (recommended, so relative links and the language toggle behave exactly as in production):

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

## Structure

```
.
├── index.html      # the entire site (markup, styles, scripts, embedded assets)
├── README.md
└── .gitignore
```

## Deploy with GitHub Pages

1. Push this repo to GitHub (see commands below).
2. In the repo: **Settings → Pages**.
3. Source: **Deploy from a branch**, branch **main**, folder **/ (root)**.
4. Save. The site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

Because the entry point is named `index.html`, GitHub Pages serves it automatically — no extra configuration needed.

## Usage / licence

No open-source licence is attached **on purpose**: this page carries personal content (photo, biography, contact details), so it is *not* meant for reuse. All rights reserved unless stated otherwise. The code structure may freely inspire your own work, but please don't republish the personal content.

## Contact

- **Email:** paul.molliess@gmail.com
- **LinkedIn:** [linkedin.com/in/paulmollies](https://www.linkedin.com/in/paulmollies)
