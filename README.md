# LOR Robotics · ChoreBot — marketing site

Static brochure site for **LOR Robotics** (working brand) and product **ChoreBot**.
No framework, no build step. Ready for [Cloudflare Pages](https://pages.cloudflare.com/).

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
# or: python3 -m http.server 8080
```

## Deploy on Cloudflare Pages

1. Push this directory as a GitHub repository (or connect the monorepo subdirectory).
2. In Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
3. Select the repo (and root directory if nested).
4. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (project root — the folder that contains `index.html`)
5. Save and deploy. Custom domain optional later.

No Node build is required. `_headers` (if present) is applied automatically by Pages.

## Contents

| Path | Role |
|------|------|
| `index.html` | Single-page landing |
| `styles.css` | Layout and brand styles |
| `script.js` | Mobile nav + year |
| `assets/` | SVG mark, wordmark, favicon, hero illustration |
| `docs/hosting.md` | Hosting notes (Pages now; optional API later) |

## Brand notes

- Company: LOR Robotics (working brand)
- Product: ChoreBot
- Contact placeholder: `hello@lor-robotics.com` (domain unconfirmed)
- Not affiliated with Chore Robotics (US) or other “Chore” brands
