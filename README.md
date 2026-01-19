# Shannon-bar

A small static landing for "SHANSON" — a luxury karaoke bar concept. This repository contains the front-end markup, styles and a minimal script for a parallax hero, animated headings and a menu (kitchen / bar / hookah).

Проект: лендинг для караоке-бара в премиальном стиле — чистый HTML/CSS/JS.

## Features / Возможности
- Full-screen parallax hero with layered depth effects
- Shimmering gold headings and animated divider
- Sticky translucent navigation
- Responsive layout with mobile-specific tweaks
- Simple intersection-observer based entrance animations
- Menu sections for Kitchen, Bar and Hookah

## Preview
Open `index.html` in a modern browser (Chrome / Firefox / Safari) to view the page locally. If you want a live demo on GitHub Pages, see "Deploy" below.

## Contents (suggested)
- index.html — main markup (hero, nav, sections)
- assets/
  - css/ (if you split styles)
  - js/ (if you split scripts)
  - img/ (images, logos)
- README.md
- LICENSE

> Note: The repo currently contains a minimal README. If you have the HTML from the project (hero/index) it can be added as `index.html`.

## How to run locally
1. Clone the repo:
   git clone https://github.com/tyrbo-94/Shannon-bar.git
2. Open `index.html` in your browser:
   - double-click the file or
   - run a simple static server, e.g.:
     - Python 3: `python -m http.server 8000` then open `http://localhost:8000`

## Development notes / Suggestions
- Consider splitting large inline styles into `styles.css` for better maintainability.
- Move inline script to `main.js` and enhance accessibility (skip links, focus states).
- Add image assets (logo, background textures) and optimize them (WebP/AVIF).
- Add meta tags for SEO / social preview (Open Graph / Twitter Card).
- Add a LICENSE (MIT recommended) and a simple GitHub Actions workflow for linting.

## Deployment
- GitHub Pages: add `index.html` to the repository root and enable Pages in repo settings (branch `main` / `/ (root)`).
- Or use any static host: Netlify, Vercel, Surge.

## License
Add a LICENSE file (e.g. MIT) if you want to make the project open-source.

## Contact
Repo owner: tyrbo-94