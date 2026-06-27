---
name: Atelier de Parfum
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c9c6c5'
  secondary: '#5e5f5c'
  on-secondary: '#ffffff'
  secondary-container: '#e0e0dc'
  on-secondary-container: '#626360'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#241a00'
  on-tertiary-container: '#a08000'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e3e2df'
  secondary-fixed-dim: '#c7c7c3'
  on-secondary-fixed: '#1b1c1a'
  on-secondary-fixed-variant: '#464744'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-xl:
    fontFamily: Playfair Display
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 90px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
  caption:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
spacing:
  unit: 8px
  container-max: 1440px
  margin-desktop: 80px
  margin-mobile: 24px
  gutter: 32px
  section-gap: 160px
---

## Brand & Style

This design system is built upon the principles of **High-Luxury Minimalism** and **Editorial Elegance**. It seeks to evoke an emotional response of exclusivity, sensory sophistication, and timelessness. The aesthetic is inspired by high-fashion archives and artisanal perfumery, where the "scent" is represented through vast negative space and structured, rhythmic layouts.

The visual direction avoids the clutter of traditional e-commerce, opting instead for a "Gallery" approach. Every element is treated as an art object. The brand personality is quiet but commanding—relying on the quality of the imagery and the precision of the typography rather than decorative flourishes.

## Colors

The palette is rooted in a high-contrast relationship between **Ivory (#F9F8F4)** and **Deep Black (#0A0A0A)**. Ivory serves as the primary canvas, providing a warmer, more organic feel than pure white, reminiscent of high-quality vellum or silk.

- **Primary (Deep Black):** Used for all critical text, iconography, and structural borders. It represents the ink of a fragrance house.
- **Secondary (Ivory):** The foundational surface color. It creates an atmosphere of calm and expansive luxury.
- **Accent (Satin Gold):** Used sparingly for interactive highlights, subtle notifications, or "Special Edition" markers.
- **Functional Grays:** Reserved for secondary information and disabled states, ensuring the primary contrast remains undisturbed.

## Typography

Typography in this design system is used to create a clear hierarchy between "The Story" and "The Detail."

**Playfair Display** is the editorial voice. It should be used for large, expressive headlines and product names. High-end layouts should leverage its italic variant to emphasize sensory descriptions.

**Montserrat** provides the functional structure. It is used for body copy, pricing, and navigation. To maintain a premium feel, body text uses a "Light" (300) or "Regular" (400) weight with slightly increased tracking (letter-spacing) to ensure the text "breathes."

Labels and interactive small caps are tracked out heavily (0.15em) to mimic the labeling found on apothecary bottles.

## Layout & Spacing

This design system employs a **Fixed Grid with Asymmetric Refinement**. While a 12-column grid provides the underlying structure, content is often offset to create an editorial, magazine-like flow.

- **Negative Space:** Use generous padding. Section-to-section transitions should feel like turning a page in a high-fashion periodical.
- **Asymmetry:** On desktop, hero images should rarely span the full width. Aligning text to the 2nd column while an image starts at the 5th column creates a sophisticated visual tension.
- **Breakpoints:**
  - **Desktop (1200px+):** 12 columns, 80px margins.
  - **Tablet (768px - 1199px):** 8 columns, 40px margins.
  - **Mobile (Up to 767px):** 4 columns, 24px margins. Layout becomes linear, but maintains vertical white space between blocks.

## Elevation & Depth

To maintain a minimalist and "flat luxury" aesthetic, this design system avoids traditional shadows. Depth is created through **Tonal Layering** and **Ghost Outlines**.

- **Surfaces:** All primary containers use the Ivory background. When a secondary surface is needed (e.g., a search drawer or cart), use a slightly darker "Paper" tint or the Deep Black for high-impact contrast.
- **Outlines:** Use 1px solid lines in Deep Black or a very faint gold for separation. These lines should feel like hairline strokes from a drafting pen.
- **Overlays:** For modals or menus, use a high-density background blur (30px+) with a 90% opacity Ivory tint to maintain the "frosted glass" feel of a perfume bottle.

## Shapes

The shape language is strictly **Sharp (0px)**. 

Sharp corners convey a sense of architectural precision and professional authority. All buttons, image containers, input fields, and dividers must utilize right angles. The only organic shapes permitted within the UI are the product forms (bottles) themselves, which stand out more effectively against a rigid, geometric frame.

## Components

### Buttons
Primary buttons are Deep Black with White text, using `label-caps` typography. Secondary buttons utilize a 1px Black border with a transparent background. Hover effects must be "Inverted": the border button fills with black, and the solid button transitions to a Gold stroke.

### Input Fields
Inputs are minimalist, consisting only of a 1px bottom border. Labels use `label-caps` and sit above the line. Error states are indicated by a shift to a deep garnet color, avoiding bright "web-standard" reds to maintain the palette's sophistication.

### Cards
Product cards are borderless. The focus is on a high-resolution, cut-out bottle shot against the Ivory background. Price and name are center-aligned beneath the image using `headline-sm` and `body-md`.

### Navigation
The header is tall (100px+) and remains sticky. Links use `label-caps` with a 1px underline that appears on hover, animating from the center outward.

### Chips & Tags
Used for scent notes (e.g., "Oud," "Bergamot"). These are small, sharp-edged rectangles with a 1px light gray border and `caption` typography.