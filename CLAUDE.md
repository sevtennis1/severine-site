# Severine Toussaert Academic Website

## Overview
Static academic portfolio site for Séverine Toussaert, Associate Professor of Economics at the University of Oxford. Pure HTML/CSS with minimal inline JS — no build tools, no dependencies.

Live at: https://joseph-a-levine.github.io/severine-site

## Structure
- `index.html` — Homepage (hero with photo, bio, affiliations, project links)
- `research.html` — Research papers with category filtering, expandable story panels, and BibTeX copy-to-clipboard
- `cv.html` — Academic CV with downloadable PDF (`new_CV.pdf`)
- `media.html` — Podcast and seminar series projects
- `styles.css` — All styling (CSS custom properties for theming)
- `headshot.jpg` — Professional photo (John Cairns, Oxford)
- `papers/` — Local PDFs, slides, appendices, and replication data for research papers
- `missing_files_tracker.md` — Tracks remaining files needed from Sev (share-ready)

## Design
- **Fonts**: Playfair Display (headings), Source Sans 3 (body) via Google Fonts
- **Colors**: Warm academic palette — cream background, charcoal text, coral accent, soft blue secondary (see `:root` in `styles.css`)
- **Responsive**: Mobile breakpoint at 768px
- **Special section**: Research "graveyard" uses a dark slate color palette

## Development
- No build step — edit HTML/CSS directly
- JS is inline in `research.html` (filter chips, story panel toggles, BibTeX clipboard copy)
- All pages share identical nav; active state is set per-page
- Deploy via GitHub Pages

## Conventions
- All internal links use relative paths
- External links open in same tab (no `target="_blank"`)
- Published papers link to publisher URLs (DOI-resolved); working papers use local PDFs in `papers/`
- Footer appears on all pages with copyright + email
