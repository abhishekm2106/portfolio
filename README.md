# Abhishek Mohanty · Portfolio

Personal portfolio of Abhishek Mohanty, frontend and full-stack engineer building Gen AI products.

**Live:** https://abhishekm2106.netlify.app

## What's inside

A single, dependency-free `index.html` (HTML, CSS and vanilla JavaScript) designed like a design-tool canvas:

- **Live theme engine.** Pick an accent hue and the whole site recolors. Hover and active shades are derived automatically through CSS variables, the same approach I built for Scrut's customers. Typeface (Instrument Serif, Anybody, Bagel Fat One) and appearance (dark by default, light, or system) are switchable too, and choices persist in `localStorage`. Each new visit starts with a random preset accent until the visitor picks their own.
- **Breathing dot grid.** A canvas background that ripples outward from the center, with per-dot twinkle and an accent glow that follows the cursor.
- **Frame selection.** Each section is a "frame" with Figma-style selection handles and a live size badge on hover.
- **Streaming demo.** A simulated SSE progress replay of the AI-assisted Trust Vault setup, with three parallel LangGraph-style subtasks.
- Respects `prefers-reduced-motion`, works at phone width, and supports light and dark themes.

Fonts load from Google Fonts. Logos, icons ([Simple Icons](https://simpleicons.org)) and images are inlined, so there are no other external requests.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Deploy

```bash
npx netlify-cli deploy --prod --no-build --dir . --site abhishekm2106
```
