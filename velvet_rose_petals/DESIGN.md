---
name: Velvet Rose & Petals
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#5c3f40'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#906f70'
  outline-variant: '#e5bdbe'
  surface-tint: '#be0037'
  primary: '#b80035'
  on-primary: '#ffffff'
  primary-container: '#e11d48'
  on-primary-container: '#fffaf9'
  inverse-primary: '#ffb3b6'
  secondary: '#765469'
  on-secondary: '#ffffff'
  secondary-container: '#fdd0ea'
  on-secondary-container: '#79576c'
  tertiary: '#605a5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#797273'
  on-tertiary-container: '#fffaf9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b6'
  on-primary-fixed: '#40000c'
  on-primary-fixed-variant: '#920028'
  secondary-fixed: '#ffd8ed'
  secondary-fixed-dim: '#e5bad3'
  on-secondary-fixed: '#2c1325'
  on-secondary-fixed-variant: '#5c3d51'
  tertiary-fixed: '#eae0e1'
  tertiary-fixed-dim: '#cdc4c5'
  on-tertiary-fixed: '#1f1a1b'
  on-tertiary-fixed-variant: '#4b4546'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system establishes a digital celebration experience tailored for romantic, heartfelt birthday surprises. It evokes emotional intimacy, delight, and effortless sophistication without sliding into juvenile party motifs or cloying sentimentality. The aesthetic synthesizes high-end editorial minimalism with soft, tactile warmth—reminiscent of bespoke stationery, fine French patisserie packaging, and cinematic storytelling.

### Guiding Principles
- **Editorial Tenderness**: Prioritize sprawling white space, deliberate pacing, and literary phrasing in Spanish (e.g., *Para alguien inolvidable*, *Nuestra historia en instantes*).
- **Curated Delight**: Micro-interactions are gentle and spring-loaded rather than frenetic. Delights unfold gradually—unveiling photos, handwritten notes, audio snippets, or memory timelines.
- **Modern Restraint**: Avoid kitschy birthday tropes like pixel balloons, plastic confetti bursts, or garish neon banners. Instead, lean into luminous blur halos, organic card contours, and immaculate typographic hierarchies.

## Colors

The palette balances airy, light-soaked blush backdrops with the vibrancy of fresh rose petals and grounded editorial charcoals.

### Application Roles
- **Primary (`#E11D48`, Warm Rose Crimson)**: Used for primary calls-to-action (e.g., *Descubrir sorpresa*, *Abrir dedicatoria*), focal highlights, active states, and expressive iconography accents. Use `#F43F5E` for vibrant interactive hover states and `#BE123C` for pressed interactions and deep contrast accents.
- **Secondary (`#FBCFE8` to `#FCE7F3`, Pastel Blush)**: Serves as pill tag fills, subtle pill borders, envelope linings, and soft spotlight washes behind images or celebratory cards.
- **Tertiary (`#FFF5F6` to `#FDF2F4`, Romantic Canvas Milk)**: Serves as warm tinted section backgrounds, input surface fills, and inset memory containers that gently break pure white pages.
- **Neutral (`#1E293B` to `#475569`, Deep Slate & Muted Charcoal)**: Replaces stark black with velvety dark tones to ensure maximum readability while preserving a gentle contrast against pink canvases. Secondary copy and timestamps use `#64748B`.
- **Base Canvas (`#FFFFFF`)**: The foundational surface for cards, envelopes, floating dialogs, and navigation pills, keeping the interface crisp and modern.

## Typography

The type system pairs the romantic, editorial flair of `Playfair Display` with the friendly, ergonomic clarity of `Plus Jakarta Sans`.

- **Editorial Headings**: Headline titles, milestone dates, and central birthday greetings use `Playfair Display`. Italics within headings are encouraged for evocative emphasis (e.g., *Feliz cumpleaños, amor*).
- **Body & Captions**: All functional UI, narrative letters, instructions, and interactive options employ `Plus Jakarta Sans` with relaxed line-heights for serene, effortless readability.
- **Badges & Microcopy**: Small contextual tags use uppercase or semi-bold `Plus Jakarta Sans` with subtle tracking to maintain clarity at compact scales.

## Layout & Spacing

The layout embraces generous breathing room to impart an unhurried, luxury keepsake mood.

- **Grid Architecture**: A centered 12-column responsive fluid grid on desktop (`max-width: 1120px`), shifting to a 4-column layout on mobile devices.
- **Section Rhythm**: Sections are separated by sweeping vertical margins (`space-xl` scaled up to `5rem`–`6rem` on desktop displays) to allow each memory, letter, or gift reveal to stand as its own emotional vignette.
- **Micro Spacing**: Components rely on `space-sm` for tightly bound icon-label relationships and `space-md` through `space-lg` for card insets, producing a cushiony, inviting feel.

## Elevation & Depth

Visual hierarchy uses ethereal, diffuse shadows with warm undertones rather than cold grayscale drop shadows, complemented by translucent layering.

- **Rose Ambient Cast**: Shadows integrate warm crimson undertones (`rgba(225, 29, 72, 0.06)` combined with `rgba(30, 41, 59, 0.04)`) with large blur radii (16px to 32px) and no harsh outlines.
- **Layered Keepsake Surfaces**: Floating cards use pure white backgrounds (`#FFFFFF`) with ultra-fine borders rendered in `rgba(251, 207, 232, 0.5)`. This creates a tactile, deckle-edged paper appearance.
- **Glass Accents**: Sticky navigation bars and floating photo viewer controls employ subtle backdrop blur (`backdrop-filter: blur(12px)`) over translucent blush canvases (`rgba(255, 255, 255, 0.85)`).

## Shapes

The design system embraces an ultra-soft, organic contour language. 

- **Cards & Memory Modules**: Standard cards adopt continuous rounded corners (`rounded-2xl` / 1.5rem), while monumental reveal envelopes and focal interactive modules employ sweeping curves (`rounded-3xl` / 2rem–2.5rem).
- **Interactive Pills**: Action buttons, tags, chips, and progress capsules utilize continuous pill radius (`border-radius: 9999px`).
- **Media Framing**: Photos and video vignettes use rounded corners paired with optional delicate inner borders to mirror polished keepsake photo albums.

## Components

### Buttons
- **Primary Reveal Button**: Pill-shaped (`rounded-full`), filled with warm rose (`#E11D48`), text in crisp white (`#FFFFFF`). Accompanied by a gentle ambient rose glow shadow (`0 8px 24px -4px rgba(225, 29, 72, 0.28)`). On hover, shifts to `#F43F5E` with an imperceptible upward lift (`translate-y: -1px`).
- **Secondary Romantic Button**: Pill-shaped, tinted pastel blush fill (`#FFF5F6`), bordered with soft pink stroke (`#FBCFE8`), charcoal label (`#1E293B`).
- **Ghost Action**: Transparent background with rose typography and subtle underline animation for secondary navigation (e.g., *Volver a leer*, *Saltar animación*).

### Romantic Chips & Badges
- Compact pill-shaped containers used for milestone dates, mood tags (e.g., *Nuestra primera cita*, *Canción favorita*), or unlock statuses.
- Styled with `#FFF5F6` fill, `#FBCFE8` border (1px), `#BE123C` text, paired with optional subtle romantic micro-icons (sparkles, hearts, ribbon accents).

### Cards & Surprise Containers
- Rendered in pure `#FFFFFF` over `#FFF5F6` backgrounds. Outlined with low-contrast pastel rose borders (`rgba(251, 207, 232, 0.6)`), rounded to `1.5rem` or `2rem`.
- Padding set generously to `space-lg` or `space-xl`.
- Support interactive "wax seal" or "ribbon" motifs that animate smoothly open upon tap.

### Inputs & Dedication Fields
- Text areas and guest message fields feature smooth `1.25rem` corner radius, `#FFFFFF` interior, and an understated `#FCE7F3` outline.
- Active focus state applies a crisp `#E11D48` ring with a 3px soft pink bloom (`rgba(244, 63, 94, 0.15)`).
- Placeholder text is set in `#64748B` using `Plus Jakarta Sans`.

### Selection Controls (Checkboxes & Radios)
- Radio controls and choice pills utilize circular geometry with smooth rose transitions. 
- Selected state fills with `#E11D48` displaying a white internal pip or checkmark, surrounded by a subtle rose tint ring.

### Keepsake Timeline & Audio Player
- **Memory Timeline**: Vertical or horizontal dotted ribbon in `#FBCFE8` connecting circular photographic nodes bordered in pure white with rose accents.
- **Audio Note Capsule**: Floating pill card featuring a play/pause rose circle button, dynamic pastel sound waves, and romantic timestamp microcopy.