---
name: Carnes del Rancho Visual System
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0a0a0a'
  on-primary-container: '#7b7979'
  inverse-primary: '#5f5e5e'
  secondary: '#ffb3b1'
  on-secondary: '#680011'
  secondary-container: '#881c25'
  on-secondary-container: '#ff9997'
  tertiary: '#e9c349'
  on-tertiary: '#3c2f00'
  tertiary-container: '#0e0900'
  on-tertiary-container: '#947600'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdad8'
  secondary-fixed-dim: '#ffb3b1'
  on-secondary-fixed: '#410007'
  on-secondary-fixed-variant: '#881c25'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
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
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
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
  gutter-sm: 16px
  gutter-md: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
This design system embodies the intersection of traditional craftsmanship and modern culinary luxury. The aesthetic is rooted in **Modern Minimalism with a Gourmet Editorial twist**, utilizing high-contrast visuals and cinematic spatial awareness to elevate meat-buying to a premium experience. 

The target audience is the discerning epicurean who values provenance, quality, and hygiene. The UI evokes a sense of "digital white-glove service"—clean, authoritative, and sophisticated. Every interface element should feel as intentional as a chef's knife stroke, balancing the raw, visceral nature of the product with an atmosphere of sterile, high-end elegance.

## Colors
The palette is dominated by **Obsidian Black (#0A0A0A)** to create a canvas of infinite depth, allowing the vibrant reds of fresh cuts to pop. **Dark Wine Red (#720917)** is used sparingly for primary actions and highlights, suggesting richness and bloodline heritage. 

**Metallic Gold (#D4AF37)** is reserved for high-value accents, certifications, and "Prime" tiering, signifying the gold standard of the ranch. Pure **White (#FFFFFF)** is used for high-readability typography and structural dividers to maintain a sense of clinical hygiene and modern clarity.

## Typography
The typographic hierarchy relies on a "Chiaroscuro" effect—dramatic contrast between the headline and the body. **Libre Caslon Text** provides a literary, established authority for headings, suggesting a legacy of quality. 

**Manrope** provides a technical, clean counterpoint for all functional text, ensuring that weights, prices, and cuts are legible at a glance. Use wide letter spacing for labels to enhance the premium, airy feel.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain a boutique, curated feel, preventing content from becoming over-extended. 

- **Desktop:** 12-column grid with a 1200px max-width container. 64px outer margins to create "breathing room."
- **Tablet:** 8-column grid with 32px margins.
- **Mobile:** 4-column grid with 20px margins.

Spacing is aggressive; use large vertical gaps (`section-gap`) between product categories to mimic the pace of a high-end gallery.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Subtle Outlines** rather than heavy shadows. 

1. **Base:** Pure #0A0A0A.
2. **Surface (Cards):** A slightly lifted #141414 with a 1px solid border in #262626.
3. **Overlays:** 10% opacity white frost for modals to maintain the "hygienic" feel without losing the dark theme.

Imagery should utilize **Cinematic Lighting**—deep shadows and high-key highlights on the product—making the meat appear sculptural and appetizing.

## Shapes
This design system uses **Soft (0.25rem)** roundedness. While the vibe is modern, excessive roundness (pill shapes) feels too casual for a premium butcher. The slight 4px radius softens the "industrial" edge of the black-and-white palette, making the interface feel approachable but still sharp and professional. Large cards should utilize the `rounded-lg` (8px) token to feel more substantial.

## Components
- **Primary Buttons:** High-contrast White background with Black text. On hover, the background transitions to Metallic Gold. Rectangular with minimal 4px radius.
- **Secondary Buttons:** Ghost style with 1px Wine Red borders and White text.
- **Cards:** Large, expansive containers. Use a "Dark Wine Red" gradient overlay (top-to-bottom, 0% to 40% opacity) over product photography to tie the imagery into the brand.
- **Product Chips:** Small, #141414 background with Gold borders for "Dry-Aged," "Wagyu," or "Grass-Fed" labels.
- **Input Fields:** Bottom-border only (minimalist style) with Manrope typography. Focus state changes border color to Gold.
- **Status Indicators:** Use Wine Red for "Out of Stock" and a subtle Emerald (not in primary palette) for "In Stock/Fresh Today."