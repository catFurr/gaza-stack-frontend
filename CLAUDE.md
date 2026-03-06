# Gaza Stack Frontend

Astro static site for the Gaza Stack landing page.

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
- Push to main builds and deploys to production
- PRs get automatic preview deployments (branch-name.buytelegram.store)
- PR close cleans up the preview
- Calls reusable deploy workflow from gaza-stack-backend

## Rules
- AI must NEVER include itself as co-author in commits or anywhere else
- AI must NEVER add Co-Authored-By lines to commits
