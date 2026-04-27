# nicholasvest.com

Personal academic website for **Nicholas A. Vest**, postdoctoral research
scientist at the University of Florida.

Built with [Hugo](https://gohugo.io/) on the
[Hugo Blox Academic](https://github.com/HugoBlox/theme-academic-cv) theme,
deployed via GitHub Pages.

## Local development

```bash
hugo server -D
```

Requires Hugo (extended) `0.124.x` or newer — see
`.github/workflows/publish.yaml` and `netlify.toml` for the pinned version
used in CI.

## Structure

- `content/` — site content (home page, author profile, projects, consulting)
- `assets/scss/custom.scss` — editorial style overrides (typography, layout, color)
- `config/_default/` — Hugo configuration (site, params, menu, languages, modules)
- `layouts/partials/site_head.html` — Google Fonts (Libre Baskerville + DM Sans)
- `static/uploads/` — downloadable assets (CV, etc.)

## Deployment

Pushes to `main` are built and deployed by the
`Deploy website to GitHub Pages` workflow in `.github/workflows/publish.yaml`.
