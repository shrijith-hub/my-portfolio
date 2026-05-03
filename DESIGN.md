---
name: Aetheric Portfolio
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#ddb7ff'
  on-secondary: '#490080'
  secondary-container: '#6f00be'
  on-secondary-container: '#d6a9ff'
  tertiary: '#c6c6c6'
  on-tertiary: '#303030'
  tertiary-container: '#919191'
  on-tertiary-container: '#2a2a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb7ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6900b3'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  h1:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2.5rem
  xl: 4rem
  gutter: 24px
  container-max: 1200px
---

## Brand & Style

This design system embodies a "Futuristic Minimalism" aesthetic, blending the high-precision functionalism of Vercel and Linear with the tactile, premium polish of Apple’s hardware interfaces. The brand personality is sophisticated, visionary, and hyper-clean, designed to frame creative work within an atmosphere of technical excellence.

The style leverages **Glassmorphism** as its primary structural metaphor, creating a sense of depth and luminosity. Visuals are defined by high-contrast typography, generous whitespace, and "light-leak" accents that suggest an underlying intelligence or energy source. The experience should feel like navigating a high-end digital laboratory—organized, quiet, yet powerful.

## Colors

The palette is dual-natured, transitioning between an immersive, deep space aesthetic and a surgical, gallery-like clarity.

- **Dark Mode:** Utilizes a true black (#000000) base to maximize OLED contrast. Depth is created through "Elevated Blacks" (translucent overlays) rather than grays. Neon Purple and Blue serve as functional highlights and glowing "energy" sources.
- **Light Mode:** Uses a Soft White (#FAFAFA) base to reduce eye strain compared to pure white. Accents shift toward subtle Blue gradients and soft monochromatic shadows to maintain a premium, airy feel.
- **Accents:** Use gradients sparingly. A primary Blue-to-Purple transition should be reserved for high-impact CTAs, progress indicators, or active states to simulate a "processing" or "active AI" feel.

## Typography

The typography system pairs **Space Grotesk** for headlines with **Inter** for functional text. 

Space Grotesk provides a technical, geometric edge that reinforces the futuristic theme, particularly in large display sizes. Inter is used for body copy and UI labels to ensure maximum legibility and a systematic, "SaaS-like" professional tone. 

In Dark Mode, use high-contrast white for headings and a slightly muted gray (60-70% opacity) for body text to create a clear hierarchy. In Light Mode, use deep charcoal for text rather than pure black to maintain softness.

## Layout & Spacing

The layout philosophy is a **Fixed Grid with Fluid Padding**. Content is contained within a 12-column grid system for precision. 

- **The 8px Rhythm:** All spacing increments are multiples of 4px/8px to maintain a strict mathematical harmony.
- **Negative Space:** Embracing extreme whitespace is critical. Large vertical gaps between sections (using `xl` spacing) signify a premium, confident editorial approach.
- **Margins:** Use wide horizontal margins (32px+) on mobile and expansive gutters on desktop to prevent the UI from feeling "crowded."

## Elevation & Depth

Hierarchy is established through **Luminous Layers** rather than traditional drop shadows.

1.  **Base Layer:** Pure black background.
2.  **Glass Layer:** 40% - 60% opacity background with a 20px backdrop-blur. Use a 1px "inner glow" border (white at 10% opacity) to define the edge of the glass.
3.  **Accent Elevation:** Surfaces can have a subtle outer "aura"—a diffused glow using the primary accent color at very low opacity (5-10%) to suggest the element is powered on.
4.  **Shadows (Light Mode):** Soft, multi-layered shadows with a slight blue tint (`rgba(59, 130, 246, 0.05)`) to maintain a "clean" look without looking muddy.

## Shapes

The design system utilizes **Hyper-Rounded** geometry. Large radii create a friendly, approachable feel that balances the "cold" technical nature of the dark theme.

- **Standard Containers:** Use `rounded-lg` (1rem) for most cards and sections.
- **Interactive Elements:** Buttons and input fields should use `rounded-xl` (1.5rem) or full pill shapes to invite interaction.
- **Geometric Accents:** Subtle circular gradients in the background should be perfectly round but blurred to oblivion to create a soft "mist" effect.

## Components

- **Buttons:** Primary buttons use a solid gradient background with a subtle "white-to-transparent" top border to simulate a glass edge. Secondary buttons are "ghost" style with a 1px border that glows on hover.
- **Cards:** Glassmorphic backgrounds are mandatory. Every card must have a 1px border. In Dark Mode, this border should be a subtle gradient (top-left: white 20%, bottom-right: white 0%) to mimic light hitting a physical edge.
- **Inputs:** Minimalist fields with only a bottom border that expands to a full-glow highlight when focused. 
- **Chips/Badges:** Small, pill-shaped elements with a low-opacity accent background and a high-contrast label font.
- **Portfolio Project Tiles:** Use large-scale images with a "Scale-up" micro-interaction on hover. Overlay text should appear using a smooth "Blur-to-Focus" transition.
- **Custom Cursor:** A small, trailing glow or circle that reacts (expands/contracts) when hovering over interactive elements.