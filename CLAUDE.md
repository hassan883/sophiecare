# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the website for **Sophie's Homecare**, a Residential Care Facility for the Elderly (RCFE) in El Dorado Hills, CA. It is a static single-page website with no build system, framework, or package manager.

## Architecture

- **`index.html`** — Single-page site with all sections (Home, About, Services, Our Home, Gallery, Tour, Contact) defined as anchor sections
- **`css/styles.css`** — All styles in one file
- **`js/main.js`** — Vanilla JS handling hamburger menu, smooth scrolling, AOS animations, navbar scroll behavior, gallery lightbox, and tour form
- **`images/logo/`** — Logo assets
- **`prompt.md`** — Original content/design requirements document with copy, color palette, and site structure

## Running Locally

Open `index.html` directly in a browser, or use any static file server:
```
python3 -m http.server 8000
```

No build step, no dependencies to install.

## External Dependencies (loaded via CDN)

- Google Fonts (Lato, Playfair Display)
- Font Awesome 6.5.1 (icons)
- AOS 2.3.4 (scroll animations)

## Design System

Defined in `prompt.md` and implemented in `css/styles.css`:

| Role | Color | HEX |
|------|-------|-----|
| Primary | Lavender | `#8E6BD3` |
| Secondary | Warm Beige | `#E6D9CC` |
| Accent | Light Lavender | `#B9A6E8` |
| Text | Charcoal/Dark Navy | `#1C1C2E` |
| Optional Accent | Sage Green | `#8FAF9B` |

## Key Details

- Licensed RCFE, License #09950228
- Address: 4505 Brisbane Circle, El Dorado Hills, CA 95762
- Administrators: Hamza Malik (916-342-0264), Rommana Asim (916-708-5100)
- 6-bed boutique care home
- SEO keywords target "RCFE/Assisted Living/Senior Care El Dorado Hills"
- Schema.org LocalBusiness JSON-LD is embedded in `index.html`
