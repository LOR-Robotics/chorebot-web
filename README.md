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
| `index.html` | Single-page landing |
| `styles.css` | Forest green + cream brand styles |
| `script.js` | Mobile nav + year |
| `assets/` | SVG mark, wordmark, favicon, hero illustration |
| `docs/hosting.md` | Hosting notes (Pages now; optional API later) |

## Brand notes

- Company: LOR Robotics (working brand)
- Product: ChoreBot
- Palette: forest green + cream
- Contact placeholder: `hello@lor-robotics.com` (domain unconfirmed)
- Not affiliated with Chore Robotics (US) or other “Chore” brands
