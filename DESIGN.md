---
name: Seoul Minimalist Luxury
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4b4640'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#7d766f'
  outline-variant: '#cec5bd'
  surface-tint: '#615e5b'
  primary: '#040302'
  on-primary: '#ffffff'
  primary-container: '#1f1d1b'
  on-primary-container: '#898481'
  inverse-primary: '#cbc5c2'
  secondary: '#7b5643'
  on-secondary: '#ffffff'
  secondary-container: '#fecdb5'
  on-secondary-container: '#7a5542'
  tertiary: '#000400'
  on-tertiary: '#ffffff'
  tertiary-container: '#142012'
  on-tertiary-container: '#7b8975'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7e1de'
  primary-fixed-dim: '#cbc5c2'
  on-primary-fixed: '#1d1b19'
  on-primary-fixed-variant: '#494644'
  secondary-fixed: '#ffdbcb'
  secondary-fixed-dim: '#ecbca5'
  on-secondary-fixed: '#2e1507'
  on-secondary-fixed-variant: '#603f2e'
  tertiary-fixed: '#d8e7d0'
  tertiary-fixed-dim: '#bccbb5'
  on-tertiary-fixed: '#121f10'
  on-tertiary-fixed-variant: '#3d4a39'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
  surface-cashmere: '#F2EBE4'
  surface-pure: '#FFFFFF'
  border-delicate: '#E6DDD4'
  text-muted: '#6E6760'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '300'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.12em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-lg: 2.5rem
  margin: 1.25rem
  margin-md: 3rem
  margin-lg: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system expresses a refined, architectural Seoul minimalist aesthetic tailored for high-end boutique personal care. The identity balances traditional Korean aesthetic values—simplicity, organic restraint, and intentional emptiness (*yeobaek-ui mi*, the beauty of white space)—with modern Northern California luxury.

The visual tone is calm, bespoke, and discerning. It eschews loud salon tropes in favor of an editorial art-book layout style: airy negative space, immaculate typographic hierarchies, delicate linear separators, and tactile warmth. The emotional response is centered on quiet confidence, sanctuary, and prestige artistry.

## Colors

The palette is rooted in tactile organic materials: unbleached hanji paper, raw ceramics, warm travertine, and dark roasted espresso.

- **Primary (`#1F1D1B`):** Deep Espresso / Charcoal. Used for key headlines, primary actions, and anchor graphic elements where high visual gravity is required.
- **Secondary (`#B58A75`):** Muted Terracotta. Represents earth, warmth, and artisanal touch. Applied to delicate focal moments, highlights, price numerals, and secondary interactive states.
- **Tertiary (`#94A38E`):** Muted Sage. Evokes botanical treatments, scalp health, and tranquil wellness. Used for subtle status tags, boutique badges, and botanical product callouts.
- **Neutral (`#FAF8F5`):** Warm Alabaster canvas. Replaces sterile digital white with a soft, natural ambient background.
- **Named Colors:**
  - `surface-cashmere` (`#F2EBE4`): Enveloping secondary surface for service categories, inset modules, and elevated containers.
  - `surface-pure` (`#FFFFFF`): Reserved exclusively for floating service cards, image containers, and floating booking modules.
  - `border-delicate` (`#E6DDD4`): Extremely light hairline rules that define boundaries without introducing visual weight.
  - `text-muted` (`#6E6760`): Medium-contrast neutral for secondary descriptions, timing labels, and caption metadata.

## Typography

The typography pairs the editorial elegance of Playfair Display with the clean precision of Inter. 

- **Display & Headlines:** Set in Playfair Display. Used with generous vertical spacing and delicate tracking. Large headers should preserve an editorial magazine aesthetic, utilizing italic styling sparingly for accents or Korean service romanizations.
- **Body & Captions:** Set in Inter with light weights (`300` and `400`). Generous line heights are required to sustain readability and maintain an unhurried, breathing layout.
- **Labels & Microcopy:** Rendered in uppercase Inter with wide letter spacing (`0.1em` to `0.12em`) to ground architectural metadata, category tags, and timestamps.

## Layout & Spacing

The layout operates on a 12-column responsive grid with expansive vertical margins that establish breathing room around imagery and editorial copy.

- **Breakpoints:**
  - Mobile (`< 768px`): 4 columns, `margin: 1.25rem`, `gutter: 1rem`.
  - Tablet (`768px - 1024px`): 8 columns, `margin-md: 3rem`, `gutter: 1.5rem`.
  - Desktop (`> 1024px`): 12 columns, max-width `1280px`, `margin-lg: 5rem`, `gutter-lg: 2.5rem`.

Vertical flow relies on asymmetrical pairing: large editorial full-bleed imagery juxtaposed with deeply indented text columns, allowing the eye to rest. Dense stacking is prohibited; each section must feel like a dedicated gallery space.

## Elevation & Depth

This design system avoids high-contrast drop shadows and artificial skeuomorphism. Depth is achieved purely through **tonal layering** and **whisper-soft ambient diffusion**.

- **Canvas Tier:** Ground level is the natural unvarnished Warm Alabaster (`#FAF8F5`).
- **Surface Inset:** Secondary sections (such as service menus and treatment overviews) sit within Soft Cashmere (`#F2EBE4`) blocks without borders or drop shadows.
- **Card Tier:** Interactive units and boutique product displays use Pure White (`#FFFFFF`) with a hairline border of `1px solid #E6DDD4` and an ambient shadow: `0 4px 20px -2px rgba(31, 29, 27, 0.04)`.
- **Floating Modals & Sticky Booking:** Raised elements (sticky mobile booking bar, booking modal overlays) carry a deeper, diffused shadow: `0 16px 36px -4px rgba(31, 29, 27, 0.08)` paired with an ultra-subtle backdrop blur (`backdrop-filter: blur(8px)`) over translucent backing.

## Shapes

The shape vocabulary uses subtle, soft architectural corners (`0.25rem` base, with selected card contours at `0.5rem`). This restraint reflects the crisp, linear geometry of modern Korean interior design, avoiding overly playful or bubble-like roundness.

Pill shapes are strictly reserved for boutique badges, micro-tags, and category pills to contrast against the structured rectilinearity of editorial image cards.

## Components

### Buttons
- **Primary:** Deep Espresso (`#1F1D1B`) background, Pure White text, uppercase `label-md` tracking, `0.25rem` corner radius, `1rem 2rem` padding. Subtle hover shifts toward `#35322F` with a soft lift.
- **Secondary / Ghost:** Transparent background, `1px solid #1F1D1B`, Deep Espresso text. Hover fills with Soft Cashmere (`#F2EBE4`).
- **Accent Booking Action:** Muted Terracotta (`#B58A75`) fill, Pure White text, reserved for direct conversion points ("Reserve Appointment").

### Boutique Badges & Category Tabs
- **Badges:** Pill-shaped (`rounded-full`), padded `0.25rem 0.75rem`. Muted Sage (`#94A38E`) background at 15% opacity with solid Sage text, or Cashmere background with Charcoal text.
- **Tabs:** Horizontal inline scroll on mobile, anchored row on desktop. Active tab marked by an architectural underline (`1.5px solid #1F1D1B`) with no background pill, keeping the baseline feather-light.

### Service Pricing Cards
- Background: `#FFFFFF`. Hairline border: `#E6DDD4`.
- Padding: `2rem`.
- Layout: Asymmetrical title block, Korean technique descriptor in muted typography, price highlighted in Muted Terracotta using `Playfair Display`, followed by duration indicator and bulleted consultation notes.

### Review Cards (5-Star Google Experience)
- Surface: `#FAF8F5` set inside `#F2EBE4` container.
- Details: Five micro star glyphs in `#B58A75`, reviewer name in `title-lg`, verification badge ("Google Review"), body text in `body-md` italic.

### Instagram Lookbook Grid
- Clean, tight gutters (`0.75rem`).
- Strict aspect ratios: `4:5` portrait crops.
- Overlay: On hover/focus, an ultra-thin veil of Deep Espresso at 30% opacity surfaces service details (e.g., "Magic Straight Perm & Layered Cut") in white serif typography.

### Location & Studio Details
- Two-column asymmetric layout: Architectural studio photography on the left, address, parking advisory, and Walnut Creek transit information on the right.
- Map CTA: Minimalist outlined interactive button with directional icon.

### Sticky Mobile Booking Bar
- Pinned to the bottom viewport on devices `< 768px`.
- Pure White semi-translucent surface with `backdrop-filter: blur(12px)` and top border `1px solid #E6DDD4`.
- Contains studio status/next available date on the left and a compact Terracotta "Book Now" CTA on the right.