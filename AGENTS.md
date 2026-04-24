# AGENTS.md — AI Coding Agent Guidelines

## Project Overview

- **Name**: wdd-api
- **Type**: Astro SSR website with Node.js adapter
- **Purpose**: Personal reflection journal with celestial position tracking
- **Node**: >= 22.12.0 required

## Commands

| Command | Description |
|---------|-------------|
| `npm run dev` | Start dev server (Astro) |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |

## Key Files

| File | Purpose |
|------|---------|
| [astro.config.mjs](astro.config.mjs) | Astro + Node adapter config |
| [src/pages/index.astro](src/pages/index.astro) | Main page — sun/moon positions via IP geolocation API |
| [src/pages/moon.astro](src/pages/moon.astro) | Moon-specific page |
| [public/script/main.js](public/script/main.js) | Client-side JavaScript |
| [public/style/style.css](public/style/style.css) | Styles |

## Architecture

- **SSR**: Pages use `export const prerender = false` for server-side rendering
- **API Integration**: 
  - `ipgeolocation.io/astronomy` — sun/moon altitude/azimuth
  - `bigdatacloud.net/reverse-geocode-client` — lat/lng → city name
- **Environment**: Uses `import.meta.env` for API keys (e.g., `IPGEO_API_KEY`)

## Conventions

- Astro components (`.astro` files) with frontmatter exports
- Client-side JS in `public/script/`
- CSS in `public/style/`
- Server-side logic in `.astro` page frontmatter

## Documentation

- [README.md](README.md) — Project reflection and daily logs