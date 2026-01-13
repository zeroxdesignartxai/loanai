# Project Brain: Addy AI

## Product vision
Addy AI is a modern SaaS assistant that helps mortgage professionals close loans faster by automating document processing, borrower follow-ups, and underwriting readiness checks.

## Target users
- Loan officers, processors, and branch managers at mortgage lenders.
- Operations and compliance teams needing clean, audit-ready files.

## Brand rules
- Product name: **AI Loan Officer Assistant (Addy AI)**.
- Tone: confident, trustworthy, and finance-forward.
- Visuals: clean SaaS layout, calming blues, high-contrast CTAs.

## Tech stack
- Astro + React/Svelte support (frontend only in this MVP).
- SCSS for styling.
- Node.js runtime for local dev and builds.

## Integrations
- Stripe (planned): free trial, single monthly plan, customer portal.
- Auth (planned): email/password + Google SSO.

## Deployment environments
- Not configured in repo. Intended for Vercel/Netlify/Fly.io.

## Commands (auto-detected)
- Install: `npm ci`
- Build: `npm run build`
- Dev (optional): `npm run dev`

## Execution pipeline
1. Install dependencies
2. Lint (no lint script found)
3. Unit tests (no test script found)
4. Integration/E2E tests (none found)
5. Build
6. Deploy (not configured)

## Known issues
- No automated lint/test scripts in `package.json` yet.

## Decision history
- 2024-??-??: Rebuilt marketing site and dashboard for Addy AI MVP.
- 2024-??-??: Established Project Brain and changelog scaffolding.

## Roadmap
1. Wire up real authentication + Stripe checkout/session creation.
2. Add document processing API endpoints + storage.
3. Build admin console for branch managers.
4. Add audit logs and compliance exports.

## Run log
- 2026-01-13: `npm ci` failed (missing package-lock.json). Ran `yarn install --frozen-lockfile` with peer warnings. Build succeeded via `npm run build`.
