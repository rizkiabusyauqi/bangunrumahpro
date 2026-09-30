# Bangun Rumah Pro

Static multi-product landing page untuk BangunRumahPro.com

## Architecture

- `/` — product hub
- `/persiapan-bangun-rumah/` — product landing page
- Future products use one folder + `index.html` per product
- Shared design system lives in `/css`
- Shared brand assets live in `/assets/brand`
- Product-specific assets live inside each product folder

## Deployment

Designed for Cloudflare Pages with the `main` branch as production branch.

Static site: no build framework required.
