# ryanshook.org

**Live site:** [ryanshook.org](https://ryanshook.org)

The landing page for Ryan Shook — pastor and strategic AI advisor for churches and Christian organizations. Single self-contained HTML page with embedded styles, no JavaScript framework, no build step.

## Project structure

```
ryanshook.github.io/
├── index.html              # Single-page landing
├── favicon.svg             # Charcoal RS mark with vermillion accent
├── CNAME                   # Custom domain
├── robots.txt              # Crawl directives
├── sitemap.xml             # Search index
├── images/
│   ├── headshot.jpg        # Hero portrait
│   ├── Ryan Speaking.jpg   # Speaking section
│   ├── logos/              # Church logos used in the hero strip
│   │   ├── woodlands.png
│   │   ├── lifechurch.svg
│   │   ├── elevation.png
│   │   └── saddleback.svg
│   └── …
└── chokepoints/            # Standalone interactive page
```

## Page sections

1. **Hero** (charcoal) — H1 with vermillion-accented keyword, lede, credit line, headshot, social links, and a "Churches I've worked with" logo strip.
2. **Mission** (white) — Christ-centered positioning statement.
3. **Strategic support every church needs** (gray) — 2×2 card grid of capabilities.
4. **Speaking & teaching** (white) — image + booking CTA.
5. **Testimonial** (gray) — pull quote with vermillion gradient bar.
6. **Final CTA** (charcoal) — "Working through a hard problem?" + email/LinkedIn buttons.
7. **Footer strip** (charcoal) — name, role, contact, location.

## Tech stack

- **HTML/CSS only.** No JS framework, no build step.
- **Fonts:** [Inter Tight](https://fonts.google.com/specimen/Inter+Tight) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts CDN.
- **Hosting:** GitHub Pages, custom domain via CNAME.

## Design system

Tokens, IA, and live copy are documented in [`/Users/ryan/Documents/blog-repo/design.md`](../design.md) (sibling repo).

| Role | Value |
|---|---|
| Accent | `#fc5f2b` (vermillion) |
| Charcoal | `#18181b` |
| Surface | `#f4f4f5` |
| Hairline | `#e4e4e7` |
| Type | Inter Tight, weights 400 / 600 / 700 |
| Mono | JetBrains Mono 400 |
| Pill radius | 9999px |
| Card radius | 16px |

## SEO

Title, meta description, OG, Twitter card, and Schema.org `Person` + `ProfessionalService` blocks all align to the "AI advisor for churches and nonprofits" positioning. `<link rel="canonical">` set. Favicon at `/favicon.svg`.

## Local preview

```bash
python3 -m http.server 4173
# then open http://localhost:4173/
```

## Deployment

Push to `master`. GitHub Pages rebuilds within 1–2 minutes.

## Contact

Ryan Shook · contact@ryanshook.org · Houston, Texas
