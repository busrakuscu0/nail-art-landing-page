# Begüm Nail Art — Static Landing Website

A static website highlighting Begüm Nail Art’s services and portfolio, built with semantic HTML and plain CSS, optimized for accessibility and responsive breakpoints.

## Features

- Responsive layout with mobile-first CSS and breakpoints at `768px` and `1024px`.
- Lightweight, no JavaScript required for core interactions (read-more toggles use native checkboxes).
- Image optimization using `picture` sources and `webp` assets with `loading="lazy"` on gallery images.
- Accessible markup: meaningful `alt` text, `aria-label` on major regions, and focus-friendly controls.

## Project structure

```
index.html
styles.css
assets/
    collection/
    icons/
    service-cards/
favicon/
    site.webmanifest
```

Key files:

- `index.html` — main page containing header, hero, about, services, collection carousel and footer.
- `styles.css` — all styling, variables, responsive rules and a11y-related media queries.
- `assets/` — images and SVG icons used across the site.
- `favicon/` — favicon and web manifest for browser tabs and mobile devices

## Links

- GitHub Repository: [View on GitHub](https://github.com/busrakuscu0/nail-art-landing-page)
- Live Site: [Visit the live site](https://begumnailart.com/)

## Fonts & Assets

- The project uses Google Fonts (`Raleway`, `Lato`, and `Inter`) linked from `index.html`.
- All images are stored in the `assets/` folder. For best performance in production, ensure the images are properly compressed and consider using responsive `srcset` and modern formats (WebP/AVIF).

## Accessibility & SEO notes

- Semantic HTML elements used throughout the site.
- All images include descriptive `alt` text.
- `aria-label` attributes added on major regions for better screen reader support.
- `lang="tr"` set for language declaration.
- Heading hierarchy optimized for accessibility and SEO.

## Credits

- Developed by Büsra Kuscu — design and content by the author.
- Fonts from Google Fonts.

---
