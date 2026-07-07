# EE Metro — ai.eemetro.com landing page

Single-page Astro site. All HTML, CSS, and JS live in `src/pages/index.astro`.

## Setup on a new machine

1. Install Node.js LTS (v20+) from https://nodejs.org
2. In this folder:
   ```
   npm install
   npm run dev      # local preview at http://localhost:4321
   npm run build    # production build to dist/
   ```

## Deploy

- GitHub remote: https://github.com/starlyns/eemetro (branch `main`)
- Cloudflare Pages: build command `npm run build`, output directory `dist`, no env vars
- Custom domain: `ai.eemetro.com` (CNAME to the Pages project)

## Before going live

- Set the real booking link in `BOOK_URL` (top of `src/pages/index.astro`)
- Confirm package tier pricing in the Packages section

## House rules

- Never name software tools/platforms in visible copy or alt text — capability language only
- Design tokens (do not change): green `#175239`, dark green `#0E3B27`, amber `#E89B2E`, paper `#F7F6F2`, ink `#1E2A24`
- Fonts: Archivo (display), Figtree (body), IBM Plex Mono (numbers/labels) — self-hosted via Fontsource
- The ROI section styled as a wholesale purchase order is the signature element — keep it
