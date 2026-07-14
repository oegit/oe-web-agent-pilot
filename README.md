# Open English — Landing Page Pilot

Live preview of a bilingual (Spanish · Brazilian Portuguese) landing page built
from a 1400px Figma design as the end-to-end pilot of a portable Figma-to-HTML
web-development agent.

## Live pages

- **Español:** https://oegit.github.io/oe-web-agent-pilot/es/
- **Português (BR):** https://oegit.github.io/oe-web-agent-pilot/pt/
- Root `/` redirects to `/es/` (x-default).

## What this is

A production-style static build — vanilla HTML5 + CSS + a Bootstrap 12-column
grid, no build step at runtime. Every color/font/spacing is a design token;
rasters are WebP, icons/logos are inline SVG, dark mode is token remapping via
`prefers-color-scheme`, and each language is a real crawlable page set with
bidirectional `hreflang`.

**Quality:** Lighthouse 97 · 97 · 100 · 100 (Performance · Accessibility ·
Best Practices · SEO) on both language pages.

## Pilot placeholders

This is a preview, so launch-specific integrations are scaffolded but inert:

- **Analytics** — GTM snippet is present but commented (activates when a real
  container ID is set).
- **Lead form** — posts nowhere (submit is guarded) until a real endpoint is set.
- **`og:image`** — references a placeholder path; a real 1200×630 image is added
  at launch.

Testimonials, brand logos, and photography come from the source Figma design.
