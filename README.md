# The Unique Production

A single-page marketing website for **The Unique Production** — a photography, videography, drone, digital content and event management agency based in Rajshahi City, Bangladesh.

**Live site:** [theuniqueproductions.com](https://theuniqueproductions.com) · Fallback: [unique-production.pages.dev](https://unique-production.pages.dev)

## About

The Unique Production covers weddings, college/university Rag Day events, corporate functions, product/personal photoshoots, drone aerial footage, live streaming, and full event planning & management. This repo holds the marketing site used to showcase services and drive bookings via WhatsApp.

## Tech

Plain static HTML/CSS/JS — no framework, no build step.

- `index.html` — the main site (hero, services, portfolio, contact)
- `terms.html` — Terms of Service
- `refund-policy.html` — Refund & Cancellation Policy
- `robots.txt`, `sitemap.xml` — SEO crawling config

Fonts are loaded from Google Fonts (Playfair Display, Poppins); all styling is inline in each page via `<style>` blocks.

## Local development

No build tools required. Just open `index.html` in a browser, or serve the folder with any static file server:

```bash
npx serve .
```

## Deployment

Hosted on **Cloudflare Pages**, connected directly to this GitHub repository. Every push to `main` triggers an automatic rebuild and deploy — no build command or output directory needed since the site is plain static HTML at the repo root.

## Editing content

All page content lives directly in the HTML files — there's no CMS or templating layer. To update copy, services, or contact links, edit the relevant section in `index.html` and push to `main`.

## Contact

- WhatsApp: [+880 1710-318956](https://wa.me/8801710318956)
- Facebook: [facebook.com/theuniqueproductions](https://www.facebook.com/theuniqueproductions)
- Instagram: [@_the_unique_productions](https://www.instagram.com/_the_unique_productions)
- YouTube: [@theuniqueproductions](https://www.youtube.com/@theuniqueproductions)
