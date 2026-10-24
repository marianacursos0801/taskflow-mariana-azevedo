---
name: My Design System 2
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393938'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1b'
  surface-container: '#1f201f'
  surface-container-high: '#2a2a29'
  surface-container-highest: '#353534'
  on-surface: '#e4e2e0'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e4e2e0'
  inverse-on-surface: '#303030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c6'
  primary: '#c6c6c6'
  on-primary: '#2f3131'
  primary-container: '#767777'
  on-primary-container: '#040505'
  inverse-primary: '#5d5e5f'
  secondary: '#c7c6c6'
  on-secondary: '#303031'
  secondary-container: '#464747'
  on-secondary-container: '#b6b5b5'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#767777'
  on-tertiary-container: '#040506'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e3e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e4e2e0'
  surface-variant: '#353534'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

# Design System

## Brand & Style
The design system adopts a **fidelity-driven, dark-mode-first modern aesthetic**. It emphasizes clarity, precision, and an uncompromised focus on content. The emotional response is one of calm professionalism, analytical focus, and technical sophistication.

- **Style:** Clean minimalism combined with high-contrast structural dark elements.
- **Tone:** Professional, precise, minimalist, and reliable.

## Colors
The color system is built for a dark mode environment, prioritizing subdued, balanced neutral tones with high-contrast white accents and muted grayscale primaries.
- **Primary (`#767777`):** Used for primary UI actions, subtle borders, and structural framing.
- **Secondary (`#777777`):** Applied to secondary surfaces, inactive states, and supporting metadata.
- **Tertiary (`#ffffff`):** Pure white used for high-emphasis text, key interactive highlights, and critical focal points.
- **Neutral (`#787776`):** The foundational tone for dark backgrounds, panels, and continuous surface areas.

## Typography
The typography stack relies exclusively on **Inter**, ensuring pristine legibility across all screen densities and rendering engines.
- **Headlines, Body, and Labels:** All typographic tiers utilize Inter, leveraging weights from regular (`400`) to semi-bold (`600`).

## Layout & Spacing
A balanced grid system with a moderate spacing scale provides consistent breathing room throughout the interface. Margins and gutters scale predictably using the standard spacing tokens.

## Elevation & Depth
Elevation is achieved primarily through **tonal layers and subtle borders** rather than heavy drop shadows, keeping the dark-mode aesthetic clean and performant.

## Shapes
The shape language uses a **rounded** approach (roundedness level `2`), featuring standard 0.5rem corner radiuses for buttons, inputs, and containers.

## Components
Components such as buttons, inputs, cards, and chips follow the established dark-mode token set, ensuring high contrast, tactile feedback through borders and tonal shifts, and consistent Inter typography.