# Rodrigo Martinez — Portfolio

Single-page portfolio site. Static HTML/CSS/JS, no build step.

- `index.html` — the site
- `images/` — photos and product screenshots
- `metrics.json` — every number shown on the page. Each element with a `data-metric` attribute in `index.html` takes its text from the matching key on load, so a number can be updated here without touching the HTML. The HTML keeps the same text as a fallback.
- `images/cases/` — case study screenshots with client names and logos covered

## Local preview

Open `index.html` directly in a browser, or serve it:

```
npx serve .
```

## Deploy

Deployed via Netlify, connected to this repo's `main` branch. Publish directory: `/` (repo root). No build command needed.
