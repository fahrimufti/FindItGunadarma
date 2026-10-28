---
name: Vibrant Metric Admin
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464554'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#767586'
  outline-variant: '#c7c4d7'
  surface-tint: '#494bd6'
  primary: '#4648d4'
  on-primary: '#ffffff'
  primary-container: '#6063ee'
  on-primary-container: '#fffbff'
  inverse-primary: '#c0c1ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006c49'
  on-tertiary: '#ffffff'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-lg:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  stat-display:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
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
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system establishes a high-clarity, high-energy administrative environment built for modern SaaS products, operations suites, and analytics platforms. The brand voice balances decisive corporate utility with modern software vibrancy. It projects confidence, velocity, and structured calm.

The core visual language draws from **Corporate / Modern** principles fused with vibrant software accents:
- **Visual Contrast Architecture:** Anchored by an ultra-dark slate vertical navigation bar (`#0F172A` / `#1E293B`) paired against a broad electric indigo/violet hero band (`#6366F1`) and crisp pure white (`#FFFFFF`) floating cards over an airy, subtle cool-slate canvas (`#F8FAFC`).
- **Emotional Intent:** Reduces cognitive friction for data-dense workflows while maintaining an invigorating, polished consumer-grade SaaS finish.
- **Audience:** Operators, product teams, engineering leads, and business executives requiring swift scanning of key metrics, project states, and user hierarchies.

## Colors
The color architecture relies on a clear functional hierarchy that guides attention to status, primary actions, and metrics without inducing visual fatigue.

### Palette Architecture
- **Primary Accent (`#6366F1` / Hover `#4F46E5`):** Used for focal brand actions, hero banners, active tab highlights, metric progress fills, and primary interactive elements.
- **Secondary / Sidebar Foundation (`#0F172A` with `#1E293B` panel tones):** Used for persistent vertical navigation, top brand framing, and grounding the workspace.
- **Neutral Canvas & Tones:**
  - App Canvas Ground: `#F8FAFC`
  - Subtle Section Fill: `#F1F5F9`
  - High-Contrast Card Background: `#FFFFFF`
  - Structural Hairlines & Borders: `#E2E8F0`
  - Primary Body & Headings: `#0F172A` to `#1E293B`
  - Muted Text & Secondary Metadata: `#64748B`
- **Semantic Status Signals:**
  - **Success / Completed (`#10B981`):** Badges and indicators for completed or healthy states. Badge tint: `#ECFDF5`.
  - **Warning / Medium Priority (`#F59E0B`):** Badges for medium priority and pending actions. Badge tint: `#FFFBEB`.
  - **Danger / High Priority (`#EF4444`):** Badges for high priority, blocked items, or errors. Badge tint: `#FEF2F2`.
  - **Informational / Low Priority (`#3B82F6`):** Badges for low priority or secondary info. Badge tint: `#EFF6FF`.
  - **Neutral / Draft (`#64748B`):** Badges for neutral states. Badge tint: `#F1F5F9`.

## Typography
The system uses **Inter** throughout all tiers to maximize functional clarity, tabular figure alignment, and scan speed across high-density administrative views.

- **Metric Numerals:** Key statistics leverage `stat-display` with bold tabular numbering (`tnum`), ensuring metrics in summary card grids remain visually anchored.
- **Section Headers on Vivid Hero Bands:** Headers situated over the purple primary banner utilize pure white (`#FFFFFF`) with medium letter tracking, preserving crisp separation against saturated backgrounds.
- **Section Headers on Canvas:** Standard card headers leverage `headline-md` at `#1E293B` to maintain strong contrast against white and slate surfaces.
- **Micro-Copy & Navigation Categories:** Sidebar group headers and table headers rely on `label-sm` set to uppercase with wide tracking (`0.05em`) and subdued slate coloring (`#94A3B8` in the dark sidebar, `#64748B` on tables).

## Layout & Spacing
The layout structure is built on an interconnected 12-column grid anchored by a persistent navigation rail and a responsive dual-tier top section.

### Layout Mechanics
- **Desktop (1200px+):** Fixed left navigation rail (width: `260px`). Main content workspace flexes to 100% width with `2rem` side padding. Stat overview cards sit in a balanced 4-column arrangement (`col-span-3`). Secondary analytical modules divide evenly into 4-column and 8-column segments.
- **Tablet (768px - 1199px):** Left navigation collapses to an off-canvas drawer accessed via a hamburger menu. The 4-card overview shifts to a 2x2 grid (`col-span-6`). Tables adopt horizontal scrolling with sticky primary columns.
- **Mobile (<768px):** Navigation transitions entirely to an off-canvas slideover with smooth backdrop blur. Overview metric cards stack into single columns or 2-column compact tiles. Gutter and margin scales compress to `1rem`.

### Overlapping Hero Elevation
The primary color band (`#6366F1`) occupies the upper 180px–220px of the dashboard body. Stat cards sit halfway across this boundary with a negative top margin (`margin-top: -3.5rem`), physically bridging the vibrant hero header into the structured data workspace below.

## Elevation & Depth
Depth is achieved through **ambient diffused shadows** and **crisp low-contrast outlines**, avoiding harsh drop shadows to keep data views clean.

### Elevation Hierarchy
- **Level 0 (Canvas):** Flat base surface at `#F8FAFC`.
- **Level 1 (Default Cards & Data Tables):** Pure white background (`#FFFFFF`), a hairline outline of `1px solid #E2E8F0`, and an ultra-soft ambient shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Stat Cards & Active Popovers):** Positioned over the hero transition. Elevated with `box-shadow: 0 10px 15px -3px rgba(15, 23, 42, 0.05), 0 4px 6px -4px rgba(15, 23, 42, 0.02)` and crisp white card border.
- **Level 3 (Modals, Overlays, and Mobile Navigation):** Suspended depth using `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)` over a semi-translucent backdrop (`rgba(15, 23, 42, 0.5)`).

## Shapes
The design system embraces a **Rounded (Level 2)** geometry that softens analytical data without sacrificing administrative rigor.

- **Cards & Data Panels:** `0.75rem` (12px) border radius to establish friendly, modern structural boundaries.
- **Metric Icon Containers:** `0.5rem` to `0.75rem` (8px to 12px) rounded containers housing contextual icons.
- **Badges & Status Pills:** Full pill rounding (`9999px` or `1rem`) for instant distinction from standard rectangular buttons.
- **Buttons & Input Fields:** `0.5rem` (8px) border radius for clear, ergonomic tap targets.
- **Avatar Stacks:** Fully circular (`rounded-full`) overlapping clusters with a `2px solid #FFFFFF` perimeter ring to maintain separation.

## Components

### Buttons
- **Primary Button:** Indigo fill (`#6366F1`), white text (`#FFFFFF`), font weight 600, padding `0.5rem 1rem`, rounded `0.5rem`. Hover shifts to `#4F46E5` with an active state of `#4338CA`.
- **Secondary / Ghost Button (on Hero):** White fill (`#FFFFFF`), slate text (`#0F172A`), font weight 600. Hover applies subtle slate background tint (`#F8FAFC`).
- **Outline Button:** Border `1px solid #E2E8F0`, slate text (`#334155`), background `#FFFFFF`. Hover changes to background `#F8FAFC` and border `#CBD5E1`.

### Status Badges & Chips
- **Geometry:** Pill-shaped (`rounded-full`), height `22px`, padding `0.125rem 0.625rem`, font size `11px`, font weight 700.
- **Variants:**
  - *High Priority / Danger:* Text `#DC2626`, background `#FEE2E2`.
  - *Medium Priority / Warning:* Text `#D97706`, background `#FEF3C7`.
  - *Low Priority / Info:* Text `#2563EB`, background `#DBEAFE`.
  - *Completed / Approved:* Text `#059669`, background `#D1FAE5`.

### Stat Summary Cards
- White background (`#FFFFFF`), border radius `12px`, padding `1.25rem`.
- Layout uses a top flex row containing the metric title (`#64748B`, 14px) and a tinted rounded icon tile (size `40px x 40px`, background `#EEF2FF`, icon color `#6366F1`).
- Main numerical display uses `stat-display` (`#0F172A`).
- Sub-label provides trend or status context (e.g., "2 Completed") in 13px muted slate (`#64748B`).

### Data Tables & List Views
- **Header Row:** Background `#F8FAFC`, bottom border `1px solid #E2E8F0`, text 12px uppercase slate (`#64748B`), font weight 600, padding `0.75rem 1.5rem`.
- **Data Rows:** Background `#FFFFFF`, bottom border `1px solid #F1F5F9`, row height `64px`, vertical align center. Hover state shifts to `#F8FAFC/60`.
- **Progress Cells:** Slim progress bars (height `6px`, background `#E2E8F0`, fill `#6366F1`, border radius `9999px`) accompanied by a 13px numeric label.

### Input Fields & Search Bars
- Standard input height `40px`, background `#FFFFFF` with `1px solid #E2E8F0` border.
- Placeholder text in `#94A3B8`.
- Focus ring: `2px solid #6366F1` with an ambient glow of `rgba(99, 102, 241, 0.15)`.

### Avatar Clusters
- Intersecting circular avatar images (diameter `32px`), overlapping via negative margin (`-0.5rem`).
- Terminal counter badge (e.g., "+5") styled with indigo background (`#6366F1`), white text, and a crisp `2px solid #FFFFFF` boundary ring.