---
name: Architectural Precision
colors:
  surface: '#fbf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#444748'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f3f1ec'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e3e2e2'
  on-secondary-container: '#646464'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1e1b15'
  on-tertiary-container: '#89837a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e9e1d7'
  tertiary-fixed-dim: '#cdc5bb'
  on-tertiary-fixed: '#1e1b15'
  on-tertiary-fixed-variant: '#4a463f'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 120px
    fontWeight: '700'
    lineHeight: 110px
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  quote:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 36px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 160px
---

## Brand & Style

The brand personality is authoritative, sophisticated, and spatial. It targets a high-end demographic of investors, architects, and luxury homeowners who value structural integrity and avant-garde aesthetics. The emotional response should be one of "quiet luxury"—calm, expansive, and meticulously curated.

The design style is a hybrid of **Minimalism** and **Modern Brutalism**. It leverages high-contrast typography, a restrained palette of materials (Concrete, Graphite, Stone), and a layout philosophy that treats the digital screen as a physical floor plan. Expect generous negative space that acts as "breathing room" between monolithic content blocks, emphasizing quality over quantity.

## Colors

The palette is derived from raw architectural materials. 

- **Concrete White (#F3F1EC):** The primary canvas. It provides a warmer, more organic feel than pure white, mimicking gallery walls.
- **Graphite Black (#111111):** Used for structural elements, massive headings, and primary calls to action. It represents the "ink" of an architectural blueprint.
- **Architectural Gray (#8B8B8B):** Reserved for secondary information, metadata, and grid lines.
- **Soft Stone (#C9C2B8):** A subtle mid-tone for dividers, borders, and disabled states.
- **Deep Charcoal (#1A1A1A):** Used for immersive, dark-mode sections or "monolithic" components that need to recede or ground the layout.

## Typography

Typography is the "structural steel" of this design system. 

**Hanken Grotesk** serves as the display face, chosen for its sharp, contemporary geometry and high impact. It should be used at massive scales to create visual anchors. **Inter** is used for body copy to ensure maximum legibility for property descriptions and technical specs. **JetBrains Mono** is introduced for labels and technical data, providing a "blueprint" or "drafting" feel to metadata.

Always prioritize tight tracking (letter-spacing) for large headlines and wide tracking for mono-labels.

## Layout & Spacing

This design system uses a **Fixed Grid** model (12 columns) for content, but allows "cinematic" media containers to bleed to the edges of the viewport.

The spacing rhythm is intentionally "Brutalist"—meaning it is unapologetically large. Section gaps are expansive (160px+) to ensure that each architectural project feels like its own independent exhibition. 

**Breakpoints:**
- **Desktop:** 1440px+ (12 columns, 64px margins)
- **Tablet:** 768px - 1439px (8 columns, 40px margins)
- **Mobile:** < 767px (4 columns, 20px margins)

Internal component spacing follows a strict 8px baseline grid to maintain mathematical precision.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Glassmorphism**, avoiding traditional shadows. 

- **Level 0 (Base):** Concrete White (#F3F1EC) background.
- **Level 1 (Cards):** Soft Stone (#C9C2B8) outlines with no fill, or slightly darker Concrete tones to create a subtle stack.
- **Level 2 (Floating Navigation):** A frosted glass effect (Backdrop Blur: 20px) with a 1px Graphite Black stroke at 10% opacity. 
- **Level 3 (Cinematic Modals):** High-contrast Deep Charcoal (#1A1A1A) overlays that completely occupy the z-axis, creating a dramatic focus on imagery.

Avoid "fuzzy" shadows. Use 1px solid strokes in Architectural Gray to define boundaries where necessary.

## Shapes

The shape language is **Sharp (0)**. 

True to modern architectural principles, there are no rounded corners. Every button, input, card, and image container must have 0px border-radius. This reinforces the "monolithic" and "structural" feel of the design system. Interactive elements are defined by their borders and typography rather than their corner treatment.

## Components

### Buttons
Primary buttons are solid Graphite Black with white JetBrains Mono text in all caps. Secondary buttons use a 1px border of Graphite Black with no fill. Hover states should involve a full color invert or a subtle shift to Architectural Gray.

### Navigation
The navigation is a floating "monolith." It should be centered at the bottom or top of the viewport, using a glassmorphic background. Links are JetBrains Mono, separated by thin vertical 1px pipes.

### Cards
Real estate cards use "Layered Depth." The image is the primary focus, with metadata (price, location) overlaid in a small Graphite Black box at the bottom-left or top-right, using sharp edges.

### Input Fields
Inputs are minimal: a single 1px bottom border in Architectural Gray. The label floats above in JetBrains Mono caps. On focus, the border transitions to Graphite Black.

### Cinematic Containers
Full-width, high-aspect-ratio containers for architectural photography. These should have no padding and should act as the "foundation" for massive Display-XL typography to overlay, using white text for contrast against dark imagery.