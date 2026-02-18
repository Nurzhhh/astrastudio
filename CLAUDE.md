# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Landing page for **Astra Studio** — beauty salon in Rudny, Kazakhstan (astrastudio.kz). Site content is in Russian. No build system, no dependencies — pure vanilla HTML5, CSS3, and JavaScript.

## Development

No build or install steps. Open `index.html` in a browser or serve with any static file server.

## Architecture

- **`index.html`** — Single-page: header, hero, about (owner Zhuldyz), services & prices (3 categories + special offer), gallery, contacts, footer, fixed WhatsApp button
- **`css/style.css`** — All styles with CSS variables for theming, responsive breakpoints at 1024px, 768px, 480px
- **`js/main.js`** — Sticky header, mobile burger menu, smooth anchor scrolling, Intersection Observer scroll animations
- **`images/logos/`** — `black.jpeg` (gold on dark, used in hero), `white.jpeg` (gold on white, used in header/footer)
- **`images/workers/`** — Owner photos: `IMG_1940.JPG.jpeg` (portrait), `IMG_1943/1944` (certificates)

## Conventions

- **Color palette (CSS vars):** `--gold: #C9A55C`, `--graphite: #2D2D2D`, `--milky: #FFFAF5`, `--beige: #F5EDE3`, `--white: #FFFFFF`
- **Fonts:** `Cormorant Garamond` (headings), `Jost` (body)
- **CSS naming:** BEM (`.service-category__title`, `.btn--primary`)
- **Animation:** `.animate-on-scroll` + `.visible` via Intersection Observer
- **WhatsApp number:** +7 708 754 50 93 (used in all CTA links)
- **Prices:** In Kazakhstani tenge (&#8376;). Services can be updated directly in HTML `<ul class="service-list">` elements
- **SEO keywords:** "салон красоты в Рудном", "маникюр Рудный", "наращивание ресниц Рудный"
