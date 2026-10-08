---
name: Washi & Stone
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#44474a'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ec'
  outline: '#75777a'
  outline-variant: '#c5c6ca'
  surface-tint: '#5d5e61'
  primary: '#1a1c1e'
  on-primary: '#ffffff'
  primary-container: '#2f3133'
  on-primary-container: '#98999b'
  inverse-primary: '#c6c6c9'
  secondary: '#526442'
  on-secondary: '#ffffff'
  secondary-container: '#d2e6bc'
  on-secondary-container: '#576846'
  tertiary: '#041f2a'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c3440'
  on-tertiary-container: '#849cab'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e5'
  primary-fixed-dim: '#c6c6c9'
  on-primary-fixed: '#1a1c1e'
  on-primary-fixed-variant: '#454749'
  secondary-fixed: '#d5e9bf'
  secondary-fixed-dim: '#b9cda4'
  on-secondary-fixed: '#111f05'
  on-secondary-fixed-variant: '#3b4c2c'
  tertiary-fixed: '#cde6f6'
  tertiary-fixed-dim: '#b1cad9'
  on-tertiary-fixed: '#031e2a'
  on-tertiary-fixed-variant: '#324a57'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 68px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system embodies the Japanese concept of *Ma* (negative space, pause, interval) fused with functional modern minimalism. Drawing inspiration from MUJI's honest utility, Aesop's literary precision, Apple’s structural restraint, and traditional architectural elements like shoji screens, tatami geometry, and washi paper, the aesthetic is quiet, tactile, and deliberate.

The experience evokes calm, mental clarity, and permanence. The UI acts as a serene background canvas rather than a vocal centerpiece—letting content breathe within expansive, unhurried negative space. Visual noise, aggressive prompts, saturated gradients, and synthetic gloss are strictly rejected in favor of organic warm neutrals, subtle line-work, and unadorned surfaces.

## Colors

The palette is derived from natural, unbleached materials, architectural stone, mineral pigment, and plant dyes. 

- **Canvas & Background (`#F8F6F2` - Warm Ivory):** The foundational ambient backdrop, reminiscent of fibrous handmade paper. Never use pure `#FFFFFF` as a base canvas.
- **Surfaces (`#FCFBF8` - Paper White):** Elevated planes, floating sheets, and interaction panels. Provides delicate luminous separation against Warm Ivory.
- **Surface Containers (`#E8E6E3` - Mist Grey):** Recessed wells, code blocks, quiet badges, and structural groupings.
- **Dividers & Strokes (`#D6D2CC` - Soft Stone):** Used for hair-thin, architectural gridlines echoing shoji framing.
- **Text & Core Contrast (`#2F3133` - Warm Charcoal):** The primary ink color. Deep yet softened with warm undertones; never stark pure black.
- **Muted Text (`#686966` - Muted Charcoal):** Secondary metadata, captions, and de-emphasized actions.
- **Accents:** 
  - **Sage / Muted Matcha (`#9CAF88`):** Organic primary action markers, selected states, and calm success indicators.
  - **Dusty Blue (`#9EB7C6`):** Secondary informative cues and quiet focus rings.
  - **Slate Indigo (`#6C7A89`):** Precise metadata, active tab underlines, and structural icons.

## Typography

The typographic system creates an editorial counterpoint between the contemplative literary presence of `Newsreader` (optical size 72, upright, balanced ascenders) and the precise, mechanical clarity of `Geist`.

- **Headlines & Editorial Focus:** Large titles and reflective statements utilize `Newsreader` with standard or medium weights. Never set Newsreader in bold weights or all-caps.
- **Body & Functional Hierarchy:** Dense information, interface labels, interactive elements, and navigation rely on `Geist`. 
- **Leading & Rhythm:** Generous line heights are enforced across body copy to invite unhurried reading and sustain calm breathing space.
- **Letter Spacing:** Headlines utilize optical tightening (`-0.01em` to `-0.02em`), while small UI labels and metadata leverage deliberate tracking (`+0.04em` to `+0.06em`) for effortless scannability.

## Layout & Spacing

Layouts follow an asymmetric, quiet grid inspired by tatami mats and editorial broadsheets. The canvas does not crowd density; spatial pause takes precedence over rapid visual density.

- **Grid Structure:** A 12-column fluid grid on desktop (max width 1280px) with expansive `margin` (3rem) and `gutter` (1.5rem). Collapses to an 8-column layout on tablet and a single-column or 4-column framework on mobile with `1.25rem` outer margins.
- **Horizontal Framing:** Boundaries and content sections prefer generous vertical margins (`space-2xl` and `space-3xl`) over heavy dividing boxes.
- **Component Padding:** Elements favor airy interior whitespace: cards and panels use `space-lg` to `space-xl` internally to maintain an uncluttered presence.

## Elevation & Depth

Depth is tactile and architectural rather than synthetic or floating.

- **Tonal Layering:** The primary mechanism for elevation is tonal stacking: `Warm Ivory (#F8F6F2)` serves as the grounding plane, `Paper White (#FCFBF8)` forms foreground surfaces, and `Mist Grey (#E8E6E3)` hosts recessed states.
- **Hairline Outlines:** Instead of heavy shadows, floating cards and popovers rely on 1px borders using `Soft Stone (#D6D2CC)`.
- **Atmospheric Shadows:** When structural separation is mandatory (e.g., sticky headers, modals, floating menus), use exceptionally soft, diffused, warm-tinted ambient shadows with zero harsh edge:
  - Low elevation: `0 2px 8px rgba(47, 49, 51, 0.03)`
  - High elevation (dropdowns, dialogs): `0 12px 32px rgba(47, 49, 51, 0.06), 0 2px 6px rgba(47, 49, 51, 0.02)`
- No glows, colored drop shadows, or harsh dark drop shadows are permitted.

## Shapes

The design system employs a soft, restrained geometry (`roundedness: 1`). Corners have a 4px (`0.25rem`) baseline radius for inputs, buttons, and micro-elements, scaling to 8px (`0.5rem`) for larger surface cards and modal sheets. 

Sharp 90-degree corners create excessive visual tension, while high-radius pill buttons feel overly playful and synthetic. A soft, disciplined 4px to 8px radius emulates hand-cut paper and natural smoothed stone edges.

## Components

### Buttons
- **Primary:** Solid Warm Charcoal (`#2F3133`) background with Warm Ivory (`#F8F6F2`) text. 4px corner radius. Padding: `0.625rem 1.25rem`. Hover state softly drops opacity to 0.88.
- **Secondary:** Transparent background with a 1px border in Soft Stone (`#D6D2CC`) and Warm Charcoal text. Hover shifts background to `Mist Grey (#E8E6E3)`.
- **Tertiary / Ghost:** No border or background fill. Warm Charcoal or Muted Charcoal text with an underline offset on hover.

### Chips & Badges
- Background in `Mist Grey (#E8E6E3)` or transparent with a 1px `Soft Stone (#D6D2CC)` outline.
- Text in `Muted Charcoal (#686966)` using `label-md`. 
- Active or filtered state applies Sage (`#9CAF88`) fill with subtle charcoal text.

### Inputs & Text Areas
- Background in `Paper White (#FCFBF8)` with a 1px border in `Soft Stone (#D6D2CC)`.
- Text in `Warm Charcoal (#2F3133)`, placeholder in `Muted Charcoal (#686966)` at 60% opacity.
- Focus state avoids thick glowing halos; transition the border to Slate Indigo (`#6C7A89`) or Sage (`#9CAF88`) with an ultra-soft 2px tint.

### Checkboxes & Radios
- Size: 16px square (checkbox) or circle (radio) with a 1px `Soft Stone (#D6D2CC)` border.
- Selected state fills with `Sage (#9CAF88)` or `Warm Charcoal (#2F3133)` holding an ivory indicator check or dot.

### Cards & Paper Sheets
- Background in `Paper White (#FCFBF8)`.
- Structured with a subtle 1px border in `Soft Stone (#D6D2CC)` and the lowest atmospheric shadow tier.
- Ample inner padding (`space-lg` to `space-xl`) prevents content from feeling confined.

### Structural Dividers & Shoji Panels
- Dividers are strict 1px solid lines using `Soft Stone (#D6D2CC)`.
- Sections can alternate between full-bleed Warm Ivory and framed Paper White modules.