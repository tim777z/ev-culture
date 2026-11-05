# EV Culture — EV / car-culture decal store

Play **N21** from `data/product-innovation-20261105.md`: original-art vinyl decals via print-on-demand, sold from a static GitHub Pages store.

## Live
- https://tim777z.github.io/ev-culture/ (Pages, main branch / root)

## Products
6 original designs in `assets/` (also used as the product photos):
`EV — Not A Phase`, `Grid Certified`, `I Charge The Future`, `WattsUp!`, `Electric Or Nothing`, `Zero Emissions`.
All artwork generated programmatically in-session (Pillow) — original, no trademarked marks.

## Pricing / margin (per N21 plan)
- Single sticker: $12 · bundle 3 for $30 → target AOV ~$30–45
- Fulfilment: made-to-order print-on-demand (Printify/Printful/SVG Stickers) — target print cost ≤ $5–6 → ≥40% margin
- AOV $45 at 42% margin → modeled ~$2,700 gross / 90 days

## Order flow (launch rail)
1. Customer clicks "Order this" → email with product, qty, shipping address.
2. Agent sends PayPal invoice (timlangeveldt@gmail.com) within 24h.
3. On payment → order POD → ship → log order in `data/storefront/` ledger.

Payment rail: PayPal invoice only at launch (operator-approved). No card details anywhere. Stripe Payment Links deferred until the card is re-supplied in-session.

## Upgrade path
- Etsy shop for discovery (same designs) → monthly digest of bestsellers feeds the design cycle.
- Car-culture subreddit/meetup organic posts (disclose affiliation, never spam).

## Compliance
- Original artwork only; no OEM marks ("EV", "watts" are generic).
- POD print quality check on the first physical sample before any ad spend.
- Returns: peer-to-peer, POD reprint on any defective unit.
