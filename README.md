# LOR Robotics · ChoreBot — marketing site

Static brochure site for **LOR Robotics** (working brand) and product **ChoreBot**.
No framework, no build step. Hosted on [Cloudflare Pages](https://pages.cloudflare.com/).

## Live

- **Primary:** https://chorebot-web.pages.dev
- Preview alias: https://4a9717c3.chorebot-web.pages.dev
- Repo: https://github.com/LOR-Robotics/chorebot-web

Custom domain later (e.g. `lor-robotics.com`) once DNS is ready.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
# or: python3 -m http.server 8080
```

## Deploy on Cloudflare Pages

Already connected to this repo under Oliver Holt’s Cloudflare account.

Build settings (for rebuilds / new projects):

- **Framework preset:** None
- **Build command:** *(leave empty)*
- **Build output directory:** `/` (project root — the folder that contains `index.html`)

No Node build is required. `_headers` is applied automatically by Pages.

## Contents

| Path | Role |
|------|------|
| `index.html` | Landing — product, software-first, Demo (#demo = G0 status R4), where, contact |
| `investors.html` | Soft investor overview stub · deck coming soon · R4 demo honesty pointer |
| `styles.css` | Forest green + cream brand styles |
| `script.js` | Mobile nav + year |
| `assets/` | SVG mark, wordmark, favicon, hero illustration |
| `docs/hosting.md` | Hosting notes (Pages now; optional API later) |

## Demo claim status

Public `#demo` uses claim rung **R4** plain-English (soft G0 virtual evidence; stubs; no public Gazebo pitch clip; not DoD complete).
Do not ship “Virtual demo coming soon” or “full virtual demo complete” copy.
`DEMO_CLIP_URL` / `data-demo-clip-url` stays empty until an R5 GUI mp4 is published.
Source of truth: `/workspace/chorebot/investor/g0-demo-claim-boundaries.md`.

## Brand notes

- Company: LOR Robotics (working brand)
- Product: ChoreBot
- Palette: forest green + cream
- Contact placeholder: `hello@lor-robotics.com` (domain unconfirmed)
- Not affiliated with Chore Robotics (US) or other “Chore” brands
