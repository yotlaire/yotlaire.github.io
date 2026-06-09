# Boukay Vital — Website Project Briefing

## What this project is
The website for **Boukay Vital**, a pre-launch premium wellness supplement brand.
The site is a bilingual (English/Polish) waitlist landing page.
One single file: `index.html`

## Founders
- **Yotlaire Guillou** — based in New York
- **Emmanuel Cherestal** — based in Poland
- Both Haitian-born. Brand draws on Caribbean botanical heritage.
- Founder story: parents lost to preventable disease — this is the emotional core of the brand.

## The Products
**TANBOU AM** — Morning Vitality
- Ingredients: Moringa, Guava Leaf, Panax Ginseng, Schisandra, Acerola, L-Theanine, Turmeric, Black Seed, Zinc, Selenium, B vitamins
- Targets: Energy, Focus, Immunity

**ZANTRAY PM** — Evening Rest & Renewal
- Ingredients: Chamomile, Lemon Balm, Passionflower, Tamarind, Soursop Leaf, Lemongrass, Magnolia Bark, Jujube Seed, Magnesium Glycinate, D3+K2
- Targets: Sleep, Recovery, Renewal

**Pricing:** 349 PLN/bundle | 299 PLN/month subscription

## Brand Colors & Fonts
- Forest green: #0e2318
- Gold: #c9a84c
- Cream: #f5f0e8
- Display font: Cormorant Garamond
- Body font: Jost

## Tech Stack
- Pure HTML/CSS/JS — single file, no framework
- Hosted on GitHub Pages (free)
- Repo: https://github.com/yotlaire/yotlaire.github.io
- Live domain: https://bookayvital.com
- DNS managed by Cloudflare (free)
- Email form: Formspree — https://formspree.io/f/mzdqgoal

## How to deploy changes
After editing index.html, run:
```
git add index.html
git commit -m "describe your change here"
git push
```
Site updates automatically within 30–60 seconds.

## Current site sections (in order)
1. Language toggle bar (EN/PL switch)
2. Hero — split AM/PM with waitlist form
3. Story — founder narrative
4. Products — TANBOU AM + ZANTRAY PM detail cards
5. How it works — 3 steps
6. Waitlist — second signup form
7. Legal disclaimer (EU compliant)
8. Footer

## Important rules for all copy changes
- NEVER use disease treatment language: "cures", "treats", "prevents"
- ALWAYS use EFSA-safe language: "supports", "contributes to", "helps maintain"
- All health claims must have the footnote: "This statement has not been evaluated by EFSA"
- Position as pre-launch brand validating demand — never as finished product
- Never claim military endorsement or affiliation

## Language
- Every piece of text exists in both English (.en class) and Polish (.pl class)
- Language toggle works via body class: lang-en or lang-pl
- When adding new text always add BOTH the .en and .pl versions

## Contact
- hello@bookayvital.com
