# Diomale Romero — Developer Hub

Personal developer portfolio website for Diomale Romero: game development, software engineering, projects, certificates, and experiments.

## Overview

This is a static, no-build website (vanilla HTML / CSS / JavaScript) with a central homepage that routes visitors to focused game and software portfolios, plus a projects carousel, certificates carousel, timeline, skills grid, and contact form.

## Features

- Central hub with portal cards into the game and software portfolios
- Auto-scrolling (infinite loop) projects carousel with drag / wheel / touch support
- Drag-based certificates carousel
- Developer-status terminal hero with floating tech stack
- Scroll-reveal animations, particle field, grid/glow backgrounds
- Certificate modal (focus-trapped, keyboard accessible)
- Contact form with honeypot spam protection via EmailJS
- Responsive layout (breakpoints at 1040 / 860 / 680 / 420 px)
- `prefers-reduced-motion` support

## Local Development

No build step required. Serve the folder with any static server, e.g.:

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .
```

Then open `http://localhost:8080`.

## Structure

```
index.html            Central developer hub (home)
game_web.html          Game development portfolio (placeholder)
software_web.html      Software development portfolio (placeholder)
style.css             Main styles (design tokens, layout, components, responsive)
modal.css             Certificate modal styles
script.js             UI logic: nav, particles, reveals, modal, carousels, EmailJS
favicon.svg           Site favicon
My-Certificate/       Certificate assets (PNG previews + PDF proofs)
```

## Deployment

Static site intended for GitHub Pages (see repository remote: `diomale/diomale-main-portfolio`).
