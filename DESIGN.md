---
name: Voltage Precision
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#40493a'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#707a69'
  outline-variant: '#c0cab6'
  surface-tint: '#226d00'
  primary: '#226d00'
  on-primary: '#ffffff'
  primary-container: '#6cbf4a'
  on-primary-container: '#154a00'
  inverse-primary: '#86db62'
  secondary: '#3e6836'
  on-secondary: '#ffffff'
  secondary-container: '#bcedad'
  on-secondary-container: '#426d3a'
  tertiary: '#4f644d'
  on-tertiary: '#ffffff'
  tertiary-container: '#9cb297'
  on-tertiary-container: '#324530'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a1f87b'
  primary-fixed-dim: '#86db62'
  on-primary-fixed: '#052100'
  on-primary-fixed-variant: '#185200'
  secondary-fixed: '#bff0b0'
  secondary-fixed-dim: '#a3d396'
  on-secondary-fixed: '#002201'
  on-secondary-fixed-variant: '#275020'
  tertiary-fixed: '#d2e9cc'
  tertiary-fixed-dim: '#b6cdb1'
  on-tertiary-fixed: '#0e1f0e'
  on-tertiary-fixed-variant: '#384c37'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style
The design system is engineered to evoke a sense of high-tech precision, environmental stewardship, and mechanical expertise. Targeting owners of hybrid and electric vehicles, the interface must feel as advanced as the propulsion systems it services. 

The style is **Corporate Modern** with **High-Contrast** accents. It leverages expansive white space to denote cleanliness and professional organization, while utilizing sharp green accents to signify electrical energy and sustainability. The aesthetic is clinical yet approachable, ensuring users feel their high-value assets are in capable, technologically-literate hands.

## Colors
The color palette is built on a foundation of "Efficiency Green" and "Deep Technical Charcoal." 

- **Primary Green (#6CBF4A):** Used for action-oriented elements and branding. When used as a background, all overlaid text must be pure white for AA/AAA accessibility.
- **Secondary & Tertiary Greens:** Reserved for tonal layering, subtle hover states, and background containers to differentiate service categories.
- **Dark Neutral (#1A1A1A):** Used for the footer and high-impact "Power Sections." On these backgrounds, typography must be white.
- **Surface Strategy:** Use #FFFFFF as the primary background to maintain a "clean-room" workshop aesthetic. Use #D8EFD2 for secondary surface areas like sidebar backgrounds or card headers.

## Typography
This design system utilizes **Inter** exclusively to achieve a systematic, utilitarian, and highly legible look. 

- **Headlines:** Use Bold weights (700) with slight negative letter-spacing to create a "machined" and impactful appearance.
- **Body:** The base size is 16px. Use #4A4A4A for long-form text to reduce eye strain while maintaining high contrast.
- **Labels:** Use uppercase for small labels (like "Part Number" or "Battery Health") to provide a technical, data-driven feel.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop and a **Fluid** model on mobile.

- **Desktop:** A 12-column grid with a 1280px max-width. Gutters are fixed at 24px to ensure breathing room between technical specs.
- **Mobile:** A 4-column fluid grid with 16px side margins. 
- **Spacing Rhythm:** Based on an 8px linear scale. Large vertical gaps (80px+) are encouraged between major sections (e.g., Service List to Contact Form) to maintain the minimalist, high-end automotive feel.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Ambient Shadows**.

- **Shadows:** Use extremely soft, large-radius shadows (e.g., `y-offset: 10px, blur: 30px, opacity: 0.05`) to lift cards off the white background without creating visual clutter.
- **Layering:** Use the Very Light Green (#D8EFD2) for "inset" sections or background containers that need to hold multiple pieces of content (like a parts catalog grid).
- **Interactive Depth:** On hover, buttons should subtly increase their shadow spread rather than changing color significantly, mimicking a physical press.

## Shapes
The design system uses a **Rounded** (Level 2) logic, but leans into "extra-large" radius for primary components to feel friendly and modern.

- **Buttons:** Use `rounded-xl` (1.5rem / 24px) to create a approachable, modern "pill-lite" appearance.
- **Cards & Inputs:** Use `rounded-lg` (1rem / 16px) for a structured yet soft layout.
- **Icons:** Use a 2px stroke weight with rounded terminals to match the typography's geometric nature.

## Components
- **Buttons:** Primary buttons are Solid Green (#6CBF4A) with White text. Secondary buttons use a Green outline with 2px width.
- **Cards:** White backgrounds with a subtle 1px border in #D8EFD2 and an ambient shadow. Headers within cards should use the Light Green surface.
- **Input Fields:** 16px padding with a #4A4A4A border that turns Primary Green on focus. Labels should always be visible above the field in `label-md` style.
- **Chips/Status:** Use for vehicle status (e.g., "Hybrid System OK"). These should have a background of #D8EFD2 and text of #6CBF4A for a "monochromatic" look.
- **Icons:** High-tech iconography. Use symbols for lightning bolts (charging), circuitry, car silhouettes with battery icons, and wrenches. All icons should be rendered in the primary color or white depending on the background.
- **Data Tables:** For parts and pricing, use clean horizontal lines only. No vertical borders. Every second row should have a #D8EFD2 background for readability.