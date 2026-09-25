# Hosting notes — ChoreBot brochure

## Now: Cloudflare Pages (static)

This site is a **brochure only** — HTML/CSS/JS, no server, no database, no auth.

**Recommended host:** Cloudflare Pages

- Connect the GitHub repo
- Framework preset: **None**
- Build command: empty
- Output directory: project root (`/` or `.`)

Optional: attach a custom domain (e.g. `lor-robotics.com`) once DNS is ready. Until then, use the `*.pages.dev` URL.

Security headers live in `_headers` at the site root and are applied by Pages automatically.

## Later (optional, not built)

If product demos need a small API (waitlist form, fleet status stub, auth for partners):

| Option | Fit |
|--------|-----|
| Cloudflare Workers / Pages Functions | Same account; edge; good for thin JSON APIs |
| Free tier elsewhere (e.g. Fly.io, Railway, Render) | Only if you need a long-running process |

Do **not** put secrets in this static repo. Keep any future API in a separate service or Pages Function with secrets in the host dashboard.

This document is guidance only — no API is included in v1.
