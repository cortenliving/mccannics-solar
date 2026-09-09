# Mc Cannics Solar

Static homepage for Mc Cannics Solar. No build step.

## Deploy (Cloudflare Pages)

- **Production branch:** `main`
- **Build command:** none (leave blank)
- **Output directory:** `/` (or leave blank / use `/`)

Connect the repo in Cloudflare Pages and deploy from `main`. Static files are served as-is.

## Open locally

Open `index.html` in a browser (double-click, or any static file server).

Tailwind and the Google fonts load from the network. If they fail, the page still uses the system font stack and the layout classes that already resolved. Estimator, tabs, FAQ, and the quote wizard run from `app.js` on this page only — nothing is sent to a server.

## Component hierarchy

- Promo bar — green loans / Q Card, link to `#finance`
- Header (sticky) — wordmark, primary nav, Get a quote, hamburger, quiet trust row
- Hero — copy + estimator card (bill slider, battery toggle, live saving and size)
- Numbered differentiators 01–04
- Comparison — retailer / home solar / solar + battery (cards below `lg`, table from `lg`)
- Impact stats — 1981, East Coast first, written quote
- Solutions `#solutions` — Home / Lifestyle block / Farm / Small commercial tabs
  - Batteries `#batteries`
  - `#commercial` opens the Small commercial tab and scrolls here
- Size guide
- Equipment band
- Projects `#projects` — example briefs, not case studies
- How it works — four steps
- Finance `#finance`
- FAQ — one panel open at a time
- Quote wizard `#quote` — four local steps, then a confirmation
- About `#about`
- Footer — address, phone, anchors, disclaimer
