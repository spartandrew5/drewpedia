# wiki

Source for my personal docs/tutorials site, built with [MkDocs](https://www.mkdocs.org/).

## Local setup

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open http://localhost:8000 to preview with live-reload.

## Deploying

```bash
mkdocs gh-deploy
```

This builds the site and pushes it to the `gh-pages` branch, which GitHub Pages serves automatically.

## Structure

- `mkdocs.yml` — site config, theme, and navigation
- `docs/` — all Markdown content lives here
