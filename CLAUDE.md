# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a minimal static landing page for Timons Risk Capital, a company in stealth mode that provides alternative risk transfer solutions for primary property insurance companies.

## Project Structure

This is a pure HTML/CSS static website with no build process or dependencies:
- `index.html` - Main landing page
- `styles.css` - Styling with responsive design
- No JavaScript framework or build tools required

## Development

To view the site locally, simply open `index.html` in a web browser or use a local server:
```bash
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Deployment

This site is configured for Cloudflare Pages deployment using Wrangler.

### Cloudflare Pages Deployment

Cloudflare settings:
- Build command: `exit 0` (no build needed for static site)
- Deploy command: `npx wrangler pages deploy .`
- Root directory: `/`

To deploy manually:
```bash
npx wrangler pages deploy .
```

Or deploy to a specific project:
```bash
npx wrangler pages deploy . --project-name=timons-capital-landing
```

The site can also be deployed to other static hosting services (GitHub Pages, Netlify, Vercel).
