---
name: M&J Tur Gestão Universitária
colors:
  surface: '#f9f9fe'
  surface-dim: '#d9dadf'
  surface-bright: '#f9f9fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f8'
  surface-container: '#ededf3'
  surface-container-high: '#e8e8ed'
  surface-container-highest: '#e2e2e7'
  on-surface: '#1a1c1f'
  on-surface-variant: '#5a403f'
  inverse-surface: '#2e3034'
  inverse-on-surface: '#f0f0f5'
  outline: '#8e706e'
  outline-variant: '#e2bebc'
  surface-tint: '#b4262d'
  primary: '#740010'
  on-primary: '#ffffff'
  primary-container: '#9b111e'
  on-primary-container: '#ffa8a3'
  inverse-primary: '#ffb3af'
  secondary: '#745b00'
  on-secondary: '#ffffff'
  secondary-container: '#fcd358'
  on-secondary-container: '#735a00'
  tertiary: '#73001c'
  on-tertiary: '#ffffff'
  tertiary-container: '#97182e'
  on-tertiary-container: '#ffa6aa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3af'
  on-primary-fixed: '#410005'
  on-primary-fixed-variant: '#910618'
  secondary-fixed: '#ffe08b'
  secondary-fixed-dim: '#eac249'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#ffdada'
  tertiary-fixed-dim: '#ffb3b5'
  on-tertiary-fixed: '#40000b'
  on-tertiary-fixed-variant: '#8e0f28'
  background: '#f9f9fe'
  on-background: '#1a1c1f'
  surface-variant: '#e2e2e7'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system embodies institutional stability, corporate refinement, and operational precision tailored for university mobility logistics. Combining the timeless authority of deep ruby red with the distinction of metallic amber-gold accents and a pristine off-white canvas, the aesthetic delivers an executive yet functional experience. 

The visual style is **Corporate / Modern** with subtle tactile quality:
- **Atmosphere:** Grounded, trustworthy, executive, and punctilious.
- **Audience:** Logistics coordinators, university transport administrators, fleet managers, and student passengers expecting reliability and clarity.
- **Visual Rhythm:** Structured layouts, sharp hierarchical demarcation, crisp borders, and purposeful contrast engineered for high-density transport dashboards, route assignments, and student fleet tracking.

## Colors

The color palette balances the gravitas of Crimson Ruby with the prestige of transport gold on clean, light surfaces:

- **Primary (`#9B111E` - Crimson Ruby):** Used for primary CTAs, critical status badges, active navigation indicators, key brand elements, and priority route highlights.
- **Secondary (`#C5A028` - Imperial Gold / Amber):** Applied sparingly to premium tier indicators, key operational confirmations, certification badges, active vehicle telemetry highlights, and decorative border accents.
- **Tertiary (`#800020` - Deep Burgundy):** Serves as an anchoring contrast tone for table headers, active navigation rails, and prominent status flags.
- **Neutral (`#2B2D31` - Graphite Ink):** High-readability body text, secondary icons, and structural divider lines.
- **Surfaces & Backgrounds:** Crisp white (`#FFFFFF`) layered over soft institutional off-white (`#F8F9FA` to `#F3F4F6`), preventing glare during extended operational monitoring.

## Typography

Typographic scale is powered exclusively by **Inter**, leveraging its tall x-height, neutral tone, and superior tabular numeral legibility for timetable grids, passenger manifests, and bus telemetry.

- **Headlines:** Set with compact negative tracking (`-0.01em` to `-0.02em`) to project firm executive control and structure.
- **Data & Tables:** Tabular figures (`tnum`) must be enforced on all time displays, student registration IDs, seat capacities, and vehicle plate numbers.
- **Labels & Microcopy:** Clean uppercase or semi-bold sentence case with slight positive tracking to ensure high readability under low-light cabin or terminal settings.

## Layout & Spacing

The layout is built upon an 8pt architectural rhythm within a 12-column responsive fluid grid:

- **Desktop (1200px+):** 12 columns with 24px (`gutter-md`) to 32px (`gutter-lg`) gutters and 48px (`margin-lg`) outer margins. Supports side-by-side trip maps, data grids, and live dispatch schedules.
- **Tablet (768px - 1199px):** 8 columns, 16px to 24px gutters, collapsing secondary analytics panels beneath primary route feeds.
- **Mobile (< 768px):** 4 columns, 16px gutters, and 16px outer margins. Route manifests collapse into single-column card stacks with persistent bottom-anchored action bars.
- **Component Padding:** Strictly adheres to the 4px/8px step scale (`space-xs` through `space-xl`) to preserve clean typographic margins inside compact table rows and route badge containers.

## Elevation & Depth

Visual hierarchy combines low-contrast outlines with subtle ambient elevation, providing clarity without visual noise:

- **Surface Tier 0 (Canvas):** `#F8F9FA` for overall system backdrop.
- **Surface Tier 1 (Cards & Data Panels):** `#FFFFFF` bordered by a crisp `1px solid #E5E7EB` stroke.
- **Surface Tier 2 (Flyouts & Dropdowns):** Subtle ambient shadow: `0 4px 16px -2px rgba(43, 45, 49, 0.08)`, elevated for schedule selects and filter menus.
- **Surface Tier 3 (Modals & Alerts):** Grounded shadow: `0 12px 32px -4px rgba(155, 17, 30, 0.12)`, accented with a 2px top border in Ruby (`#9B111E`) or Gold (`#C5A028`) depending on context.
- **Zero-Shadow Rule:** In data-dense contexts (manifest lists, seat layouts), eliminate drop shadows in favor of precise `1px` structural borders to preserve vertical reading flow.

## Shapes

The design system standardizes on **Level 2 Roundedness** (8px base radius) to strike a balance between executive seriousness and modern ergonomic usability:

- **Inputs, Buttons, and Form Controls:** `0.5rem` (8px) radius.
- **Cards, Tables, and Manifest Containers:** `rounded-lg` at `1rem` (16px) radius for outer wrappers.
- **Pills and Badges:** `rounded-xl` (`1.5rem`) strictly reserved for status chips (e.g., "Em Rota", "Vagas Esgotadas").
- **Inner Nested Elements:** Nested chips or inner panels inside cards must maintain an 8px radius to keep concentric harmony.

## Components

### Buttons
- **Primary:** Background `#9B111E`, text `#FFFFFF`, 8px corner radius, bold Inter label. On hover, darken to `#800020` with a smooth 150ms transition.
- **Secondary:** Surface `#FFFFFF`, border `1.5px solid #C5A028`, text `#C5A028`. On hover, fills with `#FDFBF2`.
- **Destructive / Alert:** Background `#C02626`, text `#FFFFFF`.
- **Tertiary / Ghost:** Borderless, neutral `#2B2D31`, text underline or ruby highlight on hover.

### Chips & Status Badges
- **Active / En Route:** Background `#FDF8E8`, border `1px solid #C5A028`, text `#8A6E18`.
- **Critical / Delayed:** Background `#FDF2F2`, border `1px solid #9B111E`, text `#9B111E`.
- **Confirmed / On Schedule:** Background `#F0FDF4`, border `1px solid #22C55E`, text `#15803D`.

### Form Fields & Inputs
- **Base Style:** 8px radius, white surface, `1px solid #D1D5DB`, 14px typography.
- **Focus State:** Border transitions to `#9B111E` with an outer ring `0 0 0 3px rgba(155, 17, 30, 0.12)`.
- **Prefix / Suffix Icons:** Neutral `#6B7280`, shifting to `#9B111E` when active.

### Lists & Manifest Tables
- Header row backed by `#F3F4F6` with bold 12px uppercase labels and bottom border `2px solid #E5E7EB`.
- Alternating row zebra banding is disabled; rows rely on `1px solid #F3F4F6` separators and `#FAFAFA` hover highlights.
- Tabular figures utilized across departure times, seat counts, and registration codes.

### Cards & Dispatch Panels
- White container (`#FFFFFF`), `1px solid #E5E7EB` border, 16px radius.
- Optional 3px accent bar along the top edge: Ruby (`#9B111E`) for university shift routes, Gold (`#C5A028`) for charter services.

### Specialized Transport Components
- **Seat Allocation Grid:** 8px square cells representing van/bus layouts with clear color states (Available: `#F3F4F6`, Selected: `#C5A028`, Occupied: `#9B111E`).
- **Student Boarding Pass Card:** Tear-line visual divider, QR code display area, and dual-tone Ruby/Gold route information header.