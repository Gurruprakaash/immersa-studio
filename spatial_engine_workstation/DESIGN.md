---
name: Spatial Engine Workstation
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353943'
  surface-container-lowest: '#0a0e17'
  surface-container-low: '#181b25'
  surface-container: '#1c2029'
  surface-container-high: '#262a34'
  surface-container-highest: '#31353f'
  on-surface: '#dfe2ef'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#cabeff'
  on-secondary: '#32009a'
  secondary-container: '#4918c8'
  on-secondary-container: '#b9aaff'
  tertiary: '#56e5a9'
  on-tertiary: '#003824'
  tertiary-container: '#30c88f'
  on-tertiary-container: '#004e34'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#e6deff'
  secondary-fixed-dim: '#cabeff'
  on-secondary-fixed: '#1c0062'
  on-secondary-fixed-variant: '#4918c8'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Geist
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
    letterSpacing: '0'
  label-md:
    fontFamily: Geist
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: 1.125rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Geist
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.02em
  code-sm:
    fontFamily: Geist
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
    letterSpacing: '0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 0.75rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system defines an authoring and creation environment for immersive AR/VR spatial computing. It bridges high-end 3D developer utility with consumer-grade accessibility, removing the intimidating density typical of traditional spatial engineering suites while preserving structural precision.

### Personality & Tone
- **Architectural & Rigorous:** Confident, reliable, and razor-sharp. Visual noise is aggressively minimized to keep focus on the 3D viewport and spatial assets.
- **Approachable Precision:** Technical depth presented through clear grouping, legible hierarchy, and friendly, human-scaled geometry.
- **Luminescent & Dimensional:** Deep, cool charcoal backdrops illuminated by controlled cyan and electric violet energy emitters.

### Design Movement
The aesthetic synthesizes **Technical Minimalism** with **Subtle Glassmorphism**:
- Deep obsidian canvas planes layered with dark slate paneling.
- Ultra-thin 1px mechanical containment borders preventing chromatic bleed.
- Restrained, luminous micro-accents indicating viewport transform states, active coordinate spaces, and real-time mesh statuses.

## Colors

The palette establishes an ergonomic, eye-fatigue-reducing darkroom baseline. It provides high-contrast signifiers essential for real-time viewport telemetry and complex spatial tree graphs.

### Core Architecture
- **Primary (`#38BDF8` - Soft Precision Cyan):** Dedicated to active transform gizmos, precision alignment indicators, tool selection highlights, active telemetry states, and interactive nodes.
- **Secondary (`#7C5CFC` - Electric Indigo):** Reserved for platform actions, primary execution buttons, key navigational anchors, and global deployment triggers. Hover shifts to `#6947EB`, active states press to `#5A35E0`.
- **Tertiary (`#10B981` - Engine Emerald):** Signifies live runtimes, clean compiles, valid physics geometry, and successful cloud rendering jobs.
- **Neutral Surface Foundation (`#0F131C`):** Base canvas and deep-space viewport framing.

### Structural Neutrals & Surfaces
- **Viewport Canvas Canvas (`#0F131C`):** Lowest substrate level; unlit anchor.
- **Panels & Toolbars (`#161B26`):** Secondary layer housing outliners, property inspectors, and persistent dock headers.
- **Surfaces & Cards (`#1F2636`):** Elevated utility components, dropdown sheets, and asset tiles.
- **Gridlines & Structural Dividers (`#2A3347`):** Fine 1px mechanical seams demarcating panel edges and collapsed tool drawers.

### Functional Typography Spectrum
- **High Contrast (`#FFFFFF`):** Selected entity titles, primary values, and viewport orientation tags.
- **Mid Contrast (`#94A3B8`):** Inspector labels, attribute keys, and dimensional inputs.
- **Subdued (`#64748B`):** Measurement units, keyboard shortcuts, and inactive node metadata.

### Semantic Alerts
- **Warning / Draft (`#F59E0B`):** Mesh unoptimized, missing asset link, draft build.
- **Destructive / Error (`#EF4444`):** Node disconnection, delete entity, shader compilation failure.

## Typography

The typographic hierarchy couples the sculptural geometry of **Plus Jakarta Sans** with the monoline precision of **Geist**.

### Strategic Hierarchy
- **Plus Jakarta Sans (Headlines & Modals):** Injects welcoming geometry into modal titles, top-level project headers, and key milestone callouts. Its soft curves balance technical intensity.
- **Geist (Body & Inspector UI):** Delivers clean readability for spatial transform parameters (X, Y, Z coordinates, Quaternions), hierarchy tree names, properties panels, and tabular data. Geist preserves micro-alignment in dense, space-constrained sidebars.

### Styling Rules
- **Numerical Alignment:** All numerical values in inspector fields must use tabular lining figures (`font-variant-numeric: tabular-nums`) to prevent layout shifts during real-time property scrubbing.
- **Uppercase Labels:** Parameter category identifiers (e.g., `TRANSFORM`, `MESH RENDERER`, `COLLIDER`) use `label-sm` with uppercase transforms and `0.05em` letter spacing for clean vertical scanning.

## Layout & Spacing

Designed primarily for standard desktop viewports (1440x900 baseline), the layout uses a specialized multi-pane desktop IDE shell with collapsible sidebars and an expansive central viewport.

### Workspace Blueprint (1440x900 Desktop Target)
- **Primary Shell:** Fixed outer perimeter margins of `1rem`. The viewport area expands fluidly to absorb all remaining screen space.
- **Top Utility Rail:** Height fixed at `3rem` (48px) for scene state, build triggers, simulation toggles, and global viewport settings.
- **Left Scene Hierarchy / Outliner:** Fixed width of `17.5rem` (280px), collapsible to 0.
- **Right Property Inspector:** Fixed width of `21.25rem` (340px) with internal section scrolling.
- **Bottom Timeline / Asset Shelf:** Collapsible shelf anchored to the lower viewport border with a default height of `12.5rem` (200px).
- **Viewport Canvas:** Fluid center area with an absolute minimum bounding width of `37.5rem` (600px).

### Spacing Rhythms
- **Micro-Gaps (`space-xs` - 4px):** Used between tightly coupled coordinate axes (e.g., X, Y, and Z input fields).
- **Control Gaps (`space-sm` - 8px):** Standard spacing between stacked property controls and toolbar icon items.
- **Container Gaps (`space-md` - 12px):** Internal padding for inspector cards and outliner item groupings.
- **Section Insets (`space-lg` - 16px):** Primary panel edge padding and floating viewport overlay offsets.

## Elevation & Depth

Depth is established through dark surface stepping, crisp 1px borders, and cyan/violet light boundaries rather than heavy drop shadows.

### Elevation Hierarchy

1. **Substrate Level 0 (Canvas Base - `#0F131C`):**
   - The interactive 3D WebGL/WebGPU viewport background. Zero elevation, infinite perceived depth.

2. **Structural Level 1 (Docked Panels - `#161B26`):**
   - Left tree outliners, right property inspectors, and top shelf panels.
   - Demarcated with a sharp 1px border (`#2A3347`) facing the central canvas. No drop shadow.

3. **Floating Utility Level 2 (Inspector Cards & Viewport HUDs - `#1F2636`):**
   - Floating spatial gizmo controls, camera mode selectors, and nested property groups.
   - Border: 1px solid `#2A3347`.
   - Shadow: `0 4px 16px -2px rgba(0, 0, 0, 0.45)`.

4. **Popout Level 3 (Menus, Color Pickers & Floating Palettes):**
   - Background: `rgba(31, 38, 54, 0.88)` with `backdrop-filter: blur(16px)`.
   - Border: 1px solid rgba(56, 189, 248, 0.25).
   - Shadow: `0 12px 32px -4px rgba(0, 0, 0, 0.65), 0 0 0 1px rgba(255, 255, 255, 0.05)`.

5. **Modal Level 4 (System Dialogs & Scene Exporters):**
   - Fully surfaced with `#1F2636`, rimmed with a 1px border (`#2A3347`).
   - Shadow: `0 24px 48px -12px rgba(0, 0, 0, 0.85)`. Backing scrim: `rgba(15, 19, 28, 0.75)` with `backdrop-filter: blur(8px)`.

## Shapes

The design system applies a calibrated **Level 2 (Rounded)** shape strategy. Corners remain compact to balance friendliness with the tight spatial density needed for professional software.

### Geometry Specifications
- **Standard UI Elements (`0.5rem` / 8px):** Applied to buttons, text inputs, inspector cards, dropdown triggers, and viewport control buttons.
- **Large Containers (`1rem` / 16px):** Applied to modal windows, asset drawer panels, and primary preview dialogs.
- **Pill Badges (`9999px`):** Used for viewport status indicators (e.g., `FPS: 60`, `AR Passthrough Active`, `Baked`), tag pills, and active camera state toggles.
- **Coordinate Badges (`0.25rem` / 4px):** Sub-labels inside input fields for X (Red/Crimson), Y (Emerald), and Z (Cyan) axis markers.

## Components

### Buttons
- **Primary Action (Secondary Color `#7C5CFC`):**
  - Height: `2.25rem` (36px). Padding: `0 1rem`. Border-radius: `0.5rem` (8px).
  - Background `#7C5CFC`, typography `#FFFFFF` (`label-md`).
  - Hover: `#6947EB`. Active: `#5A35E0`. Focus: `0 0 0 2px #0F131C, 0 0 0 4px #38BDF8`.
- **Secondary (Inspector Utility):**
  - Background `#1F2636`, border `1px solid #2A3347`, text `#FFFFFF`.
  - Hover: Background `#2A3347`, text `#FFFFFF`.
- **Ghost / Viewport Tool Toggle:**
  - Square dimension: `2rem x 2rem` (32x32px).
  - Resting: Background transparent, icon color `#94A3B8`.
  - Active/Selected: Background `rgba(56, 189, 248, 0.12)`, border `1px solid #38BDF8`, icon color `#38BDF8`.

### Input Fields & Transform Scrubbers
- **Numeric Property Inputs:**
  - Height: `1.875rem` (30px). Background `#0F131C`, border `1px solid #2A3347`, border-radius `0.375rem` (6px).
  - Typography: `Geist` tabular figures, color `#FFFFFF`.
  - Prefix Axis Label: Crisp colored indicator (X: `#EF4444`, Y: `#10B981`, Z: `#38BDF8`).
  - Scrubbing State: Cursor shifts to `ew-resize`. While dragged, display a faint horizontal bar filling with `#38BDF8`.

### Checkboxes & Radio Controls
- **Checkboxes:** Size `1rem x 1rem` (16x16px). Border `1px solid #2A3347`, background `#0F131C`, radius `0.25rem` (4px). Checked state: Background `#38BDF8`, icon color `#0F131C`.
- **Radio Buttons:** Size `1rem x 1rem` (16x16px). Ring border `1px solid #2A3347`. Checked state: Outer ring `#38BDF8`, center dot `#38BDF8` with a 4px inner gap.

### Spatial Hierarchy Tree (Lists)
- **Node Item:**
  - Height: `1.75rem` (28px). Internal padding: `0 0.5rem`.
  - Indentation: `0.75rem` per depth tier, with a subtle vertical guide line (`1px solid #2A3347`).
  - Selected Node: Background `rgba(124, 92, 252, 0.15)`, text `#FFFFFF`, left accent indicator `2px solid #7C5CFC`.

### Chips & Viewport Telemetry Tags
- **Status Chips:**
  - Height: `1.25rem` (20px). Padding: `0 0.5rem`. Radius `9999px`.
  - Background: `rgba(255, 255, 255, 0.05)`, border `1px solid #2A3347`.
  - Dot indicator: 6px circular dot with semantic color (`#10B981` for active, `#F59E0B` for unbaked).

### Inspector Accordion Cards
- Container background `#161B26` with inner sub-panels set to `#1F2636`.
- Border: `1px solid #2A3347`. Border-radius: `0.5rem` (8px).
- Header: Collapsible chevron, section title in `label-md` (`#FFFFFF`), quick-action bypass toggle aligned right.