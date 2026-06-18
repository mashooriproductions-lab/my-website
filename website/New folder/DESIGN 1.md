---
name: Cosmic Portfolio System
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#383939'
  surface-container-lowest: '#0d0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2a'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c6'
  primary: '#e2e2e2'
  on-primary: '#2f3131'
  primary-container: '#c6c6c6'
  on-primary-container: '#515253'
  inverse-primary: '#5d5e5f'
  secondary: '#bcc3ff'
  on-secondary: '#252c5e'
  secondary-container: '#3e4578'
  on-secondary-container: '#adb5f0'
  tertiary: '#ffd9dd'
  on-tertiary: '#52202a'
  tertiary-container: '#ffb2bd'
  on-tertiary-container: '#7b414b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e3e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#464747'
  secondary-fixed: '#dfe0ff'
  secondary-fixed-dim: '#bcc3ff'
  on-secondary-fixed: '#0e1648'
  on-secondary-fixed-variant: '#3b4376'
  tertiary-fixed: '#ffd9dd'
  tertiary-fixed-dim: '#ffb2bd'
  on-tertiary-fixed: '#380b16'
  on-tertiary-fixed-variant: '#6d3640'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
  void-black: '#0c0f0f'
  starlight-white: '#e2e2e2'
  cosmic-blue: '#0033fe'
  nebula-pink: '#e7005c'
  deep-space: '#001a97'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1440px
  stack-xs: 0.25rem
  stack-sm: 0.75rem
  stack-md: 1.5rem
  stack-lg: 3rem
  stack-xl: 5rem
  gutter: 1.5rem
  margin-desktop: 5rem
  margin-mobile: 1.25rem
---

## Brand & Style

The design system is rooted in a **Cinematic Dark Mode** aesthetic, evoking the vastness of space through a "Cosmic" metaphor. It is designed for high-end creative portfolios, specifically catering to industries where motion, technical precision, and immersive storytelling are paramount.

### Design Style: Glassmorphism & Modern Noir
This design system utilizes **Glassmorphism** as its primary structural driver, layering semi-transparent surfaces with heavy backdrop blurs to create a sense of three-dimensional depth within a "void." The visual language is defined by:
- **Atmospheric Depth:** Large, soft radial glows (pink and blue) acting as "nebulas" behind content.
- **Precision Detailing:** Ultra-thin "rim light" borders and high-contrast typography that mimic high-tech instrumentation.
- **Interactive Vibe:** The UI feels alive through a "Flashlight Cursor" effect and haptic-inspired motion, transforming a static page into an exploratory experience.
- **Futuristic Professionalism:** A balance of heavy, bold headings with neutral, utilitarian body text to convey both creative impact and technical reliability.

## Colors

The palette is centered on a high-contrast dark theme where the background is not a pure black, but a deep charcoal (`#121414`), allowing for richer depth when layering translucent surfaces.

- **Primary & Neutrals:** Grayscale tones are used for structural clarity. `primary` serves as the functional highlight, while `starlight-white` ensures maximum readability for body content.
- **Accents:** `secondary` (Soft Blue) and `tertiary` (Soft Pink) are used for interactive states and status indicators. 
- **Functional Glows:** `cosmic-blue` and `nebula-pink` are reserved for "power" elements like primary call-to-actions and backdrop blurs, creating the signature cosmic glow.
- **Surface Tiers:** Use `void-black` for the lowest levels (footers) and incremental steps like `#1e2020` for standard card containers to establish visual hierarchy without shadows.

## Typography

The typographic strategy relies on a "High-Low" pairing. **Montserrat** provides a heavy, geometric presence for titles, suggesting cinematic impact. **Inter** handles the functional heavy lifting, ensuring clarity across data-dense labels and long-form body text.

- **Headlines:** Should always use Montserrat. For hero sections, use `display-lg` with tight letter spacing for a modern, compressed look.
- **Text Shadows:** For critical headlines, a subtle `text-glow` using `secondary` at low opacity can be applied to enhance the "light-emissive" feel of the UI.
- **Body:** Inter is the workhorse. Maintain a generous `1.6` line height to ensure readability against the dark background.
- **Labels:** Use all-caps or increased letter spacing for `label-md` when used in buttons or tags to distinguish them from standard body text.

## Layout & Spacing

This design system follows a **Fixed Grid** approach for desktop, centering content within a `1440px` max-width container to maintain cinematic focus.

- **Rhythm:** An 8px base unit drives all spacing. Vertical "stacks" should be used to create clear separation between content groups (e.g., `stack-md` for title-to-body, `stack-xl` for section-to-section).
- **Responsive Behavior:** 
    - **Desktop:** Employs a 12-column grid with `5rem` (80px) side margins and `1.5rem` (24px) gutters.
    - **Mobile:** Shifts to a fluid single-column layout with `1.25rem` (20px) side margins.
- **Reflow Rules:** Large display headings must scale down to their mobile variants (`display-lg-mobile`) to prevent excessive word-breaking. 
- **Padding:** Containers (Cards/Modals) should use `stack-lg` internal padding to emphasize the "Glass" effect and prevent content from feeling cramped against the borders.

## Elevation & Depth

In this system, depth is communicated through **translucency and luminosity** rather than traditional drop shadows.

- **Layering:** 
    - The lowest level is the `background`. 
    - Components sit on `glass-panel` surfaces: `rgba(255, 255, 255, 0.03)` with a `20px` backdrop blur.
- **The "Rim Light" Effect:** Elevated containers must feature a `1px` top border with a linear gradient (white at 10% to transparent) to simulate light hitting the top edge of a physical object.
- **Glows:** 
    - **Backdrop Glows:** Use large, absolute-positioned containers with `blur(150px)` in the secondary/tertiary colors behind key content.
    - **Interactive Shadows:** On hover, elements should emit a blue glow (`rgba(0, 51, 255, 0.3)`) with a 30px spread, creating a haptic "light-up" sensation.
- **The Flashlight:** A global radial gradient follows the cursor, subtly illuminating surfaces at `0.05` opacity to add a layer of interactive discoverability.

## Shapes

The shape language is **Precision-Geometric**. Corners are kept sharp or only slightly softened to maintain a technical, "engineered" aesthetic.

- **Default:** A tight `2px` (0.125rem) radius for most UI controls and inputs.
- **Large Components:** Portfolio cards and major containers use `8px` (0.5rem) to provide a subtle distinction from the background grid.
- **Pills:** Interactive tags and specific secondary buttons use a `12px` (0.75rem) radius. Avoid fully circular "pill" shapes for primary CTAs to keep the design feeling grounded and architectural.

## Components

### Buttons
- **Primary (Cosmic):** Features a gradient from `nebula-pink` to `deep-space`. On hover, scale by `1.05` and transition the shadow to a magenta glow.
- **Secondary (Glass):** Clear background with a `1px` white border at `0.1` opacity. Text uses `primary` color.

### Portfolio Cards
- **Structure:** `glass-panel` background with `8px` radius. 
- **Interaction:** On hover, apply a haptic bounce (`cubic-bezier(0.175, 0.885, 0.32, 1.275)`). Image content inside the card should zoom slightly (`scale(1.1)`) over 700ms.
- **Border:** Must include the "card-highlight" top-rim gradient.

### Input Fields & Controls
- **Fields:** Dark background (`void-black`) with a 1px `outline` border. On focus, the border color shifts to `secondary`.
- **Chips/Tags:** Small `label-sm` text on a pill-shaped glass background.

### Navigation
- **Top Bar:** Fixed position with a `blur(20px)` glass effect. Active links are indicated by a `border-b-2` in the `primary` color.
- **Logo:** Displayed in `headline-md` weight for immediate brand recognition.

### Interaction Details
- **Text Reveal:** When sections enter the viewport, text should animate from `Opacity: 0 / Blur: 10px / TranslateY: 20px` to their default state using a `0.05s` stagger per character.