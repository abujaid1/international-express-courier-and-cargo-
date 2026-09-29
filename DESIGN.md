---
name: International Express Logistics
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#43474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#49607e'
  primary: '#000f22'
  on-primary: '#ffffff'
  primary-container: '#0a2540'
  on-primary-container: '#768dad'
  inverse-primary: '#b0c8eb'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#040e1f'
  on-tertiary: '#ffffff'
  tertiary-container: '#192436'
  on-tertiary-container: '#808ba1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#b0c8eb'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#314865'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#d8e3fb'
  tertiary-fixed-dim: '#bcc7de'
  on-tertiary-fixed: '#111c2d'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-tracking:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-sm: 1rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-velocity global supply chain logistics, engineered specifically for high-trust international courier operations, air freight, customs clearing, and multi-modal freight management. The aesthetic balances deep institutional maritime authority with immediate operational legibility. 

The visual style blends **Corporate Modernism** with **Engineered Precision**:
- Crisp, clinical light surfaces evoke modern customs transit terminals and clean corporate operations.
- Deep maritime navy creates unwavering stability and institutional credibility for high-value enterprise cargo contracts.
- High-visibility logistics amber conveys precision, transit movement, urgency, and live execution.
- The interface feels calibrated, dependable, frictionless, and commanding, instilling confidence in both multinational enterprise supply chain heads and cross-border commercial shippers.

## Colors

The palette leverages high-contrast international maritime hues paired with active transit indicators:

- **Primary (`#0A2540`)**: Maritime Navy. Serves as the bedrock color for top-level navigation, structural headers, active milestones, and master enterprise actions.
- **Secondary (`#F97316`)**: Logistics Amber. Applied deliberately for high-priority calls-to-action (e.g., "Book Freight", "Track Consignment"), critical real-time alerts, delayed flight flags, and interactive tracking accents. A deeper shade (`#EA580C`) is reserved for pressed states and critical status nodes.
- **Tertiary (`#1E293B`)**: Slate Command. Utilized for secondary navigation controls, high-density data table headers, and structural sub-borders.
- **Neutral Surface (`#F8FAFC`)**: Canvas light. Paired with pure `#FFFFFF` for container cards to ensure distinct visual boundaries without visual weight.
- **Neutral Outline (`#E2E8F0`)**: Hairline borders defining high-density logistics tables, manifest views, and input boundaries.
- **Feedback & Telemetry**:
  - Clearance / Delivered: `#059669` (Emerald Sea)
  - In-Transit / Customs Review: `#D97706` (Customs Ochre)
  - Exception / Delay: `#DC2626` (Terminal Red)

## Typography

Typography prioritizes high-speed scan-ability across dense manifests, multi-leg flight segments, and instant AWB (Air Waybill) lookups. 

- **Primary Typeface**: Plus Jakarta Sans delivers sharp geometric clarity with structured humanist terminals, preventing eye fatigue across data-heavy operational views.
- **Hierarchy & Tracking Numbers**:
  - `code-tracking` utilizes tabular numerals, semi-expanded letter spacing, and a bold weight to ensure zero ambiguity between visually similar alphanumeric characters (e.g., `0` vs `O`, `1` vs `I`).
  - Waybill numbers, container codes (BIC), and flight identifiers must always be rendered in `code-tracking` or `label-md` with uppercase transformations.
- **Headlines & Metric Callouts**: Tightly kerned negative letter spacing (`-0.02em` to `-0.03em`) lends an authoritative, institutional weight to volumetric weights, tonnage metrics, and portal headings.

## Layout & Spacing

The layout is built around a rigorous **12-column responsive fluid grid** calibrated for data density and operational dashboards:

- **Desktop (≥ 1280px)**: 12 columns, `gutter-lg` (32px), `margin-lg` (48px), max-width bounded at `1440px` for optimal tabular reading spans.
- **Tablet (768px – 1279px)**: 8 columns, `gutter` (24px), `margin` (24px). Dual-pane layouts collapse side navigation into an operational rail.
- **Mobile (≤ 767px)**: 4 columns, `gutter-sm` (16px), `margin-sm` (16px). Cards collapse into a vertical stack; cargo milestones switch from horizontal flow diagrams to vertical step tickers.
- **Spacing Rhythm**: Spacing strictly derives from an 8pt base unit. `space-xs` and `space-sm` bind micro-labels to input boundaries and flight icons. `space-md` controls standard component internal padding, while `space-xl` cleanly separates functional dispatch modules.

## Elevation & Depth

Visual hierarchy relies on crisp, architectural separation rather than heavy skeuomorphism, using low-contrast structural outlines combined with ambient maritime shadows:

- **Surface Level 0 (Base Canvas)**: `#F8FAFC`. Structural page floor.
- **Surface Level 1 (Cards, Modules, Manifest Tables)**: `#FFFFFF`. Paired with a precision border `1px solid #E2E8F0` and subtle ambient elevation:
  - `box-shadow: 0 1px 3px 0 rgba(10, 37, 64, 0.04), 0 1px 2px -1px rgba(10, 37, 64, 0.02);`
- **Surface Level 2 (Hover States, Interactive Cards, Shipment Drawers)**:
  - `box-shadow: 0 10px 25px -5px rgba(10, 37, 64, 0.08), 0 8px 10px -6px rgba(10, 37, 64, 0.04);`
  - Border transitions to `#CBD5E1`.
- **Surface Level 3 (Tracking Modals, Air Cargo Manifest Overlays)**:
  - `box-shadow: 0 20px 30px -10px rgba(10, 37, 64, 0.16), 0 10px 15px -5px rgba(10, 37, 64, 0.08);`
  - Backdrop blur filter: `backdrop-filter: blur(8px); background-color: rgba(15, 23, 42, 0.4);`

## Shapes

The design system uses deliberate corner radii to soften high-density logistics tables while maintaining an enterprise structural posture:

- **Base Radius (`rounded-md`, 8px)**: Default for operational form inputs, dropdown selectors, inner data chips, and micro action buttons.
- **Container Radius (`rounded-xl`, 16px)**: Used for shipment overview cards, tracking search hero modules, and cargo manifest summary panels.
- **Module Radius (`rounded-2xl`, 24px)**: Applied exclusively to major surface islands, featured rate calculator sections, and dashboard landing hero modules.
- **Full Pill (`rounded-full`)**: Applied to live telemetry badges (e.g., "IN TRANSIT", "CUSTOMS HOLD") and circular progress checkpoints on route lines.

## Components

### Buttons & Quick Actions
- **Primary Operational Action ("Track", "Book Consignment")**: Solid Logistics Amber (`#F97316`) background, white label, `rounded-md` (8px), height 44px (touch target 48px). Subtle drop shadow: `0 2px 4px rgba(249, 115, 22, 0.2)`. Active/Hover: `#EA580C`.
- **Secondary Action ("Download Manifest", "Export AWB")**: Deep Navy outline (`1.5px solid #0A2540`), navy text, transparent background. Hover: background fills with `rgba(10, 37, 64, 0.04)`.
- **Tertiary Utility**: Ghost style, slate text (`#475569`), zero border, used inside high-density tables for row-level actions.

### Shipment Cards & Consignment Panels
- Built with pure `#FFFFFF` background, `rounded-xl` (16px), bordered by `1px solid #E2E8F0`.
- Split into a clear dual-zone layout:
  - *Header Zone*: AWB Code in `code-tracking`, Origin (e.g., BOM - Mumbai) → Destination (e.g., LHR - London) route arrows, accompanied by live status pills.
  - *Payload Zone*: Split 3-column data grid showing Gross Weight, Dimensional Volume, and Estimated Delivery Time.

### Input Fields & Rapid Waybill Search
- **Hero Waybill Lookup**: 56px height, pure `#FFFFFF`, `rounded-xl` (16px), `2px solid #E2E8F0`. Focus state: border shifts to `#0A2540` with an amber glow ring `0 0 0 3px rgba(249, 115, 22, 0.2)`. Integrated inline amber "Track" button.
- **Standard Table Inputs**: 40px height, `rounded-md` (8px), `1px solid #CBD5E1`. Placeholder text in muted slate (`#94A3B8`).

### Status Badges & Transit Chips
- Pill-shaped (`rounded-full`), padding: `4px 12px`, typography: `label-sm` in all caps.
- *In-Transit*: Soft blue-slate background (`#F1F5F9`), Navy text (`#0A2540`), pulsing amber waypoint dot (`#F97316`).
- *Out for Delivery / Cleared*: Light emerald background (`#ECFDF5`), green text (`#065F46`).
- *Customs Inspection*: Light amber background (`#FFFBEB`), warm amber text (`#B45309`).

### Interactive Route Progress Stepper
- Horizontal chain for desktop, vertical for mobile.
- Active leg: 2px solid `#F97316` connecting line with animated transit pulse.
- Completed leg: 2px solid `#0A2540` line with a checkmarked node.
- Pending leg: 2px dashed `#CBD5E1` line with hollow node.

### Logistics Data Tables
- Row height: 48px (compact) or 60px (standard with piece breakdown).
- Zebra-free layout: pure `#FFFFFF` with `1px solid #F1F5F9` bottom dividers.
- Hover state: Row illuminates with `#F8FAFC` and displays quick-action triggers on the right boundary.