---
name: My Design System
colors:
  surface: '#fef9ec'
  surface-dim: '#dedace'
  surface-bright: '#fef9ec'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3e7'
  surface-container: '#f3ede1'
  surface-container-high: '#ede8dc'
  surface-container-highest: '#e7e2d6'
  on-surface: '#1d1c14'
  on-surface-variant: '#4b4737'
  inverse-surface: '#323028'
  inverse-on-surface: '#f5f0e4'
  outline: '#7c7765'
  outline-variant: '#cdc6b1'
  surface-tint: '#6c5e00'
  primary: '#6c5e00'
  on-primary: '#ffffff'
  primary-container: '#ffea7a'
  on-primary-container: '#776800'
  inverse-primary: '#dbc75b'
  secondary: '#675f35'
  on-secondary: '#ffffff'
  secondary-container: '#efe3ae'
  on-secondary-container: '#6d653a'
  tertiary: '#00696c'
  on-tertiary: '#ffffff'
  tertiary-container: '#89fbfe'
  on-tertiary-container: '#007477'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f8e373'
  primary-fixed-dim: '#dbc75b'
  on-primary-fixed: '#211c00'
  on-primary-fixed-variant: '#514700'
  secondary-fixed: '#efe3ae'
  secondary-fixed-dim: '#d2c794'
  on-secondary-fixed: '#211c00'
  on-secondary-fixed-variant: '#4e4720'
  tertiary-fixed: '#82f4f7'
  tertiary-fixed-dim: '#63d8db'
  on-tertiary-fixed: '#002021'
  on-tertiary-fixed-variant: '#004f51'
  background: '#fef9ec'
  on-background: '#1d1c14'
  surface-variant: '#e7e2d6'
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
  space-xl: 2rem
---

# Design System Document

## Brand & Style
The design system adopts a clean, modern aesthetic utilizing the **Inter** font family for all typography levels. The visual style leans towards a balanced, fidelity-driven approach with a light color mode, structured layout, and a roundedness scale of 2.

## Colors
The color palette is built upon a light color mode using semantic derivations from the seed color `#ffea79`.
- **Primary (`#87770c`)**: Used for key interactive elements, primary actions, and brand focal points.
- **Secondary (`#80774b`)**: Supports secondary actions and complementary UI highlights.
- **Tertiary (`#89fbfe`)**: Provides vibrant accents for specialized states and highlights.
- **Neutral (`#7a776d`)**: Forms the structural base for text, backgrounds, and subtle borders.

## Typography
All typography utilizes the **Inter** font family, ensuring high legibility, clean geometry, and a modern neutral appearance across headlines, body text, and labels.

## Layout & Spacing
The layout follows a consistent grid system using a spacing multiplier of 2, providing balanced rhythm and breathing room across standard breakpoints.

## Elevation & Depth
Elevation is handled through tonal layering and soft ambient shadows that respect the light color mode and neutral palette.

## Shapes
A roundedness level of 2 is applied across UI elements, providing a modern, approachable curvature with standard components featuring a 0.5rem radius and larger containers scaling up accordingly.

## Components
Components utilize the primary color (`#87770c`) for active states, Inter typography for text hierarchy, and a roundedness level of 2 for consistent visual styling across buttons, cards, inputs, and chips.