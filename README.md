# LOR Robotics — marketing site

Static brochure site for **LOR Robotics** (working name). No framework, no build step.
Hosted on [Cloudflare Pages](https://pages.cloudflare.com/), deployed from `main`.

## Live

- https://chorebot-web.pages.dev (custom domain later, once the name and domain are settled)

## What the site says

- One shared core (drive and power, navigation, safety, skills, fleet app) under many single-job robots.
- First robot: a mobile smart bin for parks, campuses, estates and events.
- Status: simulation today; first physical prototype this autumn in Gulbene, Latvia.
- Call to action: register pilot interest.

Keep public copy plain. No internal gate codes, test IDs or claim-ladder language, and no
unreleased video. The product has no public name yet, so the site uses **LOR Robotics** only.
Direction and wording rules live in `chorebot-docs/PLAN.md`.

## Contents

| Path | Role |
|------|------|
| `index.html` | Landing: first robot, platform, pilots, contact |
| `investors.html` | Short investor overview |
| `styles.css` | Forest green and cream styles |
| `script.js` | Mobile nav and footer year |
| `assets/` | Logo mark, wordmark, favicon, `hero-bin.svg` illustration |
| `docs/hosting.md` | Hosting notes |

## Local preview

```bash
python3 -m http.server 8080
```

## Open item

`hello@lor-robotics.com` does not work yet: the domain is not registered. Register it (or
pick another address) and update both pages.
