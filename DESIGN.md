---
name: EcoTech Precision
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#414844'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#006c48'
  on-secondary: '#ffffff'
  secondary-container: '#92f7c3'
  on-secondary-container: '#00734d'
  tertiary: '#002d1c'
  on-tertiary: '#ffffff'
  tertiary-container: '#00452e'
  on-tertiary-container: '#75b393'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#92f7c3'
  secondary-fixed-dim: '#75daa8'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005235'
  tertiary-fixed: '#b1f0ce'
  tertiary-fixed-dim: '#95d4b3'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#0e5138'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2.5rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the balance between rigorous modern manufacturing and ecological stewardship: "Sustainable by Choice, Responsible by Design." It captures the spirit of high-grade industrial fabrication combined with environmental conscience. 

The aesthetic is grounded in **Minimalist Industrial Eco-Tech**—austere, crisp white spaces, balanced architectural typography, hairline geometric dividers, and technical clarity. The emotional target is deliberate trust, institutional reliability, and technological purity. The user interface eschews loud organic cliches (such as distressed kraft paper or rough hand-drawn motifs) in favor of clinical precision, surgical alignment, and high-efficiency whitespace that reflects advanced, clean-room non-woven manufacturing.

## Colors

The palette operates under a high-luminance light mode, contrasting surgical whites and soft sage-tinted neutral surfaces against deep forest greens and botanical accents:

- **Primary Canvas & Surfaces**: `#FFFFFF` for primary cards and focus layers, supported by `#F8FAF9` (a subtly cool, bio-clean neutral) for page-level backgrounds and grouped content backdrops.
- **Deep Forest Green (`#1B4332`, `#2D6A4F`)**: Acts as the primary anchor for institutional authority, structural framing, high-emphasis headers, and dominant primary actions.
- **Fresh Leaf Accent (`#52B788`, `#74C69D`)**: Delivers vibrant, living energy for micro-indicators, active state highlights, sustainability verification badges, and focus rings.
- **Slate Text Hierarchy**: Primary typography sits at `#1E293B` (rich graphite slate) for clear legibility without the harshness of pure black; secondary metadata rests at `#475569`; structural placeholders and deactivated indices reside at `#94A3B8`.
- **Micro-Border System**: Hairline dividers use `#E2E8F0`, keeping grid modules structured without visually cluttering content areas.

## Typography

The typographic hierarchy pairs the structured geometric elegance of **Plus Jakarta Sans** for display, headings, and metric callouts with the utilitarian, screen-optimized rhythm of **Inter** for dense technical specifications, bills of materials, and UI elements.

- **Display & Headlines**: Set in Plus Jakarta Sans with tighter negative letter-spacing (`-0.02em` to `-0.03em`) to mimic architectural and industrial type systems.
- **Labels & Overlines**: Uppercase tracking (`+0.06em`) in small sizes for product serials, GSM (grams per square meter) classifications, eco-certifications, and engineering specs.
- **Body & Data**: Inter maintains neutral horizontal proportions, avoiding visual fatigue across high-density inventory lists and spec sheets.

## Layout & Spacing

The layout is built on an expansive 12-column responsive fluid grid designed around generous whitespace to highlight product form and manufacturing caliber.

- **Desktop (>= 1200px)**: 12-column layout with 24px (`1.5rem`) gutters and generous 40px (`2.5rem`) outer section margins, bounded by a 1440px maximum content shell.
- **Tablet (768px - 1199px)**: 8-column configuration with 16px gutters and 24px margins. Spec tables transition into dual-column cards.
- **Mobile (< 768px)**: 4-column framework with 16px margins (`1.25rem`). Data grids collapse into vertical accordion cards with fixed micro-padding.
- **Rhythm**: Element offsets adhere strictly to multiples of 4px/8px, prioritizing uncluttered air around key figures, eco-metrics, and technical schematics.

## Elevation & Depth

Visual hierarchy prioritizes precision planes and low-contrast perimeter boundaries over heavy, floating cast shadows:

- **Surface Level 0 (Base Canvas)**: Flat `#F8FAF9`.
- **Surface Level 1 (Card & Module Layer)**: Pure `#FFFFFF` enclosed within a crisp 1px perimeter border of `#E2E8F0`. Shadows are omitted entirely or replaced by an imperceptible ambient bleed: `0 1px 3px rgba(27, 67, 50, 0.04)`.
- **Surface Level 2 (Flyouts, Menus & Modals)**: Floated on an ultra-diffused, botanical-tinted drop: `0 12px 32px -4px rgba(27, 67, 50, 0.08), 0 4px 8px -2px rgba(0, 0, 0, 0.02)`.
- **Interactive State Depth**: On hover, interactive cards do not pop vertically; rather, their border transitions from `#E2E8F0` to `#52B788`, accompanied by an inner hairline glow (`box-shadow: 0 0 0 1px #52B788 inset`).

## Shapes

The design uses a restrained, semi-structured **Soft (Level 1)** curvature model. 

- Interactive inputs, tags, and standard buttons utilize a subtle `4px` (`0.25rem`) border radius, preserving clean technical precision.
- Product cards, analytical modules, and modal sheets use an `8px` (`0.5rem`) radius.
- System pills and status indicators (e.g., certification flags, bio-degradable badges) use a fully rounded format (`9999px`) to create an intentional visual contrast with the rigid geometric grid.

## Components

### Buttons
- **Primary**: Solid deep forest green (`#1B4332`) background, crisp white text, 4px border radius. Hover introduces a subtle shift to `#2D6A4F` with zero translate offset.
- **Secondary (Outline)**: Transparent background, 1px border in `#1B4332`, text in `#1B4332`. On hover, fills with an ultra-light tint (`rgba(45, 106, 79, 0.05)`).
- **Eco Accent**: Leaf green (`#52B788`) background with white text, reserved for positive conversions and environmental impact verification links.

### Input Fields & Controls
- **Inputs**: Solid `#FFFFFF` fill framed by a 1px `#E2E8F0` border. Text in `#1E293B` with `#94A3B8` placeholders. Active/focus state applies a sharp 1px border of `#2D6A4F` paired with a 2px outer ring of `#74C69D` at 30% opacity.
- **Checkboxes & Radios**: 4px radius for checkboxes, circle for radios. Default border `#CBD5E1`. Checked state fills `#1B4332` with an engraved white vector icon.

### Chips & Badges
- **Technical Specs**: Monospace-like tight sans layout, background `#F1F5F3`, border `#E2E8F0`, text `#2D6A4F`.
- **Sustainability Tags**: Soft leaf green background (`rgba(82, 183, 136, 0.12)`), text `#1B4332`, accompanied by an organic leaf icon or certification checkmark.

### Cards & Modules
- **Product & Spec Cards**: Pure `#FFFFFF` background, razor-thin 1px border (`#E2E8F0`), 8px border radius, 24px inner padding. Content separates through horizontal hairline rules (`#F1F5F9`) rather than heavy background contrast.
- **Metric Highlight Tiles**: Off-white `#F8FAF9` background with top accent borders (2px `#52B788`) demonstrating Make in India production throughput, tensile strength tests, and carbon offset statistics.