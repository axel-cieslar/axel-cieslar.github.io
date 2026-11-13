# cieslar.fr

Axel Cieslar’s personal website. A lightweight, single-page Astro site with a dark theme, system fonts, and no client-side JavaScript.

## Local development

Use a Node.js version compatible with Astro (>= 22.23.4, even-numbered release).

```sh
npm ci
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

The static output is generated in `dist/`.

## Deployment

Target domain: https://cieslar.fr

The GitHub Pages workflow is currently manual-only. It builds the site from the committed source and publishes only the generated static output.

No analytics, embedded third-party resources, or contact forms are included.
