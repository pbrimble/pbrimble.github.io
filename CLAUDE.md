# Personal Website — CLAUDE.md

## Project Overview

**URL:** https://pbrimble.github.io
**Repo:** https://github.com/pbrimble/pbrimble.github.io
**Framework:** Jekyll (academicpages theme, based on Minimal Mistakes)
**Purpose:** Paul Brimble's personal academic website — bio, research, CV, publications.

## File Locations

| Resource | Path |
|---|---|
| GitHub repo | `/Users/pbrimble/Github/pbrimble/pbrimble.github.io/` |
| Overleaf (CV) | `/Users/pbrimble/Library/CloudStorage/Dropbox-UniversityofMichigan/Paul Brimble/Apps/Overleaf/pbrimble/` |

## Site Structure

| Directory/File | Purpose |
|---|---|
| `_config.yml` | Site-wide settings (title, URL, social links, navigation) |
| `_pages/` | Static pages: about, research, publications, CV, etc. |
| `_posts/` | Blog posts (rarely used) |
| `_publications/` | Individual publication entries |
| `_talks/` | Talk entries |
| `_teaching/` | Teaching entries |
| `_data/` | Navigation, author info, other structured data |
| `assets/` | CSS overrides, JS |
| `images/` | Images used across the site |
| `files/` | PDFs and downloadable files (e.g., CV) |
| `_layouts/`, `_includes/`, `_sass/` | Theme templates and styles |

## Key Pages

**Currently only the about page is functioning.** Other pages exist but are not actively maintained:

- `_pages/about.md` — **ACTIVE** — Homepage / bio, working papers, research in progress
- `_pages/research.md` — Inactive (research content consolidated to about page)
- `_pages/publications.md` — Inactive
- `_pages/cv.md` — Inactive

## Development

Run locally:
```bash
bundle exec jekyll serve
```

Or with dev config:
```bash
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Site builds and deploys automatically via GitHub Pages on push to `main`.

## CV / LaTeX

The Overleaf folder (`pbrimble`) is intended for a LaTeX-formatted CV. When ready, the compiled PDF should be exported to `files/cv.pdf` in this repo so it's linked from `_pages/cv.md`.

## Current Status

- Website is live and active at https://pbrimble.github.io
- Main pages: about, research, CV
- Future work: LaTeX CV via Overleaf
