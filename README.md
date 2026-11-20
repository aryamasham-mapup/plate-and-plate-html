# plate-and-plate-html

Static HTML presentation (`presentation.html`).

## Deploy on Render

1. Render dashboard → **New + → Blueprint** → select this repo.
2. Render reads `render.yaml` and creates a free static site.
3. Click **Apply**. Every push to `main` redeploys automatically.

`/` serves `presentation.html` (via the rewrite in `render.yaml`, with `index.html` as a fallback redirect).
