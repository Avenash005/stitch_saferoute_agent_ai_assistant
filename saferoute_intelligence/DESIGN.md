---
name: SafeRoute Intelligence
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
  on-surface-variant: '#c5c6cd'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8f9097'
  outline-variant: '#44474d'
  surface-tint: '#b9c7e4'
  primary: '#b9c7e4'
  on-primary: '#233148'
  primary-container: '#0a192f'
  on-primary-container: '#74829d'
  inverse-primary: '#515f78'
  secondary: '#ffffff'
  on-secondary: '#003733'
  secondary-container: '#00fdee'
  on-secondary-container: '#00716a'
  tertiary: '#2ae500'
  on-tertiary: '#053900'
  tertiary-container: '#021f00'
  on-tertiary-container: '#199700'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#00fdee'
  secondary-fixed-dim: '#00ded1'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#00504b'
  tertiary-fixed: '#79ff5b'
  tertiary-fixed-dim: '#2ae500'
  on-tertiary-fixed: '#022100'
  on-tertiary-fixed-variant: '#095300'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is engineered to evoke high-level trust and predictive intelligence. Targeted at global travelers and urban commuters, the aesthetic balances the cold precision of high-tech safety with the approachable warmth of an AI guardian.

The style is a fusion of **Apple-inspired Minimalism** and **Glassmorphism**. It utilizes expansive negative space, ultra-refined typography, and translucent material layers to create a sense of depth and focus. The UI should feel like a premium heads-up display—calm, organized, and ahead of the curve.

**Key Visual Principles:**
- **Clarity over Clutter:** Every element must serve a functional safety purpose.
- **Glass Optics:** Background blurs and subtle border highlights simulate physical glass lenses.
- **Dynamic Vitality:** Subtle glow effects on accent colors indicate "active" AI monitoring.

## Colors
The palette is rooted in a "Deep Space" dark mode to reduce eye strain during nighttime travel and to make the neon safety accents pop with functional urgency.

- **Primary Deep Blue (#0A192F):** Used for primary backgrounds and deep structural elements to establish authority.
- **Accent Cyan (#00FFF0):** The "AI Active" color. Used for progress, primary actions, and system status.
- **Neon Green (#39FF14):** Reserved exclusively for "Safe" status and positive route confirmations.
- **Functional Alerts:** Orange and Red are used sparingly for risk warnings and immediate danger, ensuring high signal-to-noise ratio.
- **Surface Strategy:** Use semi-transparent white overlays (5-10%) on the dark background to create tiered glass containers.

## Typography
The system uses **Inter** for its neutral, highly legible characteristics across all UI states. For technical data and AI-driven labels, **Geist** is introduced to provide a monospaced, precise feel that reinforces the "Agent" persona.

**Usage Guidelines:**
- **Tamil Support:** For Tamil script, maintain the same optical sizing as Inter. Use a clean, modern sans-serif Tamil font that matches the x-height of Inter.
- **Hierarchy:** Use font weight rather than size to distinguish information. Body text should remain at a comfortable 16px-18px for readability during movement.
- **Labels:** Technical labels (Risk Scores, ETA, Coordinates) should use the Geist font for a distinct "data-driven" look.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous margins to ensure the interface feels airy and uncompressed.

- **Mobile:** 24px side margins with a single-column stack for safety cards.
- **Desktop/Tablet:** 12-column grid with elements spanning 4-6 columns for AI panels.
- **Safe Zones:** Ensure all interactive elements have a minimum 44px hit target, especially for "Emergency" or "SOS" features.
- **Rhythm:** An 8px linear scale governs all padding and margins to maintain mathematical harmony.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Backdrop Blurs** rather than traditional heavy shadows.

- **Base Layer:** Deep Blue (#0A192F).
- **Secondary Layer (Cards):** Translucent white (5% opacity) with a 20px `backdrop-filter: blur()`.
- **Borders:** 1px solid borders with 10% white opacity create a "rim light" effect on glass elements.
- **Active Elevation:** When a route card is selected, add a subtle Cyan glow (`box-shadow: 0 0 20px rgba(0, 255, 240, 0.15)`).

## Shapes
The shape language is sophisticated and friendly. We use a **Rounded** philosophy to soften the "technical" nature of the app.

- **Standard Cards:** 16px (1rem) corner radius.
- **Large AI Panels:** 24px (1.5rem) corner radius.
- **Buttons:** 12px or fully rounded (pill) for secondary toggles.
- **Gauges:** Circular geometries for risk scores to suggest wholeness and 360-degree monitoring.

## Components
Consistent implementation of these components ensures a polished, high-end experience:

- **Route Comparison Cards:** Use glass containers with a 1px Cyan border for the "Recommended" route. Display ETA in Inter and Risk Score in Geist.
- **Risk Score Gauges:** Circular SVG strokes. 0-30% (Neon Green), 31-60% (Warning Orange), 61-100% (Danger Red). Include a subtle inner glow.
- **AI Assistant Panel:** Positioned as a persistent bottom sheet or side drawer. Use a distinct semi-transparent gradient background (Deep Blue to dark Cyan) to differentiate AI-generated content.
- **Tamil/English Toggle:** A pill-shaped segmented control. Use a high-contrast background for the active state to ensure the language choice is clear at a glance.
- **Input Fields:** Minimalist underlines or subtle dark-grey fills. Focus states should trigger a Cyan glow on the bottom border.
- **Buttons:** Primary buttons use a solid Cyan background with black text for maximum visibility. Secondary buttons use the "Ghost" style with a 1px glass border.