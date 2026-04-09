# Gaza Stack Frontend

Astro static site. Part of [Gaza Stack](https://github.com/catFurr/kon).

## Stack
- Astro (static output)
- Tailwind CSS
- Lucide icons (via lucide-astro)
- Bun as package manager

## Commands
- `bun install` — install deps
- `bun run dev` — start dev server
- `bun run build` — build static site to `dist/`

## CI/CD
- Push to main builds and deploys to production via [kon](https://github.com/catFurr/kon)
- PRs get automatic preview deployments (`branch-name.buytelegram.store`)
- Each commit also gets its own URL (`short-sha.buytelegram.store`)
- PR comments are automatically posted/updated with preview URLs
- Build caching via Bun dependency cache

## Rules
- AI must NEVER include itself as co-author in commits or anywhere else
- AI must NEVER add Co-Authored-By lines to commits
