# phData Delivery Enablement Bootcamp

A self-contained static site (`index.html`, no build step or external assets) for the Delivery Engagement Bootcamp.

## Deploy

Deployed to GitHub Pages by `.github/workflows/deploy.yml` on every push to `main`.

One-time setup: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
