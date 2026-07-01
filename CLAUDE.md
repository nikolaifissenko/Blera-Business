# RASNA — Blera Business Site

Single-page static marketing/booking site for RASNA, small-group immersive adventure travel in Blera, Italy.

**Live URL:** https://nikolaifissenko.github.io/rasna/
**Repo:** nikolaifissenko/blera-business (GitHub Pages from `main`)
**File:** `index.html` (~986 lines) — the only file that matters

---

## Standing rules (never re-ask)

- Always commit, push, and send the live link — no confirmation needed
- Formspree endpoint: `https://formspree.io/f/xlgynpjo`
- Contact email: `nikolai.fissenko1@gmail.com`
- Max group size: **9** (furgone 9 posti — 9-seat van)
- Pricing: **no fixed price**. Flow is select activities → contact form → custom quote

---

## Activity catalog (must match BUSINESS_PLAN.md exactly)

**Farm & Field:** Olive Harvest, Tomato & Sauce Day, Grape Harvest, Foraging
**Artisan & Food:** Charcuterie Degustation, Cheese & Charcuterie, Pasta Making
**Culture & Outdoors:** Cammino dei Tre Villaggi, San Giovenale & Panonto, Horseback Riding
**Day Trips:** single card ("Wherever you want")

NO Hazelnut Harvest. NO Renzo/leather arts and crafts.

---

## Design tokens (CSS custom properties)

```
--terra: #B84C2A   --sienna: #7A2E10   --gold: #C9953A
--parch: #E8D8BC   --sand: #D4BFA0     --ink: #1E1008
--earth: #2E1C0C   --smoke: #4A3420    --cream: #F4EDE0
--olive: #5C6B3C   --noir: #14100B
```

## Key design elements

- Section dividers: inline SVG "vase-rim" bands (two thin rules + meander path), 14px tall
- Hero: diamond-chain frieze SVG, `color: var(--terra)`, `opacity: 0.55`
- Catalog section: lozenge grid CSS background (`stroke-opacity: .14`)
- Three-ways section: diamond row ornament, `opacity: 0.45`, 160px wide
- `.fi` class + IntersectionObserver for scroll fade-in

---

## Git / deploy

Local `git push origin main` **always fails HTTP 503**.

**Push workflow:**
1. Use `mcp__github__push_files` (owner: `nikolaifissenko`, repo: `blera-business`, branch: `main`)
2. Then sync local: `git fetch origin main && git reset --hard origin/main`

---

## Commit history (recent)

```
6245e32 Remove fixed pricing — quote based on activities selected
942aad8 Update max group size to 9 (furgone 9 posti)
b58bc7a Increase visibility of Etruscan decorative elements
935e849 Add Etruscan decorative patterns: hero diamond-chain frieze, catalog lozenge background, price card corner brackets, geometric ornament row in three-ways
```
