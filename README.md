# Institute for Ocular Vision & Research — Single Page Site

A clean, modern, and authoritative single-page website built with Tailwind CSS and Inter font. Fully responsive and accessible, designed to inspire trust and clarity.

## Tech Stack
- HTML (single file): `index.html`
- Tailwind CSS CDN
- Google Fonts (Inter)

## Color Palette
- Headings (Navy): #1d3557
- Body (Grey): #4a5568
- Accent (Teal): #14b8a6
- Background: #FFFFFF

## Sections
- Sticky Navigation (Home, About, Research, News, Contact)
- Hero (high-quality lab image)
- About Us (mission + icon)
- Research Cards (3): Glaucoma, Macular Degeneration, AI in Diagnostics
- Latest News (3 mock articles)
- Contact (form with validation)
- CTA (Navy block)
- Footer (contact + social)

## Local Development
- Open `index.html` directly in your browser
- Optional static server:
  - Python: `python -m http.server`
  - Node: `npx serve .`

## Accessibility
- ARIA labels on social links
- Reduced-motion-friendly smooth scrolling
- High contrast and focus-visible styles via Tailwind

## Deployment

### Option A: Netlify
1. Create a new Netlify site and connect this repo, or drag-and-drop in the UI.
2. Use the included `netlify.toml`. Build command: none. Publish directory: `/`.

### Option B: GitHub Pages (via GitHub Actions)
1. Push this repository to GitHub
2. Ensure Pages is enabled (Settings → Pages → Source: GitHub Actions)
3. The workflow in `.github/workflows/pages.yml` will build and deploy your static site.

## Customization
- Replace the hero image URL in `index.html` for a different visual style (e.g., abstract data viz)
- Update copy in About, Research, and News sections as needed
- Update footer contact details and social URLs

## License
Copyright © 2024 Institute for Ocular Vision & Research. All rights reserved.
