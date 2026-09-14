---
name: Saffron & Shadow
colors:
  surface: '#151312'
  surface-dim: '#151312'
  surface-bright: '#3c3837'
  surface-container-lowest: '#100e0d'
  surface-container-low: '#1d1b1a'
  surface-container: '#221f1e'
  surface-container-high: '#2c2928'
  surface-container-highest: '#373433'
  on-surface: '#e8e1df'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e8e1df'
  inverse-on-surface: '#33302e'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#ecbf84'
  on-secondary: '#452b00'
  secondary-container: '#624313'
  on-secondary-container: '#ddb177'
  tertiary: '#ffc197'
  on-tertiary: '#4c2709'
  tertiary-container: '#e1a67e'
  on-tertiary-container: '#643b1b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#ecbf84'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#5f4111'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#f7ba90'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#663d1d'
  background: '#151312'
  on-background: '#e8e1df'
  surface-variant: '#373433'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 76px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 44px
    fontWeight: '400'
    lineHeight: 54px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '400'
    lineHeight: 38px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '300'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '300'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.2em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-mobile: 1.5rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.5rem
  space-lg: 2.5rem
  space-xl: 4.5rem
---

## Brand & Style

This design system embodies the sensory opulence, ritual, and modern architectural precision of contemporary Indian haute cuisine. It departs completely from cliché ethnic ornament, choosing instead a cinematic, editorial visual language that treats culinary tradition as high art.

The visual ethos blends **Minimalism** with atmospheric **Tactile Depth** and delicate **Glassmorphism**:
- Generous, deliberate negative space mirroring quiet, dimly lit private dining salons.
- A profound nocturnal palette that highlights food photography and typography like spotlighting artifacts in an intimate gallery.
- Filigree-fine metallic accents that imply hand-chiseled brass, hammered copper, and gold leaf without overwhelming structural clarity.
- Sensual, slow micro-interactions and whisper-soft lighting gradients that evoke flickering warm ambient candlelight against dark slate and charcoal plaster.

## Colors

The color palette is strictly keyed around nocturnal warmth and noble culinary metals:

- **Canvas & Surface Grounds**:
  - Base Background: Deep charcoal soot (`#0C0A09`), providing boundless depth.
  - Surface Elevation 1: Smoky basalt (`#141210`), used for structural containers and backdrop overlays.
  - Surface Elevation 2: Warm stone ash (`#1D1916`), for active cards, drawers, and modal sheets.
  - Border & Filigree Tint: 12% to 24% opacity spun gold (`rgba(212, 175, 55, 0.16)`).

- **Typography & Content**:
  - Primary Content: Warm ivory (`#F5F0EB`), softened to avoid harsh digital contrast.
  - Secondary Content: Aged parchment (`#E8DFD5`), used for body copy and supporting descriptions.
  - Tertiary Content: Muted ash cream (`#9C948B`), reserved for metadata, timestamps, and dietary tags.

- **Noble Accents**:
  - Spun Gold (`#D4AF37`): Primary interactions, active states, tasting course milestones, and insignia badges.
  - Muted Raw Copper (`#C59B63`): Secondary actions, hover accents, and refined divider rules.
  - Scorched Saffron / Terra (`#A3704C`): Tertiary warmth, subtle indicators, and background radial aura blurs.

## Typography

The typographic system creates tension between the lyrical, historical flourishes of Playfair Display and the cool, geometric restraint of Plus Jakarta Sans.

- **Headings & Display**: Set in Playfair Display. Maintain normal or medium weights; avoid heavy, commercial bold treatments. For tasting menus and hero headlines, italics may be applied selectively to spice names, regional provenance, or single poetic words.
- **Editorial Sub-headings and Meta**: Set with `label-caps` in uppercase with generous tracking (`0.2em`) to evoke luxury atelier engraving.
- **Body & Prose**: Rendered in Plus Jakarta Sans at light (`300`) and regular (`400`) weights. High line-height ratios preserve breathability against dark backgrounds, preventing eye strain.

## Layout & Spacing

The layout is built around an airy, asymmetrical 12-column grid that permits wide gutters and generous margins reminiscent of an art monograph:

- **Desktop (1200px+)**: 12 columns, 64px margins, 24px gutters. Editorial layouts offset dishes and narrative pairings into staggered 5-column / 7-column configurations. Max content width is capped at 1440px for intimate scale.
- **Tablet (768px - 1199px)**: 8 columns, 32px margins, 20px gutters. Dish listings collapse into structured 4-column pairing units.
- **Mobile (< 768px)**: 4 columns, 24px outer margins, 16px gutters. Structural lines remain continuous, relying on vertical rhythm rather than boxed density.

Vertical flow relies on vast section gaps (`space-xl` and higher) to pace the user's attention, treating each section (e.g., The Cellar, The Chef's Tasting, Reservations) as an autonomous chapter.

## Elevation & Depth

Rather than relying on drop shadows, depth is achieved through translucent dark tiers, luminous amber halation, and hairline gold boundaries:

- **Layering & Blurs**: Base elevation starts at `#0C0A09`. Elevated cards and sticky reservation rails use translucent dark glass (`rgba(20, 18, 16, 0.72)`) backed by heavy backdrop blurs (`backdrop-filter: blur(20px)`).
- **Filigree Boundaries**: Low-contrast, razor-thin borders (`1px solid rgba(212, 175, 55, 0.14)`) trace cards, separators, and sticky headers. Hover states transition this hairline boundary to raw copper (`rgba(197, 155, 99, 0.45)`).
- **Ambient Candlelight Shadows**: High-elevation surfaces (e.g., booking modals, sommelier notes) cast ultra-diffused, warm-tinted shadows: `0 24px 48px -12px rgba(0, 0, 0, 0.75), 0 0 40px 2px rgba(212, 175, 55, 0.04)`.
- **Specular Glow**: Interactive focal points feature an imperceptible radial gradient background wash of scorched amber (`rgba(163, 112, 76, 0.12)` fading to transparent over 300px).

## Shapes

The shape system adopts a refined, nearly architectural discipline (`roundedness: 1`). Edges are gently softened just enough to remove digital harshness while retaining crisp structural authority.

- Default interactive containers and cards use subtle `4px` (`0.25rem`) corners.
- Hero media vessels, food imagery apertures, and tasting flight accordions adopt `8px` (`0.5rem`) outer radii to complement plate geometries.
- Fully rounded pills are strictly forbidden except for miniature status dots or sommelier vintage tags. Form follows the precision of modern stone, brass, and teak joinery.

## Components

### Buttons & CTAs
- **Primary Action (Reservations, Concierge Inquiry)**: A solid spun gold surface (`#D4AF37`) with dark charcoal text (`#0C0A09`), styled with `label-caps` typography. Upon hover, shifts to raw copper (`#C59B63`) accompanied by a gentle gold edge glow.
- **Secondary Action (Wine Pairing Details, Story Archive)**: Transparent ground with a 1px border in `rgba(212, 175, 55, 0.35)` and warm ivory text (`#F5F0EB`). Hover fills the background with `rgba(212, 175, 55, 0.08)`.
- **Text Link**: `body-sm` in `#E8DFD5` underlined with a continuous 1px metallic gold filigree rule spaced 6px beneath the baseline.

### Menu Cards & Tasting Items
- Cards rest on `#141210` at 70% opacity with a `1px` border of `rgba(212, 175, 55, 0.12)`.
- Dish title appears in `headline-sm` (`#F5F0EB`), accompanied by an inline right-aligned price or pairing note in `title-md` (`#D4AF37`).
- Botanical and spice profiles are rendered in `body-sm` (`#9C948B`), separated by subtle centered gold dots (`•`).

### Selection Controls & Inputs
- **Text Inputs (Guest Name, Dates, Requests)**: Borderless on sides and top; anchored by a single bottom stroke of `1px solid rgba(232, 223, 213, 0.2)`. Focus state elevates the bottom border to `#D4AF37` with a subtle vertical text shift. Background is completely transparent.
- **Checkboxes & Radios**: Custom square selectors (`16px`) with 2px radius and a 1px border of `#C59B63`. Checked state fills with `#141210` displaying an inner miniature brass diamond.

### Chips & Dietary Badges
- Compact badges (e.g., *Sattvic*, *Coastal Karavali*, *Single-Origin Saffron*) rendered in `label-caps`. 
- Outlined in `rgba(197, 155, 99, 0.25)`, filled with `rgba(29, 25, 22, 0.6)`, and text set in `#E8DFD5`.

### Bespoke Elements
- **Gold Filigree Dividers**: Used between degustation courses; a hairline horizontal rule fading from transparent to `#D4AF37` (at 40% opacity) in the center, punctuated by a delicate 4px gold diamond glyph.
- **Floating Reservation Dock**: A fixed-bottom mobile/tablet glass bar (`rgba(12, 10, 9, 0.85)` with `backdrop-filter: blur(16px)`) trimmed with a top gold filigree line, keeping the booking path effortless.