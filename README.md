# Farid Hussein Portfolio

This repository contains the production-built static version of Farid Hussein's bilingual portfolio. It includes the site, locally bundled fonts, brand assets, the colored Looped-Fa symbol, social-sharing image, and English and Arabic portfolio PDFs.

## Deploy with Vercel

1. Import this GitHub repository into Vercel.
2. Keep the project root at `/`.
3. Deploy. No environment variables, package installation, or build command are required.

The included `vercel.json` tells Vercel to serve the already-built files from the repository root, avoiding a redundant build step. Hashed assets receive long-lived immutable caching; standard security headers are also set.

## Social preview image

After the first deployment, update both the `og:image` and `twitter:image` values in `index.html` to the full HTTPS address of `brand/og-share.png` on your live domain. This lets WhatsApp and other messaging apps load the social preview image.

## Included files

- `index.html` and the compiled files in `assets/`
- `brand/` logos, favicons, Apple touch icon, and 1200 × 630 social card
- `downloads/farid-hussein-portfolio-en.pdf`
- `downloads/farid-hussein-portfolio-ar.pdf`
- `vercel.json` deployment and cache configuration

## Local preview

Because this is a static production build, it can be previewed with any static file server. For example, run `npx serve .` from the repository root.
