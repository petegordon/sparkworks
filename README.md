# sparkworks

Landing page for the **AI Improv** session at Sparkworks Startup Week.

> Pete and Dan vibe code an app with prompts from the audience.
> 4:00 PM at Meridian — 45 min.

Deployed at <https://sparkworks.jimandi.love>.

## Deploy

- Pushes to `main` deploy to GitHub Pages via `.github/workflows/deploy.yml` (publishes the repo root to the `gh-pages` branch).
- Pull requests get a preview at `https://sparkworks.jimandi.love/pr-preview/pr-N/` via `.github/workflows/pr-preview.yml`.

## Local preview

It's a static page — open `index.html` in a browser, or run any static file server:

```sh
python3 -m http.server 8000
```
