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
| Overleaf (CV) | `/Users/pbrimble/University of Michigan Dropbox/Paul Brimble/Apps/Overleaf/Paul Brimble/` |

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

- `_pages/about.md` — Homepage / bio
- `_pages/research.md` — Research page (working papers, work in progress)
- `_pages/publications.md` — Publications list
- `_pages/cv.md` — CV page

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

The Overleaf folder (`Paul Brimble`) is intended for a LaTeX-formatted CV. When ready, the compiled PDF should be exported to `files/cv.pdf` in this repo so it's linked from `_pages/cv.md`.

## Current Status

- Website is live and active at https://pbrimble.github.io
- Main pages: about, research, CV
- Future work: LaTeX CV via Overleaf
