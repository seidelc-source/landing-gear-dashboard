# Landing Gear Results Dashboard

A self-contained, interactive web dashboard for gradient-boosted **landing-gear
jig-drop** surrogate models, reconstructed from public NASA / NACA / FAA
landing-gear and impact-test reports.

**Live site:** _(GitHub Pages URL — added after first publish)_

## What's here

This repository contains only the published web app:

- `index.html` — the entire dashboard in one file (data is embedded; no server,
  no build step, no external scripts). Open it locally by double-clicking, or
  view it on the live site above.
- `.nojekyll` — tells GitHub Pages to serve the file as-is.

The data pipeline, source PDFs, and model-training code live in a separate
(private) project repository and are intentionally not published here.

## Updating

The dashboard is regenerated in the main project repo and copied here. From the
project root run:

```bash
make publish
```

This rebuilds `index.html` from the latest model outputs and pushes it.
