---
name: Heritage Hearth
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#414844'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#7d562d'
  on-secondary: '#ffffff'
  secondary-container: '#ffca98'
  on-secondary-container: '#7a532a'
  tertiary: '#29261a'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f3c2e'
  on-tertiary-container: '#aba694'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffdcbd'
  secondary-fixed-dim: '#f0bd8b'
  on-secondary-fixed: '#2c1600'
  on-secondary-fixed-variant: '#623f18'
  tertiary-fixed: '#e8e2cf'
  tertiary-fixed-dim: '#ccc6b3'
  on-tertiary-fixed: '#1e1c10'
  on-tertiary-fixed-variant: '#4a4738'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e5e2e1'
  pilsner-green: '#083121'
  warm-wood: '#A67C52'
  paper-white: '#FAFAF9'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 56px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
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
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 80px
---

## Brand & Style
The design system is built upon the concept of "Modern Heritage." It seeks to bridge the gap between a traditional Czech guesthouse and a contemporary dining destination. The brand personality is warm, reliable, and authentic. 

The aesthetic is **Modern-Tactile**. It utilizes the cleanliness of minimalism—plenty of whitespace and structured grids—but warms it with organic textures and a palette inspired by Bohemian forests and traditional brewing. The target audience includes both locals seeking a dependable meal and travelers looking for a cozy, upscale rustic experience. The UI should feel substantial and grounded, avoiding the "floaty" nature of standard SaaS designs in favor of something that feels as permanent as a wooden table.

## Colors
This design system uses a palette grounded in nature and tradition. The **Primary Color** is a deep, forest green reminiscent of Pilsner brewing heritage, used for navigation, primary buttons, and brand-heavy sections. The **Secondary Color** is a warm, oaken tan used for accents, icons, and subtle highlights.

**Tertiary and Named Colors** provide the "paper" and "wood" feeling. We use a "Paper White" (#FAFAF9) instead of pure white to reduce eye strain and add a vintage, organic feel. High-contrast text uses a deep charcoal (#222222) rather than pure black to maintain a softer, premium look.

## Typography
The typography strategy pairings tradition with modern utility. 

**EB Garamond** is the primary display face. It conveys authority and history. It should be used for all major headings and menu item titles. For large display sizes, a tighter letter spacing and semi-bold weight should be applied to create a sophisticated, editorial feel.

**Hanken Grotesk** serves as the functional workhorse. It is a clean, contemporary sans-serif that ensures readability for descriptions, pricing, and booking forms. Labels and small metadata should use Hanken Grotesk in uppercase with slight letter spacing to create a distinct hierarchy against the serif headings.

## Layout & Spacing
This design system utilizes a **Fixed Grid** on desktop (1200px max width) to ensure a controlled, magazine-like reading experience. 

- **Desktop:** 12-column grid with 24px gutters.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px side margins.

A generous "section-gap" of 80px (scaling to 48px on mobile) ensures that the different offerings—Restaurant, Accommodation, History—feel distinct and uncrowded. Use card-based modules for the menu and room listings to encapsulate information clearly against the warm "Paper White" background.

## Elevation & Depth
Depth in this design system is achieved through **Tonal Layering** rather than heavy shadows. 

- **Level 0 (Base):** The Paper White background (#FAFAF9).
- **Level 1 (Cards/Surface):** White (#FFFFFF) surfaces with a very subtle, 1px border in a light wood tone or a 2% opacity forest green.
- **Level 2 (Interactive):** Elements that require focus (like booking modals) use a soft, diffused ambient shadow tinted with the primary green (#1B4332 at 10% opacity) to provide a "lifted" effect without feeling synthetic.
- **Overlays:** Use a subtle backdrop blur (glassmorphism) on navigation bars when scrolling to maintain context of the high-quality food photography beneath.

## Shapes
The shape language is **Soft (0.25rem)**. While modern, the design avoids the overly bubbly look of mobile apps. Small corner radii on cards and buttons mimic the slight softening of aged wood or stone, providing a comfortable feel while maintaining the structural integrity of the grid. 

Images, particularly in the hero section and gallery, should remain sharp (0px radius) or use very minimal softening to maintain a professional, architectural photography aesthetic.

## Components
- **Buttons:** Primary buttons are solid Forest Green with White text. Secondary buttons use a "Warm Wood" outline with serif text. All buttons should have a slight hover transition that deepens the color.
- **Menu Cards:** Use a clean white surface. The dish name is EB Garamond (Headline-sm), the price is Hanken Grotesk (Bold), and descriptions are Hanken Grotesk (Body-md). 
- **Input Fields:** Use a simple bottom-border style or a very light-filled box to keep the forms for room booking looking elegant and non-intrusive.
- **Chips/Badges:** Use for dietary requirements (e.g., "Vegetarian") or room features (e.g., "Free Wi-Fi"). These should be pill-shaped with the Secondary Tan color at a low opacity.
- **Booking Widget:** A floating or anchored card that uses the Primary Green for the "Check Availability" call-to-action, ensuring it is the most prominent element on the page.