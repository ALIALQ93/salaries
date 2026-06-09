---
name: PayRose Enterprise
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
  on-surface-variant: '#44474c'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#535f72'
  primary: '#000205'
  on-primary: '#ffffff'
  primary-container: '#101d2d'
  on-primary-container: '#788599'
  inverse-primary: '#bac7dd'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#000104'
  on-tertiary: '#ffffff'
  tertiary-container: '#0c1d30'
  on-tertiary-container: '#75859d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3fa'
  primary-fixed-dim: '#bac7dd'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3b4859'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  slate-900: '#0F172A'
  slate-500: '#64748B'
  leaf-vibrant: '#10B981'
  attendance-full: '#2563EB'
  attendance-half: '#F59E0B'
  attendance-absent: '#EF4444'
  attendance-overtime: '#8B5CF6'
typography:
  headline-lg:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  table-cell-padding: 8px 12px
---

## Brand & Style

The design system embodies a **Corporate / Modern** aesthetic, pivoting from a startup-centric purple to a commanding Enterprise identity. It is engineered for the financial sector, where trust, precision, and efficiency are paramount. The visual narrative balances the "Rose" aspect of the name—represented by organic green accents—with the "Pay" aspect, grounded in deep, authoritative navy blues.

The target audience consists of HR professionals, accountants, and administrators who manage high-density data. To support them, the UI utilizes a high-contrast, clean layout with "crisp" edges and subtle depth. The emotional response is one of **calm reliability and professional rigor**, ensuring that complex payroll tasks feel manageable and secure.

## Colors

The palette is anchored by **Deep Navy (#101D2D)**, used for primary navigation and high-level headings to establish authority. The **Vibrant Green (#10B981)** serves as the primary action color and brand accent, symbolizing growth and "completion" (paid status). 

**Subtle Slate Greys** are used for secondary information and borders to maintain a clean, airy feel without the harshness of pure black. Functional colors for attendance tracking are strictly categorized:
- **Blue:** Full presence.
- **Orange:** Partial presence.
- **Red:** Critical alerts and absence.
- **Purple:** High-value overtime.

The background uses a near-white **Slate-50 (#F8FAFC)** to reduce eye strain during long data-entry sessions.

## Typography

The design system utilizes **IBM Plex Sans Arabic** for its exceptional dual-language legibility and technical character. It provides a structured, professional appearance that scales perfectly from large dashboard titles to compact data grid cells.

- **Headlines:** Use Bold (700) or SemiBold (600) weights to clearly demarcate sections.
- **Data Grids:** Use `body-md` and `body-sm` for table content to maximize information density without sacrificing readability.
- **Monospace:** `JetBrains Mono` is reserved for Employee IDs, Transaction Codes, and System UIDs to ensure characters like '0' and 'O' are never confused during audits.
- **Hierarchy:** Maintain a clear vertical rhythm. English and Arabic text should always be aligned to the same baseline for a cohesive bilingual experience.

## Layout & Spacing

This design system uses a **12-column Fixed Grid** for the main dashboard content, ensuring that financial forms remain readable and don't stretch excessively on ultra-wide monitors.

- **Data Density:** A strict 4px baseline grid is used. For the "Bulk Entry" and "Payroll Table" components, padding is reduced to `8px 12px` to allow for the maximum number of rows to be visible above the fold.
- **Breakpoints:**
  - **Mobile (<768px):** Single column forms, condensed tables with horizontal scrolling, 16px margins.
  - **Tablet (768px - 1280px):** 2-column form layouts, 24px margins.
  - **Desktop (>1280px):** Full multi-column dashboard, 32px margins, fixed-width sidebars.
- **Print Optimization:** Layouts for A3/A4 must adhere to a rigid 16px safe-zone margin to prevent data loss during physical voucher printing.

## Elevation & Depth

To maintain an "Enterprise" feel, depth is communicated through **Tonal Layering** and **Soft Ambient Shadows**. We avoid heavy neomorphism or aggressive blurs.

- **Base Level (0dp):** The main application background in Slate-50.
- **Card Level (1dp):** White surfaces with a 1px border (#E2E8F0) and a subtle 4px blur shadow (5% opacity). This is the primary container for forms and tables.
- **Navigation Level (2dp):** Fixed sidebars and headers use a slightly stronger shadow to indicate they sit above the content.
- **Overlay Level (3dp):** Modals and dropdowns use a 12px blur shadow (10% opacity) and a semi-transparent backdrop blur (4px) to focus the user on the task at hand.

## Shapes

The system adopts a **Soft (0.25rem)** roundedness profile. This specific radius strikes a balance between the friendliness of consumer SaaS and the precision of industrial software.

- **Small Components:** Checkboxes and small tags use 4px (0.25rem) corners.
- **Medium Components:** Buttons, Input fields, and List items use 8px (0.5rem) corners.
- **Large Components:** Main content cards and Modals use 12px (0.75rem) corners.
- **Pill Shapes:** Exclusively reserved for status indicators (e.g., "Active", "Paid") to make them instantly recognizable from data fields.

## Components

### Buttons
- **Primary:** Solid `leaf-vibrant` with white text. High-end SaaS "squishy" feel achieved through a subtle 1px inset shadow on hover.
- **Secondary:** Transparent background with a `slate-200` border and `primary-color` text.
- **Tertiary:** Text-only for low-priority actions (e.g., "Cancel", "View More").

### Input Fields
- **Standard:** 1px border (#CBD5E1). On focus, the border changes to `primary-color` with a 2px soft glow in the same hue.
- **Density:** Provide a "Compact" variant for tables where the height is reduced from 40px to 32px.

### Data Tables (Payroll Grids)
- **Header:** Sticky headers with a `slate-100` background and `label-md` typography.
- **Rows:** Alternating "zebra" stripes (Slate-50) for readability. 1px bottom border for every row.
- **States:** Hovering over a row highlights it in a very pale green tint to assist with eye-tracking across long rows.

### Cards
- Use white backgrounds with 1px `slate-200` borders. Avoid heavy shadows; rely on the border to define the container.

### Status Chips
- Small, pill-shaped markers. Use the named attendance colors with 10% opacity backgrounds and 100% opacity text (e.g., Red text on light pink background for "Absent").