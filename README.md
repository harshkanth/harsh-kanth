# harshkanth.com

Source for [harshkanth.com](https://harshkanth.com), the documentation portfolio of Harsh Kanth, built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Run locally

```bash
pip install -r requirements.txt
mkdocs serve
```

Open http://127.0.0.1:8000.

## Publish

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site with `--strict` and publishes it to the `gh-pages` branch. To publish manually instead, run `mkdocs gh-deploy`.

## Structure

| Path | Contents |
|------|----------|
| `docs/index.md` | Home page (hero, selected work, services summary) |
| `docs/work/` | Case studies, one page per project |
| `docs/samples/` | Complete public writing samples |
| `docs/experience.md`, `services.md`, `about.md`, `contact.md` | Supporting pages |
| `docs/assets/` | Logo, images, stylesheet, résumé |
| `overrides/main.html` | Social sharing meta tags |

## Add a case study

1. Copy an existing page in `docs/work/` and rename it.
2. Keep the structure: lead paragraph, facts panel, The challenge, What I delivered, How I approached it, What this shows.
3. Add the page to `nav` in `mkdocs.yml` and a card to `docs/work/index.md`.
