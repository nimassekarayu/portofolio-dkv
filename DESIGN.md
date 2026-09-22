---
name: Editorial Portfolio
colors:
  surface: '#FFF9F1'
  surface-dim: '#e8d6d4'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#fceae8'
  surface-container-high: '#f6e4e2'
  surface-container-highest: '#f0dfdc'
  on-surface: '#221918'
  on-surface-variant: '#554240'
  inverse-surface: '#382e2d'
  inverse-on-surface: '#ffedea'
  outline: '#88726f'
  outline-variant: '#dbc0bd'
  surface-tint: '#9b433c'
  primary: '#250001'
  on-primary: '#ffffff'
  primary-container: '#4b0707'
  on-primary-container: '#d16d64'
  inverse-primary: '#ffb4ab'
  secondary: '#9e4039'
  on-secondary: '#ffffff'
  secondary-container: '#fd8a7f'
  on-secondary-container: '#75221e'
  tertiary: '#160902'
  on-tertiary: '#ffffff'
  tertiary-container: '#2f1f13'
  on-tertiary-container: '#9d8575'
  error: '#EA4335'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#400103'
  on-primary-fixed-variant: '#7c2c26'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#7f2924'
  tertiary-fixed: '#faddca'
  tertiary-fixed-dim: '#ddc1af'
  on-tertiary-fixed: '#27180d'
  on-tertiary-fixed-variant: '#564335'
  background: '#F4EBDD'
  on-background: '#221918'
  surface-variant: '#f0dfdc'
  text-primary: '#211614'
  text-secondary: '#6D5B54'
  border: '#E7DDD3'
  success: '#34A853'
  warning: '#F4B400'
typography:
  display-xl:
    fontFamily: Playfair Display
    fontSize: 108px
    fontWeight: '700'
    lineHeight: 108px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 45px
    fontWeight: '700'
    lineHeight: 52px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 25.6px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  max-width: 1280px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 96px
---

# Design System: Graphic Designer Portfolio

Premium editorial-style portfolio website for showcasing graphic design projects.

## Visual Identity
- **Brand Personality**: Premium, Editorial, Elegant, Creative, Modern
- **Inspiration**: Behance, Awwwards, Editorial Magazine, Swiss Design
- **Design Rules**:
    - Keep oversized editorial typography.
    - Use warm neutral colors.
    - Maintain generous whitespace.
    - Use flat design only.
    - Avoid unnecessary decorative elements.
    - Photography should remain the main visual focus.
    - Keep layouts clean and balanced.
    - Never use glassmorphism or neumorphism.

## Colors
- **Primary**: #4B0707 (Deep Burgundy)
- **Secondary**: #7A2621
- **Tertiary**: #B79D8C
- **Background**: #F4EBDD
- **Surface**: #FFF9F1
- **Text Primary**: #211614
- **Text Secondary**: #6D5B54
- **Border**: #E7DDD3
- **Success**: #34A853
- **Warning**: #F4B400
- **Error**: #EA4335

## Typography
- **Display (H1)**: Playfair Display, 108px (6.8rem), Bold (700), Line Height 1, Letter Spacing -0.03em
- **Heading (H2)**: Playfair Display, 45px (2.8rem), Bold (700), Line Height 1.15
- **Body**: Inter, 16px (1rem), Regular (400), Line Height 1.6
- **Caption**: Inter, 14px (0.875rem), Medium (500)

## Layout & Spacing
- **Grid**: 12-column, 1280px Max Width
- **Container Padding**: 80px
- **Section Spacing**: 96px
- **Border Radius**: 
    - Card: 0px (Sharp edges for editorial look)
    - Button: 8px
    - Input: 8px
    - Badge: 9999px
- **Elevation**: Flat design, no shadows.

## Components & Motion
- **Hero**: Split layout, portrait image, oversized editorial typography.
- **About**: Two-column layout with icon badge row for skills.
- **Gallery**: Responsive grid (3 columns desktop), hover scale 1.02 with image zoom and dark overlay.
- **Motion**: 150ms duration, ease-out transition.

## Accessibility
- WCAG AA compliant.
- Minimum contrast 4.5:1.
- Semantic HTML.
- Touch target 44x44.