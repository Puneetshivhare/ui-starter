# UI Starter

A minimal, reusable Next.js + Tailwind + Framer Motion starter for spinning up a clean, animated project showcase page fast. Static-export ready (`next.config.mjs` sets `output: "export"`), so it deploys straight to Cloudflare Pages, Vercel, Netlify, or any static host — no server required.

## Using this for a new project

1. Copy this repo.
2. Edit `content.ts` — that's the only file you need to touch for copy (project name, tagline, description, badges, stats, features, architecture steps, GitHub link).
3. `npm install && npm run build` — output goes to `out/`.
4. Deploy `out/` (or connect the repo directly) to your static host.

## Structure

- `content.ts` — single source of truth for all page copy
- `components/Hero.tsx` — headline + stats
- `components/Features.tsx` — feature grid
- `components/Architecture.tsx` — pipeline/steps strip
- `components/CTA.tsx` — GitHub link callout
- `components/Nav.tsx` / `Footer.tsx`

Design system (colors, type, spacing) matches puneet.sbs — swap `tailwind.config.ts` colors to rebrand.
