# Portfolio Website

Personal portfolio site for Shubham Malpani, Data Architect based in New York.

## About

A single-page editorial portfolio built as one self-contained HTML file. No frameworks, no build step, no dependencies. Ink/gold/ochre color system, canvas animations, accordion interactions, tab navigation, and modals, all in vanilla HTML/CSS/JS.

## Sections

- **Hero** with animated data-visualization canvas (floating tables, bar charts, dot grids)
- **Work** featuring two flagship projects: a full-stack data platform consolidating 21 source systems, and an AI analytics layer that surfaced $7.6M in unrealized capacity
- **What Else Shipped** with modal deep-dives into additional projects
- **About** and **Timeline** covering background and career progression
- **Opinions** on data engineering and leadership
- **Contact** with links to LinkedIn and resume

## Running locally

Open `shubham_website_v3.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/shubham_website_v3.html`.

## Tech

- Vanilla HTML, CSS, JS (no build tools)
- Canvas API for hero animation
- CSS custom properties for theming
- Responsive down to 375px
- Accessible: keyboard navigation, ARIA attributes, reduced-motion support

## License

All rights reserved.
