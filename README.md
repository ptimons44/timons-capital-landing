# Timons Risk Capital - Landing Page

Minimal static landing page for Timons Risk Capital, currently in stealth mode.

## About

Timons Risk Capital provides alternative risk transfer solutions for primary property insurance companies.

## Viewing Locally

Open `index.html` in your browser, or use a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deployment

### Cloudflare Pages

This site is configured for Cloudflare Pages deployment:

```bash
npx wrangler pages deploy .
```

Or with a specific project name:
```bash
npx wrangler pages deploy . --project-name=timons-capital-landing
```

Cloudflare settings:
- Build command: `exit 0` (no build needed)
- Deploy command: `npx wrangler pages deploy .`
- Root directory: `/`

### Other Platforms

Can also be deployed to GitHub Pages, Netlify, Vercel, or any static hosting service.
