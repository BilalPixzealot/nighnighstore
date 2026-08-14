# Nigh Nigh — Homepage Redesign Prototypes

Three premium, award-level homepage directions for **Nigh Nigh** (sleepwear & bed linen).
All three share the same content, the same warm light aesthetic, and are built to sit on a **Shopify + custom theme** foundation.

## Open the prototypes

Open **`index.html`** to compare all three, or open any option directly.
Best viewed on desktop — scroll slowly to feel the motion.

For full smooth-scroll / animation, serve the folder locally:

```bash
python -m http.server 8080
# then open http://localhost:8080/index.html
```

## The three options

| File | Name | Direction |
|------|------|-----------|
| `nighnigh-luxe.html` | **Option 1 · The Editorial** | Photography-led, full-bleed imagery, horizontal pinned "Worlds to dream in" gallery, marquee, custom cursor |
| `nighnigh-prototype.html` | **Option 2 · The Cinematic** | Type-behind-subject hero, full-screen statement scenes, floating glass labels, smooth scroll |
| `nighnigh-option3.html` | **Option 3 · The Journey** | Split hero (Infants / Kids / Adults) + one sticky image that scales, tilts, travels and morphs from one age to the next as you scroll |

## Also included

- `nighnigh-homepage.html` — earlier static homepage mockup (real product photography)
- `nighnigh-study.html` — the cinematic-redesign direction study
- `assets/js/` — GSAP, ScrollTrigger, Lenis (theme assets)
- `assets/images/stock/` — Unsplash placeholder photography
- `assets/images/cutouts/` — background-removed subjects (for type-behind-subject / morph)

## Notes

- Imagery is **placeholder** (Unsplash + the current site's photos). The final build uses Nigh Nigh's own photo shoot.
- Motion: Lenis (smooth scroll) + GSAP ScrollTrigger. All prototypes respect `prefers-reduced-motion`.
