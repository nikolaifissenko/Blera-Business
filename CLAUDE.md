# Rasna — Project Context for Claude

## What this is
Rasna is a small-group immersive travel experience business based in Blera (northern Lazio, Italy). International travelers come for 4 days/3 nights to participate in real local life — harvests, artisan workshops, hikes, meals with families. Not a tour company — a "live like a local" experience.

## Key people
- **Nikolai** — co-founder, handles international marketing/sales/guest experience/logistics
- **Maria Grazia** — co-founder, local relationships, on-the-ground operations, community credibility
- **Cristina Damiani** — potential manager/coordinator role (to be defined with Maria Grazia)
- **Nicolò Lenarda** — partner/board member, multiple assets (olive oil, horses, donkeys, panonto at San Giovenale)

## Confirmed local partners
- **Davide Paolocci** (Civitella Cesi) — cheese + cured meat tasting, hands-on production, nearby archaeological site. Tel: +39 327 752 2499
- **Renzo** — leather bag-making workshop. High availability, potentially free (guests buy his goods)
- **Emiliano** (Miriam's son) — cured meats/affettati. Interest and year-round availability still TBD
- **Totò** — house rental + gnocchi + olives. TBD

## The landing page
- **Live at:** GitHub Pages (was `nikolaifissenko.github.io/Blera-Business/`, may be renamed to `/Rasna/`)
- **Source:** `index.html` on the `main` branch
- **Features:** Activity selection cards, inquiry form via Formspree, auto-detected i18n (EN, IT, DE, FR, ES, NL)
- **Form endpoint:** `https://formspree.io/f/xlgynpjo`

## Repo structure
- `index.html` — the landing page (single-file, no build step)
- `BUSINESS_PLAN.md` — full business plan with phased rollout
- `FINANCIAL_PLAN.md` — pricing, costs, margins, revenue projections
- `RASNA_PITCH_IT.md` — Italian pitch document for local partners
- `CONTATTI_LOCALI.md` — local contact list with status tracking
- `PROJECT_STATUS.md` — current project status and what's done/pending

## Key business numbers
- Price: €1,400/guest all-inclusive (4 days/3 nights)
- Cost: ~€720/guest → ~€680 margin
- Groups of 6-10 (target 8)
- Deliberate cap: ~15-20 groups/year at maturity
- Year 1 target: pilot + 3-4 paying groups (~€22k profit)

## Important design decisions
- Day trips are presented as a single "Day Trip" card — destination decided together with guests, not pre-listed
- Activities are categorized: Farm & Field, Artisan & Food, Culture & Outdoors, Day Trips
- The business deliberately stays small to protect Blera's authenticity
- "Cooking in the tradition of the nonne" framing (not promising a specific grandmother)
