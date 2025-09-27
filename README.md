# micro-saas-starter

Starter template for micro-SaaS built the same way every time.

## What this gives you
- Opinionated folders: `/web` (Next.js UI), `/api` (handlers), `/pkg` (shared), `/infra` (CI/scripts)
- `.env.example` to copy into `.env`
- Ready for Cursor “vibe coding”

## How to use this as a template
1. Click **Use this template** (green button on GitHub).
2. Name your new repo (e.g., `lead-scoring-saas`), keep **Public** for now.
3. In the new repo: create `.env` by copying `.env.example` and filling secrets.

## Local run (later, when we scaffold code)
- Install: Node LTS + pnpm
- Commands: `pnpm install`, `pnpm dev` (details will be added after scaffolding)

## Conventions
- TypeScript everywhere
- Keep business logic in `/pkg`
- Small commits, clear messages
- Add TODOs with `// TODO:` and file an Issue if it takes >15 minutes

## Next tickets (open Issues)
- [ ] Scaffold Next.js app in `/web`
- [ ] Add basic API route and healthcheck in `/api`
- [ ] Add CI: lint + typecheck on PR
- [ ] Add seed script + SQLite via Prisma
- [ ] Set up Stripe test keys (optional)
