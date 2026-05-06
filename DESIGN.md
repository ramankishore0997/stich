---
name: razrmarket Premium Green System
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#383939'
  surface-container-lowest: '#0d0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2a'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#bbcbbb'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#869486'
  outline-variant: '#3d4a3e'
  surface-tint: '#4ae183'
  primary: '#54e98a'
  on-primary: '#003919'
  primary-container: '#2ecc71'
  on-primary-container: '#005027'
  inverse-primary: '#006d37'
  secondary: '#4eddbb'
  on-secondary: '#00382c'
  secondary-container: '#00b596'
  on-secondary-container: '#003f33'
  tertiary: '#a3d3ff'
  on-tertiary: '#003351'
  tertiary-container: '#5fbaff'
  on-tertiary-container: '#004970'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6bfe9c'
  primary-fixed-dim: '#4ae183'
  on-primary-fixed: '#00210c'
  on-primary-fixed-variant: '#005228'
  secondary-fixed: '#6ff9d6'
  secondary-fixed-dim: '#4eddbb'
  on-secondary-fixed: '#002019'
  on-secondary-fixed-variant: '#005141'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#92ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Work Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Work Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Work Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0em
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-caps:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  data-mono:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  section-gap: 48px
  stack-sm: 4px
  stack-md: 12px
---

## Brand & Style

The design system is engineered to evoke a sense of high-stakes precision, digital luxury, and advanced intelligence. It targets high-net-worth traders and institutional investors who demand a sophisticated, "dark mode" interface that minimizes eye strain while emphasizing critical financial data.

The aesthetic blends **Glassmorphism** with **Futuristic Minimalism**. Surfaces feel like polished obsidian slabs, layered with translucent frosted glass that allows vibrant emerald energy to bleed through. The emotional response is one of calm authority, reliability, and cutting-edge technological superiority. AI-driven motifs are represented through subtle animated glowing orbs and rhythmic pulse effects that signal live data processing.

## Colors

The palette is anchored by the **Deep Charcoal (#121414)** foundation, creating a void-like depth that allows the **Emerald Green (#2ECC71)** to pop with radioactive clarity. 

- **Primary Emerald:** Used for critical actions, positive market trends, and active AI states. It should always be accompanied by a subtle outer glow to simulate a light-emissive surface.
- **Surface Tones:** Use varying shades of charcoal to define hierarchy. The base canvas is near-black, while interactive cards use the slightly lighter neutral.
- **Semantic Accents:** While Emerald represents growth, use a high-contrast muted red for negative trends, ensuring it does not compete with the primary brand color in saturation.

## Typography

This design system exclusively utilizes **Work Sans** to provide a grounded, professional atmosphere that balances the futuristic visuals. 

- **Headlines:** Use Bold and Semi-Bold weights with tight letter spacing to create a high-impact, editorial feel.
- **Numerical Data:** For financial charts and ticker tapes, use the Medium weight. Work Sans's clean apertures ensure legibility even at small sizes in dense trading tables.
- **Labels:** Use uppercase tracking for secondary metadata to differentiate it from primary body text without increasing visual noise.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid Grid**. The primary dashboard utilizes a 12-column system for wide screens, transitioning to a stack-based layout for mobile. 

- **Rhythm:** An 8px linear scale dictates all margins and padding, ensuring mathematical harmony.
- **Trading View:** Within financial modules, the spacing is tightened to "Compact" (4px/8px units) to maximize data density.
- **Whitespace:** Use generous margins (48px+) between major sections to maintain a premium, airy feel that prevents the dark theme from feeling claustrophobic.

## Elevation & Depth

Hierarchy is established through **Layered Glassmorphism** rather than traditional drop shadows.

- **Level 1 (Base):** The #0A0B0B canvas.
- **Level 2 (Cards):** #121414 with a 1px border of `rgba(255, 255, 255, 0.05)`.
- **Level 3 (Modals/Popovers):** Semi-transparent background with a `backdrop-filter: blur(20px)`.
- **Glow Effects:** Use "Emerald Aura" for elevated primary elements. This is achieved via a 0px blur, 15px spread shadow using the Primary Emerald at 20% opacity.

## Shapes

The design system employs a consistent **8px corner radius** (Level 2) for all primary containers, buttons, and input fields. This radius strikes a balance between professional geometry and modern softness.

- **Small elements:** Tags and chips use a 4px radius.
- **Large containers:** Hero sections and large modal overlays may increase to 16px to emphasize the "glass slab" metaphor.
- **Lines:** Chart lines should use a "Bezier" smoothing to align with the organic nature of AI-driven data.

## Components

- **Buttons:** Primary buttons are solid Emerald Green with black text. Secondary buttons are "Ghost" style with an Emerald border and a subtle hover glow.
- **Glass Cards:** Feature a top-down linear gradient from `rgba(255,255,255, 0.05)` to `transparent`.
- **Input Fields:** Deep charcoal backgrounds with a bottom-only 2px Emerald border that activates/glows on focus.
- **Financial Charts:** Use "Neon-Trace" styling—thin 2pt lines with a vertical gradient fill (Emerald to Transparent) beneath the line.
- **AI Motifs:** Small, animated "Processing" pips located in the corner of data cards, using a radial Emerald gradient that pulses slowly.
- **Status Chips:** High-contrast capsules with pill-shaped rounding. Positive growth chips use Emerald Green text on a 10% opacity Emerald background.