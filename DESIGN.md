---
name: Zest & Zing
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4b4731'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7c775f'
  outline-variant: '#cdc7aa'
  surface-tint: '#6a5f00'
  primary: '#6a5f00'
  on-primary: '#ffffff'
  primary-container: '#ffe600'
  on-primary-container: '#726600'
  inverse-primary: '#dec800'
  secondary: '#006d35'
  on-secondary: '#ffffff'
  secondary-container: '#3fff8b'
  on-secondary-container: '#007237'
  tertiary: '#9f4200'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffded0'
  on-tertiary-container: '#ab4700'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fde400'
  primary-fixed-dim: '#dec800'
  on-primary-fixed: '#201c00'
  on-primary-fixed-variant: '#504700'
  secondary-fixed: '#62ff96'
  secondary-fixed-dim: '#00e475'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#005226'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb692'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#7a3000'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base-unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  border-width: 3px
---

## Brand & Style
The design system embodies an energetic, high-contrast, and playful personality tailored for a vibrant lifestyle or social platform. It targets a bold, trend-conscious audience that values expressive interfaces and immediate visual impact. 

The style is a fusion of **High-Contrast Bold** and **Modern Brutalism**. It utilizes saturated citrus tones, thick structural borders, and oversized typography to create a sense of urgency and joy. The emotional response is intended to be caffeinated and optimistic—evoking the feeling of a fresh start or a sudden burst of energy.

## Colors
This palette is built on maximum saturation and high-frequency "pop" colors. 

- **Primary (Zest Yellow):** The dominant signal color, used for primary backgrounds and high-attention surfaces.
- **Secondary (Vivid Lime):** Used for success states, active indicators, and secondary call-to-actions.
- **Tertiary (Citrus Orange):** An aggressive accent for notifications, highlights, and decorative geometry.
- **Accent (Mint Teal):** A fresh cooling tone used to balance the warmth of the palette, ideal for interactive elements and links.
- **Neutral (Deep Onyx):** A near-black used for heavy borders and high-contrast text to ensure legibility against the vibrant backgrounds.

Surface colors should prioritize full-bleed saturations rather than subtle tints.

## Typography
The typography is expressive and structural. **Bricolage Grotesque** provides a quirky, variable-width feel for large headlines, appearing almost "hand-cut" at display sizes. 

**Hanken Grotesk** maintains high legibility for body copy, balancing the eccentricity of the headlines with professional clarity. **Space Grotesk** is reserved for labels and technical metadata, adding a slight futuristic edge that complements the energetic color palette. 

Use tight letter-spacing for headlines to increase visual density and impact.

## Layout & Spacing
The layout follows a **Fluid Grid** model with an emphasis on oversized gutters and generous external margins. Components should feel "chunky" and grounded. 

- **Desktop:** 12-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px gutters.

Instead of traditional white space, use "color-blocking" to separate sections. Content containers often feature a thick 3px solid neutral border to create a "sticker" effect against vibrant backgrounds. Elements should frequently break the grid or use slight offsets to enhance the playful, energetic aesthetic.

## Elevation & Depth
In this design system, depth is achieved through **Bold Borders** and **Hard Shadows** rather than soft gradients. 

- **Shadows:** Use "Hard-Stop" shadows (non-diffused) at 45-degree angles. A 4px or 8px offset in the neutral color creates a 3D "pop" effect.
- **Layering:** Hierarchy is communicated by stacking high-contrast colors (e.g., a Teal button on a Yellow surface).
- **Outlines:** Every interactive container must have a 2px or 3px solid neutral outline. This ensures that even when vibrant colors meet, the structure remains distinct.
- **No Blurs:** Avoid backdrop blurs or soft ambient shadows to maintain a crisp, comic-book-inspired clarity.

## Shapes
The shape language is **Soft** but disciplined. The slight 0.25rem corner radius on standard elements prevents the design from feeling too aggressive while maintaining the structural integrity of the high-contrast borders.

- **Standard Elements:** 0.25rem (Soft)
- **Large Containers:** 0.5rem (Medium)
- **Interactive Toggles:** 0.75rem (Large)

Avoid full pill-shapes unless used for decorative tags, as the architectural feel of the design benefits from visible corners.

## Components
- **Buttons:** Use "Sticker-Style" buttons. High-saturation backgrounds (Teal or Orange) with a 3px black border and a 4px hard black shadow that shifts 2px on press.
- **Chips:** Rectangular with sharp 2px corners. Use alternating Zest Yellow and Vivid Lime backgrounds with bold uppercase labels in Space Grotesk.
- **Lists:** Separated by heavy 3px horizontal rules. Use oversized leading icons in contrasting "pop" colors.
- **Input Fields:** Thick black outlines with a Zest Yellow focus state. Text should be Hanken Grotesk 18px for maximum readability.
- **Cards:** High-contrast containers. Use a "Title Bar" style where the header of the card has a different background color than the body, separated by a 2px internal border.
- **Checkboxes:** Oversized and square. When checked, they should fill with Vivid Lime and a thick black checkmark.