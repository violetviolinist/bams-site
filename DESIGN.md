---
name: Bombay Academy of Management Studies
description: An enduring corporate academy balancing institutional authority with practical human performance.
colors:
  executive-navy: "#0A1F3F"
  executive-navy-light: "#132D54"
  executive-navy-dark: "#06142A"
  restorative-teal: "#2A7F7F"
  restorative-teal-light: "#3A9E9E"
  heritage-gold: "#C5A55A"
  heritage-gold-light: "#D4BA7A"
  warm-ivory: "#F8F6F0"
  white: "#FFFFFF"
typography:
  display:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "3.75rem"
    fontWeight: 700
    lineHeight: 1
  headline:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "3rem"
    fontWeight: 700
    lineHeight: 1
  title:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "1.875rem"
    fontWeight: 700
    lineHeight: 1.2
  body:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.625
  label:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: "0.05em"
rounded:
  md: "6px"
  lg: "8px"
  full: "9999px"
spacing:
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "64px"
  section: "80px"
components:
  button-gold:
    backgroundColor: "{colors.heritage-gold}"
    textColor: "{colors.executive-navy}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "12px 32px"
  button-gold-hover:
    backgroundColor: "{colors.heritage-gold-light}"
    textColor: "{colors.executive-navy}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "12px 32px"
  button-navy:
    backgroundColor: "{colors.executive-navy}"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "12px 32px"
  card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.executive-navy}"
    rounded: "{rounded.lg}"
    padding: "32px"
---

# Design System: Bombay Academy of Management Studies

## Overview

**Creative North Star: "The Enduring Academy"**

The system presents BAMS as a formal, historic institution that has evolved without discarding its authority. Deep navy establishes permanence, restrained gold signals heritage, and teal introduces the contemporary mind-management practice. Warm ivory keeps long sections approachable without turning the experience into consumer wellness branding.

The visual language is composed and conventional: centered page introductions, generous vertical rhythm, direct typography, modestly rounded controls, and orderly card grids. It should feel established before it feels fashionable. Avoid soft-focus spa language and generic startup-SaaS effects such as glass panels, playful gradients, or novelty UI treatments.

**Key Characteristics:**

- Formal, historic, and quietly authoritative
- Deep navy foundations with selective gold and teal accents
- Clear Inter typography with bold, direct headings
- Generous section spacing and restrained surface elevation
- Institutional, solid components with modest rounding

## Colors

The palette joins executive authority, restorative calm, and heritage warmth without becoming ornate.

### Primary

- **Executive Navy** (`#0A1F3F`): The dominant institutional field for navigation, page headers, footers, primary text, and dark buttons.
- **Executive Navy Light** (`#132D54`): Hover and active treatment on navy surfaces.
- **Executive Navy Dark** (`#06142A`): Deepens the home hero's restrained tonal gradient.

### Secondary

- **Restorative Teal** (`#2A7F7F`): Marks current programs, links, icons, section accents, and present-day human-performance expertise.
- **Restorative Teal Light** (`#3A9E9E`): Teal hover state.

### Tertiary

- **Heritage Gold** (`#C5A55A`): Signals legacy, active navigation, eyebrow labels, bullets, and the primary hero action.
- **Heritage Gold Light** (`#D4BA7A`): Gold hover state.

### Neutral

- **Warm Ivory** (`#F8F6F0`): Alternating section surfaces, information panels, and quiet component backgrounds.
- **White** (`#FFFFFF`): Main canvas, cards, and text on dark fields.

### Named Rules

**The Three Roles Rule.** Navy carries authority, teal identifies current expertise, and gold marks heritage or a high-priority action; do not interchange them casually.

**The Gold Restraint Rule.** Gold is an accent, not a large background field. Its scarcity preserves its institutional weight.

## Typography

**Display Font:** Inter (with system UI fallbacks)  
**Body Font:** Inter (with system UI fallbacks)

**Character:** One disciplined sans-serif family keeps the site contemporary and legible while weight, scale, and spacing provide hierarchy. The absence of decorative type supports corporate credibility.

### Hierarchy

- **Display** (700, `3.75rem`, line-height `1`): Home hero headlines on large screens; reduces responsively.
- **Headline** (700, `3rem`, line-height `1`): Page titles and major section statements on medium and large screens.
- **Title** (700, `1.875rem`, line-height `1.2`): Section headings and prominent content groups.
- **Body** (400, `1.125rem`, line-height `1.625`): Explanatory copy, generally constrained to `42–56rem` for readable line length.
- **Label** (500, `0.875rem`, letter-spacing `0.05em`): Eyebrows and institutional labels, typically uppercase.

### Named Rules

**The Single-Family Rule.** Use Inter across display, body, and labels; create hierarchy through scale and weight rather than decorative font switching.

## Layout

Pages use a centered container up to `80rem` wide with responsive horizontal gutters of `16px`, `24px`, and `32px`. Reading sections narrow to `48–56rem`; calls to action often narrow to `42–48rem`. Major desktop sections use approximately `80px` of vertical padding, while page headers use `64px`.

Grids progress from one column to two columns at `48rem`; client collections expand to four columns where space permits. Navigation switches to the desktop row at `64rem`. Content remains symmetrical and orderly, with centered introductions and left-aligned detail sections.

## Elevation & Depth

The system uses restrained layers. Most separation comes from navy, white, ivory, and low-opacity borders. Cards use soft resting shadows and rise only slightly on hover; the sticky navigation receives the strongest shadow to establish persistent hierarchy.

### Shadow Vocabulary

- **Card Rest** (`0 1px 3px 0 rgb(0 0 0 / 10%), 0 1px 2px -1px rgb(0 0 0 / 10%)`): White cards and client tiles.
- **Card Hover** (`0 4px 6px -1px rgb(0 0 0 / 10%), 0 2px 4px -2px rgb(0 0 0 / 10%)`): Interactive card response.
- **Navigation Lift** (`0 10px 15px -3px rgb(0 0 0 / 10%), 0 4px 6px -4px rgb(0 0 0 / 10%)`): Sticky site header only.

### Named Rules

**The Restrained Layers Rule.** Keep surfaces flat by default; use shadow to clarify interaction or persistent hierarchy, never as decoration.

## Shapes

Gently curved rectangles establish a dependable, contemporary form language. Buttons, navigation items, and compact badges use a `6px` radius; cards and information panels use `8px`. Circles are reserved for icons and bullet markers. Fine navy borders at roughly 10% opacity define white cards without making the interface feel boxed in.

## Components

Components should feel institutional and solid: direct labels, firm color roles, modest curves, and fast color or shadow transitions.

### Buttons

- **Shape:** Gently curved rectangle (`6px`).
- **Primary:** Gold with navy text in the home hero, or navy with white text on light sales surfaces; semibold label with `12px 32px` padding.
- **Hover / Focus:** Shift to the corresponding light color over `150ms`; retain a visible native focus outline.
- **Secondary:** Transparent with a low-opacity white border on dark surfaces; strengthen the border to white on hover.

### Cards / Containers

- **Corner Style:** Modestly rounded (`8px`).
- **Background:** White for workshop and client cards; Warm Ivory for quiet information groupings.
- **Shadow Strategy:** Soft rest shadow, changing to the hover shadow only when the card is interactive.
- **Border:** Executive Navy at 10% opacity on white cards.
- **Internal Padding:** `24px` for compact cards and `32px` for workshop or pricing cards.

### Navigation

- **Style:** Deep navy sticky header with white medium-weight links, gold active and hover states, and a strong but diffuse navigation shadow. Desktop links form a single horizontal row at `64rem` and above; mobile links become stacked full-width items with a navy-light active surface.

### Contact Method Tiles

- **Style:** Warm Ivory rectangular tiles with `8px` corners, a circular teal icon field, and left-aligned two-level labels. Hover subtly lightens the surface and shifts the title to teal.

## Do's and Don'ts

### Do:

- **Do** anchor major institutional surfaces in Executive Navy and use Warm Ivory to pace long pages.
- **Do** reserve Heritage Gold for legacy cues, active navigation, bullets, and the highest-priority action.
- **Do** use Restorative Teal for present-day programs, links, icons, and contemporary expertise.
- **Do** keep section spacing generous and prose within readable `42–56rem` measures.
- **Do** preserve visible keyboard focus, strong text contrast, and responsive stacking.

### Don't:

- **Don't** drift into consumer-spa styling with pastel washes, soft-focus imagery, script typography, or spiritual motifs.
- **Don't** imitate generic startup SaaS with glassmorphism, neon accents, playful gradients, or novelty dashboards.
- **Don't** use gold as a dominant surface or treat all three brand colors as interchangeable accents.
- **Don't** add heavy shadows, excessive rounding, or floating layers where borders and tonal separation suffice.
