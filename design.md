# CONCEPTRA AI design system

Inspired by a dark, editorial studio site: night-black canvas, off-white type, one loud acid-yellow accent, full-bleed alternating bands, a black/white stripe divider, thin hairlines and wide margins.

## Colour (packages/web/src/web/styles/theme.css)
- `--ink-900 #161616` page background · `--ink-800 #1e1e1d` surfaces · `--ink-700 #2a2a28` inputs
- `--paper #ecece6` text and light bands · `--paper-dim #a3a39e` secondary
- `--acid #e2cd0c` the only accent: CTAs, stage numbers, yellow bands, active nav
- Hairlines: `rgba(236,236,230,.14)` on dark, `rgba(22,22,22,.2)` on light

## Type
- Display: Archivo, condensed (font-stretch 70-85%), weight 800-900, uppercase, line-height .9
- Body: Familjen Grotesk 400-600
- Labels: IBM Plex Mono, 0.78rem, uppercase, 0.08em tracking

## Layout
- Max width 1440px, gutter clamp(1.1rem, 4vw, 3.5rem), band padding clamp(4rem, 9vw, 8.5rem)
- Sections are full-width bands alternating dark / paper / acid
- Stage rows alternate image left/right; square corners everywhere except chips
- Film grain overlay on body; faint star field in the hero

## Motion
- One staggered page-load reveal (`.rise` + `--d`), hover lifts on collage, scanning bar while generating
