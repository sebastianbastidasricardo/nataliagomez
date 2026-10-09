---
name: Ethereal Professionalism
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4f4445'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#817475'
  outline-variant: '#d2c3c4'
  surface-tint: '#72575b'
  primary: '#301b1e'
  on-primary: '#ffffff'
  primary-container: '#473033'
  on-primary-container: '#b7979b'
  inverse-primary: '#e1bec1'
  secondary: '#645d58'
  on-secondary: '#ffffff'
  secondary-container: '#ebe0da'
  on-secondary-container: '#6a635e'
  tertiary: '#2e1d15'
  on-tertiary: '#ffffff'
  tertiary-container: '#453229'
  on-tertiary-container: '#b5998d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fedadd'
  primary-fixed-dim: '#e1bec1'
  on-primary-fixed: '#2a1619'
  on-primary-fixed-variant: '#594043'
  secondary-fixed: '#ebe0da'
  secondary-fixed-dim: '#cfc5bf'
  on-secondary-fixed: '#201b17'
  on-secondary-fixed-variant: '#4c4541'
  tertiary-fixed: '#fcdcce'
  tertiary-fixed-dim: '#dfc0b3'
  on-tertiary-fixed: '#281810'
  on-tertiary-fixed-variant: '#574238'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  deep-espresso: '#473033'
  warm-cream: '#F4E9E3'
  soft-blush: '#F9F2EF'
  ink-black: '#1A1A1A'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 72px
    fontWeight: '500'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-xl-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system embodies a sophisticated blend of warmth and technical precision. It is designed for creative agencies and high-end professional services that prioritize human connection and aesthetic excellence. 

The style is a fusion of **Minimalism** and **Modern Corporate**, utilizing generous whitespace and a "warm-tech" atmosphere. It avoids the coldness of traditional tech brands by using a rich, organic color palette. Visuals should feel editorial and premium, leveraging high-contrast typography and subtle depth to guide the user through a curated experience.

## Colors
The palette is anchored by a deep, sophisticated espresso (`#473033`) which serves as the primary driver for text and structural elements. This is balanced by a warm cream (`#F4E9E3`) that acts as a softer alternative to pure white for large surface areas, reducing eye strain and adding a tactile, paper-like quality.

- **Primary:** Use for headers, primary buttons, and iconography.
- **Secondary:** Use for large background sections and subtle container fills.
- **Accent (Tertiary):** Use for hover states, active indicators, and secondary highlights.
- **Neutral:** Use white for high-clarity content areas and black for high-contrast micro-copy.

## Typography
The typography strategy relies on the tension between a classic, high-contrast serif and a modern, technical sans-serif.

- **EB Garamond** is used for all display and headline roles. It evokes an editorial, authoritative feel. It should be used sparingly but boldly.
- **Hanken Grotesk** provides a clean, highly legible counterpoint for body copy and UI labels. Its sharp geometry ensures the interface feels modern and efficient.
- **Visual Hierarchy:** Use wide tracking for uppercase labels to create an "airy" feel in navigation and metadata.

## Layout & Spacing
This design system utilizes a **fixed-center grid** for desktop and a **fluid grid** for mobile devices. 

- **Desktop:** 12-column grid with a 1280px max-width. Use 64px side margins to create an expansive, premium feel.
- **Mobile:** 4-column grid with 16px margins. 
- **Rhythm:** All spacing (padding, margins, gaps) must be multiples of the 8px base unit. 
- **Negative Space:** Prioritize vertical "breathing room" between sections (96px or 128px) to emphasize the editorial nature of the content.

## Elevation & Depth
Depth is created primarily through **Tonal Layering** rather than heavy shadows. 

1. **Base:** The main canvas uses the Secondary color (`#F4E9E3`).
2. **Surface:** Interactive components and cards use the Neutral white (`#FFFFFF`) to pop against the cream background.
3. **Ghost Borders:** For low-elevation elements, use 1px solid borders in a slightly darker tint of the cream background rather than shadows.
4. **Interactive Shadow:** Only apply shadows on hover or for high-priority modals. Use a very soft, diffused espresso-tinted shadow (Opacity: 8%, Blur: 20px) to maintain the "warm" aesthetic.

## Shapes
The shape language is **Soft** but disciplined. 

- **Buttons & Inputs:** Use a 4px (0.25rem) corner radius. This provides just enough softness to feel approachable without losing the professional "edge."
- **Cards & Containers:** Use an 8px (0.5rem) radius for larger containers.
- **Media:** Images should either be perfectly sharp (0px) for an editorial look or follow the container radius when nested.
- **Icons:** Use thin-stroke (1.5px) icons with slightly rounded terminals to match the typography's character.

## Components
- **Buttons:** Primary buttons use the Primary Espresso background with White text. Secondary buttons use a Primary Espresso outline with no fill.
- **Input Fields:** Use a subtle "Soft Blush" fill with a bottom-border-only focus state to maintain a clean, architectural look.
- **Cards:** Cards should be "Flat" (no shadow) with a 1px border in a tonal shade of the background. Use internal padding of 32px to ensure content doesn't feel cramped.
- **Chips/Tags:** Use the Label-SM typography, housed in pill-shaped containers with a Primary-colored outline.
- **Navigation:** The header should be transparent on scroll, transitioning to a Warm Cream background with a soft bottom border once the user scrolls past the hero section.