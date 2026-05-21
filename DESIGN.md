---
name: Industrial Precision
colors:
  surface: '#f7faf7'
  surface-dim: '#d8dbd8'
  surface-bright: '#f7faf7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f1'
  surface-container: '#ecefec'
  surface-container-high: '#e6e9e6'
  surface-container-highest: '#e0e3e0'
  on-surface: '#181c1b'
  on-surface-variant: '#42493e'
  inverse-surface: '#2d3130'
  inverse-on-surface: '#eef1ee'
  outline: '#72796e'
  outline-variant: '#c2c9bb'
  surface-tint: '#3b6934'
  primary: '#154212'
  on-primary: '#ffffff'
  primary-container: '#2d5a27'
  on-primary-container: '#9dd090'
  inverse-primary: '#a1d494'
  secondary: '#3d6a00'
  on-secondary: '#ffffff'
  secondary-container: '#aaf457'
  on-secondary-container: '#406e00'
  tertiary: '#293e28'
  on-tertiary: '#ffffff'
  tertiary-container: '#40553e'
  on-tertiary-container: '#b0c9ac'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcf0ae'
  primary-fixed-dim: '#a1d494'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#23501e'
  secondary-fixed: '#acf75a'
  secondary-fixed-dim: '#91da40'
  on-secondary-fixed: '#0f2000'
  on-secondary-fixed-variant: '#2d5000'
  tertiary-fixed: '#d0e9cb'
  tertiary-fixed-dim: '#b5cdb0'
  on-tertiary-fixed: '#0c200d'
  on-tertiary-fixed-variant: '#374c36'
  background: '#f7faf7'
  on-background: '#181c1b'
  surface-variant: '#e0e3e0'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
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
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 32px
---

## Brand & Style

This design system is built for Urban Edge Engineering, embodying the core values of **precision, reliability, and industrial expertise**. The brand personality is authoritative yet accessible, positioned as a leader in technical material testing and engineering consultancy.

The visual style follows a **Corporate / Modern** direction with a strong **Industrial** influence. It utilizes structured layouts, high-contrast typography, and a "precision-first" aesthetic. Drawing from the provided reference, the system uses sharp geometric motifs (like the hexagon and angled "edge" slices) to evoke the concept of structural integrity and technical accuracy. The interface should feel robust, clean, and meticulously organized, reflecting the environment of a high-tech laboratory.

## Colors

The color palette is derived directly from the company's industrial identity, focusing on a spectrum of greens supported by high-contrast neutrals.

- **Primary Green (#2D5A27):** A deep, forest green used for headers, primary actions, and key branding elements. It conveys stability and institutional trust.
- **Secondary Lime (#76BC21):** A vibrant accent used to draw attention to highlights, successful status indicators, and secondary UI elements.
- **Deep Neutral (#1A2E1A):** A very dark, almost black green-grey used for primary text and structural backgrounds to ensure high readability.
- **Surface Neutral (#F4F7F4):** A clean, slightly warm white used for backgrounds to maintain a professional, laboratory-clean feel.

Color usage should prioritize high contrast ratios to meet accessibility standards for professional documentation and data-heavy interfaces.

## Typography

The typography system uses **Hanken Grotesk** as the primary sans-serif for its clean, geometric, and modern industrial feel. It provides a technical but readable foundation for both marketing copy and technical reports.

**JetBrains Mono** is introduced for labels, data points, and "Technical Specs" to reinforce the precision and engineering nature of the brand.

- **Headlines:** Should be bold and impactful, often using uppercase for section titles to mimic industrial signage.
- **Body Text:** Maintains generous line height for readability in long-form reports.
- **Data Labels:** Use the monospaced font for any numeric output, registration numbers, or machine specifications to emphasize accuracy.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is "Modular and Precise."

- **Grid System:** Elements should align to a strict 8px base unit. 
- **Industrial "Edges":** Use 15-degree or 45-degree angled containers (as seen in the reference headers) to break up sections and create a sense of forward movement and "edge" engineering.
- **Data Density:** Technical dashboards should favor a "compact" spacing model (sm/md units), while marketing pages should use "expanded" spacing (lg/xl units) to allow imagery to breathe.
- **Breakpoints:** 
  - Mobile: < 600px
  - Tablet: 600px - 1024px
  - Desktop: > 1024px

## Elevation & Depth

This design system avoids excessive shadows in favor of **Tonal Layers** and **Bold Outlines**. Depth is communicated through structural layering rather than atmospheric blurs.

- **Tonal Tiers:** Use subtle shifts in background color (e.g., a slightly darker green-grey for a sidebar against a white main content area) to define hierarchy.
- **Low-Contrast Outlines:** Containers and cards should use 1px solid borders in a muted neutral-grey (#D1D5DB) rather than shadows.
- **Active Elevation:** Only use a slight, crisp shadow (4px blur, 10% opacity) on primary call-to-action buttons upon hover to indicate interactivity.
- **Hexagonal Masking:** Use the hexagonal shape from the reference as a "layer" for icons and image masks to create a distinct brand depth.

## Shapes

The shape language is **Soft (0.25rem)** to maintain a professional, "machined" look without being sharp or aggressive.

- **Standard Elements:** Buttons, inputs, and cards use a 4px corner radius.
- **Industrial Accents:** Geometric "slices" (chamfered edges) should be used on large sections and hero banners.
- **Iconography:** Icons should be enclosed in hexagonal containers where possible, or use a consistent 1.5pt stroke weight with slightly rounded terminals to match the font.

## Components

### Buttons
- **Primary:** Deep Green (#2D5A27) background, white text, 4px radius. High-contrast hover state using Lime (#76BC21).
- **Secondary:** Transparent background, Deep Green 2px border, bold uppercase text.

### Inputs & Form Fields
- Use "Precision Labels" (JetBrains Mono, 12px) floating above the field.
- Fields should have a white background with a 1px solid border. Active state uses a 2px Deep Green border.

### Cards
- White background with a 1px #D1D5DB border. 
- Headers within cards should use the Primary Green as a top border-strip (4px) to denote "Testing Category" or "Project Status."

### Progress Indicators
- Use the Lime Green (#76BC21) for "Pass/Success" states and "Certified" badges.
- Step indicators for the "Testing Process" should be connected by solid vertical or horizontal lines, representing a linear, repeatable laboratory workflow.

### Chips & Badges
- Used for "Machine Status" or "Test Type." These should be rectangular with the 4px radius, using high-contrast background tints from the brand palette.