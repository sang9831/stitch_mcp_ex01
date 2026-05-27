---
name: Citizens United
colors:
  surface: "#f9f9f9"
  surface-dim: "#dadada"
  surface-bright: "#f9f9f9"
  surface-container-lowest: "#ffffff"
  surface-container-low: "#f3f3f4"
  surface-container: "#eeeeee"
  surface-container-high: "#e8e8e8"
  surface-container-highest: "#e2e2e2"
  on-surface: "#1a1c1c"
  on-surface-variant: "#41474f"
  inverse-surface: "#2f3131"
  inverse-on-surface: "#f0f1f1"
  outline: "#717880"
  outline-variant: "#c0c7d0"
  surface-tint: "#176391"
  primary: "#176391"
  on-primary: "#ffffff"
  primary-container: "#6cabdd"
  on-primary-container: "#003e60"
  inverse-primary: "#90cdff"
  secondary: "#5f5e5e"
  on-secondary: "#ffffff"
  secondary-container: "#e2dfde"
  on-secondary-container: "#636262"
  tertiary: "#5d5f5f"
  on-tertiary: "#ffffff"
  tertiary-container: "#a4a5a5"
  on-tertiary-container: "#393b3b"
  error: "#ba1a1a"
  on-error: "#ffffff"
  error-container: "#ffdad6"
  on-error-container: "#93000a"
  primary-fixed: "#cbe6ff"
  primary-fixed-dim: "#90cdff"
  on-primary-fixed: "#001e31"
  on-primary-fixed-variant: "#004b72"
  secondary-fixed: "#e5e2e1"
  secondary-fixed-dim: "#c8c6c5"
  on-secondary-fixed: "#1b1c1c"
  on-secondary-fixed-variant: "#474746"
  tertiary-fixed: "#e2e2e2"
  tertiary-fixed-dim: "#c6c6c6"
  on-tertiary-fixed: "#1a1c1c"
  on-tertiary-fixed-variant: "#454747"
  background: "#f9f9f9"
  on-background: "#1a1c1c"
  surface-variant: "#e2e2e2"
typography:
  display-lg:
    fontFamily: Archivo Narrow
    fontSize: 72px
    fontWeight: "700"
    lineHeight: "1.1"
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Archivo Narrow
    fontSize: 48px
    fontWeight: "700"
    lineHeight: "1.2"
  headline-lg-mobile:
    fontFamily: Archivo Narrow
    fontSize: 32px
    fontWeight: "700"
    lineHeight: "1.2"
  headline-md:
    fontFamily: Archivo Narrow
    fontSize: 32px
    fontWeight: "600"
    lineHeight: "1.2"
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: "400"
    lineHeight: "1.6"
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: "400"
    lineHeight: "1.5"
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: "700"
    lineHeight: "1.2"
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: "500"
    lineHeight: "1.2"
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1440px
---

## Brand & Style

This design system captures the elite, high-performance essence of Manchester City FC. It balances a prestigious sporting heritage with a forward-thinking, digital-first aesthetic. The personality is confident, professional, and "Always Moving"—reflecting the fluidity of the modern game.

The design style is **Corporate / Modern** with a **High-Contrast** edge. It utilizes expansive whitespace to allow high-quality sports photography to breathe, paired with aggressive, rhythmic typography that feels urgent and impactful. The emotional response should be one of "Premium Accessibility"—elite performance made available to the global fan base.

## Colors

The palette is anchored by "City Blue," used as the primary catalyst for brand recognition and interactive elements. A deep Graphite Black (#222222) provides the structural weight and professional "anchor" for navigation and high-contrast typography. White is used extensively for clarity and modern minimalism.

A Neutral Silver (#ebebeb) acts as the tertiary tone, reserved for subtle UI boundaries, secondary backgrounds, and content containers. This shift toward a monochromatic supporting palette emphasizes a more technical, industrial "engineered" aesthetic compared to traditional celebratory gold. Use a logic of "Active Sky": primary actions take the Sky Blue, while core structural elements lean into the Graphite for maximum legibility.

## Typography

The typography system relies on a "Display vs. Utility" tension. **Archivo Narrow** acts as our headline workhorse, mimicking the condensed, powerful aesthetic of stadium wayfinding and kit lettering. It should be used for scores, player names, and major news headlines.

**Hanken Grotesk** provides a sharp, contemporary counterpoint for body copy, ensuring high readability for long-form articles and match reports. All labels and overlines should utilize uppercase Hanken Grotesk with slight tracking to maintain a premium, architectural feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop (12 columns) and a fluid 4-column model on mobile. A strict 8px spacing scale ensures rhythmic consistency.

Layouts should favor "Dynamic Asymmetry"—where imagery and text blocks overlap slightly to create a sense of movement. Use 24px gutters to allow for breathing room between dense data sets (like league tables or player stats). Section vertical padding should be generous (80px–120px on desktop) to distinguish between matchday content and commercial features.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. We avoid heavy skeuomorphism in favor of subtle depth that suggests a high-end digital interface.

- **Level 1 (Base):** White background.
- **Level 2 (Cards):** Neutral Silver surfaces (#ebebeb) or White surfaces with a very soft, diffused shadow (0px 4px 20px, 5% Graphite opacity).
- **Level 3 (Overlays):** Graphite Black modals or "Glass" blurring for video player controls, using a 20px backdrop blur to maintain focus on the pitch action.

Interactive elements should "lift" on hover, increasing shadow spread slightly to provide tactile feedback.

## Shapes

The shape language is **Soft (Level 1)**. Elements like buttons and cards use a 4px (0.25rem) base radius. This creates a professional, slightly technical look that feels precise rather than "bubbly."

For "Cityzens" exclusive content or youth-focused sections, the roundedness can be increased to `rounded-lg` (8px) for a friendlier tone, but the core product remains sharp and disciplined. Containers for player stats or data visualization should remain sharp-edged to reinforce the "performance data" aesthetic.

## Components

- **Buttons:** Primary buttons use a solid Sky Blue background with White text, uppercase labels. Secondary buttons use a Graphite Black outline. Ghost buttons are reserved for over-image placement.
- **Cards:** Matchday cards feature a 1px Graphite Black border at 10% opacity. Imagery should occupy the top 60% of the card with a subtle gradient overlay to ensure text legibility at the bottom.
- **Chips:** Used for "Live," "Tickets," or "Exclusive" tags. They should use a high-contrast background (Graphite for Live, Silver for secondary info) with 2px rounded corners.
- **Input Fields:** Minimalist with a bottom-border only in the default state, shifting to a full Graphite Black 2px border on focus.
- **Match Slider:** A custom component displaying upcoming fixtures. Use a split-pane design (Home vs. Away) with the club crests centered.
- **Lists:** Data lists (League Tables) use zebra-striping with the Neutral Silver (#ebebeb) at very low opacity to guide the eye across rows.
