---
name: Espresso Engineering
colors:
  surface: '#151312'
  surface-dim: '#151312'
  surface-bright: '#3c3838'
  surface-container-lowest: '#100e0d'
  surface-container-low: '#1e1b1a'
  surface-container: '#221f1e'
  surface-container-high: '#2d2929'
  surface-container-highest: '#383433'
  on-surface: '#e8e1df'
  on-surface-variant: '#d3c3c0'
  inverse-surface: '#e8e1df'
  inverse-on-surface: '#33302f'
  outline: '#9c8d8b'
  outline-variant: '#504442'
  surface-tint: '#e3beb8'
  primary: '#e3beb8'
  on-primary: '#422a26'
  primary-container: '#3e2723'
  on-primary-container: '#ae8d87'
  inverse-primary: '#745853'
  secondary: '#e7bdb1'
  on-secondary: '#442a22'
  secondary-container: '#5d4037'
  on-secondary-container: '#d4aca0'
  tertiary: '#b5ccc3'
  on-tertiary: '#20342e'
  tertiary-container: '#1d312b'
  on-tertiary-container: '#839991'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#e3beb8'
  on-primary-fixed: '#2b1613'
  on-primary-fixed-variant: '#5b403c'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#e7bdb1'
  on-secondary-fixed: '#2c160e'
  on-secondary-fixed-variant: '#5d4037'
  tertiary-fixed: '#d0e8de'
  tertiary-fixed-dim: '#b5ccc3'
  on-tertiary-fixed: '#0b1f1a'
  on-tertiary-fixed-variant: '#364b44'
  background: '#151312'
  on-background: '#e8e1df'
  surface-variant: '#383433'
  espresso-glow: rgba(62, 39, 35, 0.3)
  surface-charcoal: '#051424'
  on-surface-muted: '#94A3B8'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 64px
  gutter: 24px
  section-padding: 120px
  container-max: 1200px
---

## Brand & Style

This design system is tailored for a high-end engineering persona, evolving the "Lumina" aesthetic into a warmer, more sophisticated territory. By replacing sterile electric blues with a **Rich Espresso Brown**, the design shifts from "generic tech" to "premium craftsmanship." The style remains rooted in **Minimalism** and **Glassmorphism**, but with a color palette that evokes quality, depth, and focused energy.

The brand personality is precise, technical, and mature. It maintains a "Dark Mode First" philosophy where depth is created through atmospheric layers and light-refraction. The emotional response is one of grounded authority—the UI should feel like a bespoke physical instrument or a high-performance studio environment.

Key stylistic pillars:
- **Warm Precision:** Fine 1px borders and perfect alignment, now accented with deep, earthy tones.
- **Organic Glows:** Use "Espresso" light-bleeds and glows to suggest a glowing vacuum tube or a backlit high-end keyboard.
- **Atmospheric Depth:** Translucent surfaces that suggest a multi-layered workspace, prioritizing clarity and intentionality.

## Colors

The palette is anchored in deep charcoal foundations, utilizing the rich espresso brown as the sole driver of attention and hierarchy.

- **Backgrounds:** The base layer uses a near-black charcoal (`#051424`). Surface containers utilize incremental lightness to establish hierarchy.
- **Primary Accents:** **Espresso Brown (#3E2723)** is the hero color. It is used for primary actions, active states, and high-impact highlights. For interactive states, use a slightly lifted **#5D4037**.
- **Typography:** Primary text is Pure White (`#FFFFFF`). Secondary content uses a muted slate (`#94A3B8`) to maintain a soft contrast that reduces eye strain in dark environments.
- **Borders & Dividers:** Use low-opacity white (10% alpha) for structural definition. The primary accent color should be used for "active" borders on focused inputs or hovered cards.

## Typography

The system balances geometric modernism with technical utility through a three-font hierarchy.

- **Headlines (Geist):** Tight tracking and negative letter-spacing for a "locked-in" professional look.
- **Body (Inter):** Maximum legibility for documentation and descriptions.
- **Technical (JetBrains Mono):** Used for metadata, labels, and code snippets to reinforce the engineering pedigree.

**Hierarchy Rule:** Use significant weight jumps to define sections. All labels should be in `label-caps` to distinguish them from standard body prose.

## Layout & Spacing

A **Fixed Grid** model ensures an editorial, high-end feel on desktop, while a **Fluid Layout** provides accessibility on mobile.

- **Grid:** 12-column system within a 1200px container.
- **Rhythm:** All internal spacing follows an 8px linear scale. 
- **Whitespace:** Use aggressive vertical gaps (120px) to separate major content blocks, signaling premium production value.
- **Reflow:** On mobile devices (below 768px), reduce section padding to 64px and collapse all multi-column grids into single-column vertical stacks.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Backdrop Blurs**, moving away from standard drop shadows toward light-based metaphors.

- **Level 0 (Base):** `#051424`.
- **Level 1 (Surface):** Subtle cards (`#122131`) with 1px borders at 10% white opacity.
- **Level 2 (Overlays):** Glassmorphic panels with 12px-20px background blur and a 20% opacity charcoal fill.
- **The "Coffee Glow":** Interactive elements use a soft, large-radius aura (`blur: 40px+`, `opacity: 15%`) using the **Espresso Brown** color. This creates a warm, premium radiance behind active components.

## Shapes

The "Soft-Modern" shape language uses consistent radii to balance technical precision with approachable software design.

- **Standard Elements:** 0.5rem (8px) for buttons, inputs, and chips.
- **Major Containers:** 1.5rem (24px) for section wrappers and large project cards.
- **Visual Continuity:** Ensure that nested elements (like an image inside a card) have a slightly smaller radius than their container to maintain optical harmony.

## Components

- **Buttons:** Primary buttons feature a solid **Espresso Brown (#3E2723)** fill with white text. Hover states lift the color to `#5D4037`. Secondary buttons use a "Ghost" style with a 20% white border.
- **Input Fields:** Use a darker background than the surface (`#010f1f`). Focus states trigger a 1px Espresso Brown border and a subtle brown outer glow.
- **Project Cards:** 1.5rem rounded containers. On hover, the border transitions to Espresso Brown and a soft brown "aura" glow appears behind the card.
- **Chips (Tech Stack):** Pill-shaped, using `JetBrains Mono`. Background is a 5% white tint; the border is a muted charcoal.
- **Navigation:** Fixed glassmorphic bar at the top. Active links are highlighted with an Espresso Brown underline or text color shift.
- **Status Indicators:** Small dots with a "breathing" animation. Use Espresso Brown for "Active/System Online" to maintain the premium theme.