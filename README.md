# Punk Positronics — The Fortress

The public site and "Open Ops" record for [Punk Positronics LLC](https://punkpositronics.com): disintermediation — removing the parasitic middlemen from digital and physical infrastructure to empower community sovereignty.

- **Digital Sovereignty** — Cloud Exit Audits, homestead implementation on refurbished hardware, Guardian Retainers
- **Physical Sovereignty** — fulfillment for independent authors
- **Education** — the Open Ops Manual, masterclasses, and build-days

Built as an [Astro](https://astro.build) static site deployed to Cloudflare Workers.

## Development

```bash
npm install        # install dependencies
npm run dev        # dev server at localhost:4321
npm run build      # production build to ./dist
npm run deploy     # deploy to Cloudflare Workers
```

## Structure

- `src/pages/` — routes (home, service wings, manual, blog)
- `src/content/blog/` — blog posts ("Punk Pages") in Markdown/MDX
- `src/components/` — header, footer, head metadata
- `public/` — static assets (fonts, icons, brand images)

## Open Ops

The operating philosophy is radical transparency: the business's systems, struggles, and wins are documented in public. This repo is part of that record.
