---
name: Luminal Noir
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#909191'
  on-tertiary-container: '#282a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 84px
    fontWeight: '800'
    lineHeight: 90px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style
The design system embodies a **Dark Luxury** aesthetic, tailored for a high-end creative agency that blends technical precision with artistic flair. The brand personality is visionary, confident, and sophisticated, targeting industry leaders and tech-forward startups.

The visual style is a fusion of **Minimalism** and **Glassmorphism**, emphasizing depth through translucent layers and vibrant light leaks. It utilizes high-contrast typography and expansive whitespace to create an editorial, "Awwwards-winning" atmosphere. Highly interactive elements, subtle glows, and liquid-smooth transitions evoke a sense of futuristic craftsmanship.

## Colors
The palette is rooted in a "Deep Black" foundation to provide maximum contrast for neon-inspired accents.
- **Background:** Primary background is `#0a0a0a`. Surface containers use `#141414` with variable opacity.
- **Accents:** Vibrant Purple (`#8b5cf6`) and Electric Blue (`#3b82f6`) are used for primary actions, data visualization, and decorative glows.
- **Gradients:** Brand elements should frequently utilize a linear gradient from Electric Blue to Vibrant Purple at a 135-degree angle.
- **Text:** Primary text is pure white (`#ffffff`) for maximum legibility. Secondary text uses a muted grey (`#a1a1aa`).

## Typography
The typography strategy relies on the tension between the expressive, geometric forms of **Syne** and the ultra-clean, modern legibility of **Plus Jakarta Sans**. 

- **Display & Headlines:** Use Syne for high-impact messaging. For "Awwwards-style" layouts, use extra-bold weights with tight letter-spacing.
- **Body Text:** Plus Jakarta Sans provides a friendly yet professional reading experience.
- **Technical Accents:** Geist (monospaced) is used for labels, metadata, and navigational elements to reinforce the futuristic, developer-adjacent aesthetic.

## Layout & Spacing
The design system utilizes a **Fluid Grid** model to maintain a cinematic feel across all viewports. 
- **Grid:** A 12-column grid on desktop, 8-column on tablet, and 4-column on mobile.
- **Rhythm:** Spacing follows an 8px base unit. Large-scale sections should favor extreme vertical padding (160px+) to allow the content to "breathe" and create a premium editorial feel.
- **Safety:** Use wide horizontal margins (80px) on desktop to center focus on high-fidelity imagery and typography.

## Elevation & Depth
Depth is created through **Glassmorphism** rather than traditional shadows.
- **Surfaces:** Use semi-transparent backgrounds (`rgba(255, 255, 255, 0.05)`) with a `backdrop-filter: blur(20px)`.
- **Borders:** "Gradient Borders" are a signature element. Use a 1px border with a subtle gradient from white (10% opacity) to white (2% opacity) to define edges without adding visual weight.
- **Glows:** Higher elevation levels are indicated by an underlying "radial-gradient" glow in brand colors, appearing softly behind the element to simulate a neon light source.

## Shapes
Shapes are modern and refined. The standard corner radius is **8px (0.5rem)** for most UI components.
- **Cards & Modals:** Use `rounded-xl` (24px) to create a softer, more inviting container for complex content.
- **Buttons:** Interactive elements use a slightly more aggressive `rounded-lg` (16px) or full pill-shape for "Call to Action" buttons to distinguish them from structural containers.

## Components
- **Buttons:** Primary buttons feature a solid gradient fill (Blue to Purple) with a slight outer glow on hover. Secondary buttons use the "Glassmorphism" effect with a thin white border.
- **Chips/Tags:** Small, Geist-font labels with a low-opacity background and 1px solid border.
- **Input Fields:** Minimalist design—only a bottom border that animates into a brand gradient on focus.
- **Cards:** Feature `backdrop-filter` and `gradient-borders`. On hover, the internal glow intensity should increase by 20%.
- **Lists:** Clean separators using `rgba(255, 255, 255, 0.1)`. Interactive list items should have a horizontal slide-in effect for the text on hover.
- **Interactive Cursor:** A custom-styled circular cursor that expands and changes color when hovering over clickable elements.