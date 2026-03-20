# Severine Toussaert Academic Website

## Overview
Static academic portfolio site for Séverine Toussaert, Associate Professor of Economics at the University of Oxford. Pure HTML/CSS with minimal inline JS — no build tools, no dependencies.

## Structure
- `index.html` — Homepage (hero with photo, bio, affiliations, project links)
- `research.html` — Research papers with category filtering and expandable story panels
- `cv.html` — Academic CV with downloadable PDF (`new_CV.pdf`)
- `media.html` — Podcast and seminar series projects
- `styles.css` — All styling (CSS custom properties for theming)
- `headshot.jpg` — Professional photo (John Cairns, Oxford)

## Design
- **Fonts**: Playfair Display (headings), Source Sans 3 (body) via Google Fonts
- **Colors**: Warm academic palette — cream background, charcoal text, coral accent, soft blue secondary (see `:root` in `styles.css`)
- **Responsive**: Mobile breakpoint at 768px
- **Special section**: Research "graveyard" uses a dark slate color palette

## Development
- No build step — edit HTML/CSS directly
- JS is inline in `research.html` (filter chips + story panel toggles)
- All pages share identical nav; active state is set per-page
- Deploy via GitHub Pages at `joseph-a-levine.github.io/severine-site`

## Conventions
- All internal links use relative paths
- External links open in same tab (no `target="_blank"`)
- Footer appears on all pages with copyright + email
