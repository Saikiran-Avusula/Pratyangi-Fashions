# Pratyangi Fashions — Shared Design System

Status: Visual direction documented from the supplied homepage PDF/prototype reference. Exact Figma token values still require inspection in the editable Figma design file; do not treat inferred colors as exact HEX values.

## Brand direction visible in the supplied reference
- Traditional, premium Indian silk-saree storefront.
- Warm light/cream surfaces paired with deep maroon/burgundy areas.
- Gold/warm metallic accents used sparingly.
- Editorial serif-style display headings paired with readable supporting text (verify exact font family in Figma).
- Large fashion imagery, clean product grids/carousels, restrained borders and generous whitespace.

## Design tokens — verify against Figma before locking

| Token | Value | Status |
|---|---|---|
| `--color-primary` | `TBD_FROM_FIGMA` | Not verified |
| `--color-secondary` | `TBD_FROM_FIGMA` | Not verified |
| `--color-accent` | `TBD_FROM_FIGMA` | Not verified |
| `--color-background` | `TBD_FROM_FIGMA` | Not verified |
| `--color-surface` | `TBD_FROM_FIGMA` | Not verified |
| `--color-text` | `TBD_FROM_FIGMA` | Not verified |
| `--color-muted` | `TBD_FROM_FIGMA` | Not verified |
| `--color-border` | `TBD_FROM_FIGMA` | Not verified |
| `--font-display` | `TBD_FROM_FIGMA` | Not verified |
| `--font-body` | `TBD_FROM_FIGMA` | Not verified |
| `--radius-card` | `TBD_FROM_FIGMA` | Not verified |
| `--radius-button` | `TBD_FROM_FIGMA` | Not verified |
| `--container-max` | `TBD_FROM_FIGMA` | Not verified |

## Shared rules for all developers and AI agents
1. Do not introduce new brand colors or fonts without team approval.
2. Define final tokens once as CSS variables in `app/globals.css`.
3. Use CSS Modules for component-specific styling; do not scatter duplicate token values across components.
4. Reuse shared Button, Container, SectionHeading, ProductCard, and Carousel components.
5. Match the same tokens across desktop, tablet, and mobile.
6. If a value is not documented, mark it as `TBD_FROM_FIGMA` and ask for confirmation instead of guessing.
7. After the Figma values are verified, update this document and implement those values in CSS variables in one commit.

## Typography scale — confirm sizes/weights in Figma
- Display / Hero heading: `TBD_FROM_FIGMA`
- Section heading: `TBD_FROM_FIGMA`
- Product title: `TBD_FROM_FIGMA`
- Body: `TBD_FROM_FIGMA`
- Caption / metadata: `TBD_FROM_FIGMA`
- Button label: `TBD_FROM_FIGMA`

## Spacing and layout — confirm in Figma
- Base spacing unit: `TBD_FROM_FIGMA`
- Content max width: `TBD_FROM_FIGMA`
- Section vertical spacing: `TBD_FROM_FIGMA`
- Product grid gaps: `TBD_FROM_FIGMA`
- Header height: `TBD_FROM_FIGMA`
- Breakpoints: use existing project breakpoints unless the Figma design specifies otherwise; document the final values here.

## Component styling checklist
- Header/navigation: backgrounds, text, active/hover states, spacing.
- Hero: image composition, V-shaped visual arrangement, typography, CTA, animation states.
- Category cards: image ratio, label placement, hover behavior.
- Product cards: image ratio, wishlist, quick view, add-to-cart, price/sale treatment.
- Reviews, AI Try-On, access tiers, offers, social, benefits, newsletter, footer: shared typography, surfaces, buttons, spacing.

## Source priority
1. Editable Figma design values and frames
2. Figma prototype interaction behavior
3. Supplied prototype recording
4. Supplied PDF screenshots for visual cross-check

Do not claim exact values were extracted until they have been verified in Figma Inspect/Dev Mode or the design variables panel.
