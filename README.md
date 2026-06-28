# Poker Tales From Across the Table

Static website for the **Poker Tales From Across the Table** podcast, including episode pages, character archetypes, stories, psychology content, and RSS access.

## Project structure

The site is served from the `docs/` folder:

- `docs/index.html` — homepage
- `docs/episodes/` — episodes listing and individual episode page(s)
- `docs/characters/` — archetype hub and character pages
- `docs/stories/` — story-focused content
- `docs/psychology/` — poker psychology topics
- `docs/art/` — art and animation page
- `docs/assets/` — media/brand assets page
- `docs/about/` — creator/about page
- `docs/contact/` — contact and mailing list links
- `docs/rss/` — RSS landing page and podcast XML feed

## Run locally

From the repository root:

```bash
cd docs
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Publishing

This repo is set up like a GitHub Pages-style static site (content in `docs/`).  
Publish by deploying the `docs/` directory as your site root.
