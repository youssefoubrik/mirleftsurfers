# Mirleft Surfers – holding site

Static site served by Cloudflare Workers (static assets).

- Site files: `public/` (FR at `/`, plus `/en/`, `/de/`, `/es/`, `/pl/`)
- Deploy: push to `main`; Cloudflare Workers Builds runs `npx wrangler deploy`
- Local preview: `npx wrangler dev`
