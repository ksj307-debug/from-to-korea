---
name: Premium Private Seoul
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
  on-surface-variant: '#43474e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#050606'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1f1f'
  on-tertiary-container: '#858687'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  button:
    fontFamily: Manrope
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
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-xl: 80px
  stack-md: 40px
  stack-sm: 16px
---

## Brand & Style

The design system is engineered to evoke a sense of quiet luxury, exclusivity, and profound trust. Targeting high-net-worth travelers and discerning explorers, the visual language moves away from the cluttered aesthetic of mass tourism, instead embracing a **Minimalist** and **Modern** approach. 

The emotional response should be one of "effortless discovery." By utilizing expansive white space and a disciplined editorial layout, the UI mirrors the curated nature of a private tour. Every element is intentional, reducing cognitive load to ensure the user feels cared for and guided, even before their journey begins.

## Colors

The palette is anchored by **Deep Navy**, representing the stability and depth of a premium service. **Clean White** serves as the primary canvas, ensuring a breathable and high-end feel.

- **Primary (Deep Navy):** Used for navigation, primary actions, and authoritative text.
- **Secondary (Gold Accents):** Reserved for subtle highlights, such as rating stars or "Premium" badges, to denote luxury without over-decorating.
- **Surface (Soft Gray):** Used for subtle section nesting and background layers to prevent stark transitions.
- **Text (Off-Black/Navy):** Pure black is avoided to maintain a softer, more sophisticated reading experience.

## Typography

This design system employs a sophisticated pairing of **Noto Serif** for headings and **Manrope** for functional text. 

Noto Serif provides an authoritative, literary quality that reflects the storytelling aspect of a guided tour. Manrope, a geometric sans-serif, provides the modern, clean clarity required for transactional details and logistics. Headlines should use tight letter-spacing for a high-fashion editorial feel, while labels utilize uppercase tracking to denote structural hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain a centered, gallery-like experience. 

- **Desktop:** A 12-column grid with generous margins (64px) ensures content feels exclusive and uncrowded.
- **Mobile:** Transition to a single-column fluid layout with 20px side margins.
- **Vertical Rhythm:** Large vertical gaps (stack-xl) are used between major sections to emphasize the "Personal" nature of the service, allowing photography to shine without immediate competition from text blocks.

## Elevation & Depth

To maintain a minimalist profile, the design system avoids heavy shadows. Instead, it utilizes **Tonal Layers** and **Soft Ambient Shadows**.

1.  **Low Elevation:** Primary cards use a 1px border in a very light gray (#E0E0E0) or a soft shadow (0px 4px 20px rgba(0, 0, 0, 0.04)) to barely lift from the background.
2.  **High Elevation:** Modals or mobile navigation menus use a more pronounced, diffused shadow to create focus.
3.  **Depth via Photography:** Depth is primarily created through high-quality imagery with natural depth-of-field, rather than UI-driven skeuomorphism.

## Shapes

The design system adopts a **Soft (1)** shape language. The subtle 0.25rem (4px) radius on buttons and input fields provides a modern touch that is friendlier than sharp corners but more professional than highly rounded "bubbly" shapes. This balance reflects the "Contemporary Seoul" aesthetic—where traditional structure meets modern innovation.

## Components

### Buttons
- **Primary:** Deep Navy background, White text, 4px radius. No gradients.
- **Secondary:** Transparent with a 1px Navy border.
- **Hover States:** Subtle opacity shift (90%) or a slight lift; avoid dramatic color changes.

### Cards (Tour Listings)
- Clean White backgrounds with 1px Soft Gray borders.
- Top-heavy layout: 60% high-resolution image, 40% text content.
- Typography within cards should be highly hierarchical: Noto Serif for the tour title, Manrope for the price and duration.

### Input Fields
- Underlined or thinly outlined in Soft Gray.
- Focus state: Border transitions to Deep Navy with no glow.
- Labels: Use `label-caps` for a professional, form-like feel.

### Refined Icons
- Use thin-stroke (light weight) icons. 
- Icons should always be accompanied by labels or used sparingly to maintain the clean aesthetic.

### Image Treatment
- All photography should feature a consistent color grade—slightly desaturated with deep blacks to match the Navy brand color. Use "Hero" sections with full-bleed imagery to create an immersive introduction.