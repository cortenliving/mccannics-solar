# McCannics Solar — brand tokens

Aligned to the live McCannics Shopify theme at mccannics.co.nz.

| Role | Hex | Notes |
|------|-----|--------|
| Charcoal / dark surfaces | `#1F1F21` | Promo bar, sticky header, hero band, impact stats, footer |
| Charcoal contrast | `#2B2B2E` | Hover / secondary dark |
| Primary CTA | `#F10808` | Buttons; label `#FFFFFF` for contrast on red |
| Accent (cyan) | `#00FCED` | Links, focus rings, numerals, trust chips, progress, card accents |
| Paper / white | `#FFFFFF` | Cards, light panels |
| Soft grey | `#F5F5F5` | Light section backgrounds |
| Borders | `#E5E5E7` | Card / divider borders |
| Body ink | `#1F1F21` | Default text |
| Muted text | `#6B6B70` | Secondary copy |

## Logo

- Header / footer: local `logo-mccannics.png` (white McCannics wordmark + red C/wrench mark) on charcoal, with cyan **Solar** label beside it.
- Favicon: `favicon.png`
- `theme-color`: `#1F1F21`

## Pages assets

Local files `logo-mccannics.png` and `favicon.png` remain in the workspace. GitHub MCP cannot push binary PNGs as text, so `index.html` embeds optimized PNG **data-URIs** for the header/footer logo and favicon so GitHub Pages renders without separate image commits.
