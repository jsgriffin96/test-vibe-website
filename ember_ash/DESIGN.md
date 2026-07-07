---
name: Ember & Ash
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e7bdb2'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ad887e'
  outline-variant: '#5d4038'
  surface-tint: '#ffb5a0'
  primary: '#ffb5a0'
  on-primary: '#601400'
  primary-container: '#ff5625'
  on-primary-container: '#541100'
  inverse-primary: '#b12d00'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#a5c8ff'
  on-tertiary: '#00315e'
  tertiary-container: '#2592ff'
  on-tertiary-container: '#002a53'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#872000'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#a5c8ff'
  on-tertiary-fixed: '#001c3a'
  on-tertiary-fixed-variant: '#004785'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
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
  container-margin: 5vw
  gutter: 24px
---

## Brand & Style
This design system embodies the tension between raw, rebellious energy and meticulous, small-batch craftsmanship. The brand personality is direct, intense, and unapologetically independent. 

The visual style merges **Minimalism** with **High-Contrast Bold** elements. We utilize expansive dark space to allow the "ember" accents to vibrate with intensity. To reflect the "handmade" nature of the product, we introduce subtle tactile qualities—specifically through film grain textures and high-quality photography—while maintaining a precision-engineered UI. The emotional response should be one of intrigue and perceived premium quality: it is the "black label" of hot sauces.

## Colors
The palette is rooted in the physical elements of a fire.
- **Ash (Neutral):** The deep charcoal `#121212` serves as the canvas, providing a moody, immersive environment.
- **Ember (Primary):** The fiery orange-red `#FF4500` is used surgically for calls to action, highlights, and critical brand moments. It represents the heat.
- **Bone (Secondary):** Crisp `#FFFFFF` is used for high-readability typography and icons, ensuring the "rebellious" aesthetic remains accessible.
- **Char (Accent):** A slightly lighter grey `#1A1A1A` is used for container surfaces and input fields to create subtle depth against the background.

## Typography
The typography is designed for impact and clarity. **Sora** is the voice of the brand—bold, geometric, and assertive. It should be used for all headlines with tight letter-spacing to create a "dense" visual weight.

**Hanken Grotesk** provides a clean, contemporary contrast for body copy and UI labels. It offers exceptional legibility at small sizes, ensuring that ingredient lists and technical details are easy to digest. Use uppercase styling for labels to lean into the "industrial/batch" aesthetic.

## Layout & Spacing
The layout follows a **Fluid Grid** system with extreme margins to create a high-end, editorial feel. 

- **Desktop:** 12-column grid with a `5vw` safe margin on both sides. Use `xl` spacing (80px) between major sections to emphasize the premium whitespace.
- **Tablet:** 8-column grid with `32px` margins.
- **Mobile:** 4-column grid with `20px` margins. 

Layouts should favor asymmetrical compositions—for example, placing a product image spanning 7 columns and text spanning the remaining 5, rather than perfectly centered blocks.

## Elevation & Depth
In this dark UI, we avoid traditional shadows which can feel muddy. Instead, we use **Tonal Layers** and **Subtle Grain**.

- **Level 0 (Background):** Deepest `#121212` with a 2% opacity noise/grain overlay to give a paper-like texture.
- **Level 1 (Containers):** Surfaces use `#1A1A1A`. 
- **Level 2 (Active States):** Instead of rising higher in "space," elements highlight through color saturation (turning `#FF4500`) or thin `1px` Bone-colored outlines.
- **Glassmorphism:** Use only for sticky navigation bars or overlays—`backdrop-filter: blur(20px)` with a `10%` white tint to maintain visibility without breaking the dark aesthetic.

## Shapes
We use **Level 2 (Rounded)** shapes. This provides a `0.5rem (8px)` base radius for most elements. This specific level of roundedness is critical: it’s enough to feel finished and "designed" (premium), but not so much that it feels "bubbly" or "soft." Larger elements like cards or modal containers scale up to `1.5rem (24px)` to maintain visual harmony.

## Components
- **Buttons:** Primary buttons are high-weight, filled with `#FF4500` and black text. They use `rounded-lg` (16px) corners and significant horizontal padding. Hover states should invert colors or shift to a slightly brighter orange.
- **Cards:** Product cards use the `#1A1A1A` surface with no border. The product image should "break" the container or sit on top with a transparent background to create depth.
- **Chips:** Used for heat levels (e.g., "Scoville: 50,000"). These should have a `1px` Bone outline and uppercase `label-sm` typography.
- **Input Fields:** Dark backgrounds with a `1px` stroke of `#333333`. Upon focus, the stroke should change to `#FF4500`.
- **Lists:** Ingredient or flavor profile lists should be separated by thin, low-opacity Bone dividers (`rgba(255,255,255,0.1)`).
- **Featured Component (The "Heat Meter"):** A custom horizontal bar component that uses a gradient from Ash to Ember to visually represent the spice level of a product.