---
version: alpha
name: atrium-medical-center-design
description: A trust-driven healthcare design system for Atrium Medical Center — a 68-bed LTACH in Stafford, TX. Anchored by deep teal green (`#08533d`) drawn from the logo mark, with a warm gold accent (`#938304`) as secondary CTA. The system uses a system-native sans-serif stack, consistent 6px border-radius on all structural surfaces, and a three-mode section rhythm of white / pale green / dark green slabs. There are no decorative flourishes — the brand mark is the logo lockup itself, and all visual weight is carried by color, typographic contrast, and generous whitespace.

colors:
  primary: "#08533d"
  primary-dark: "#053a2b"
  primary-light: "#0e7355"
  primary-pale: "#e6f4ee"
  on-primary: "#ffffff"
  ink: "#0c1a15"
  ink-deep: "#000000"
  body: "#1b2c26"
  mute: "#607870"
  stone: "#829990"
  ash: "#a5b8b0"
  on-dark: "#ffffff"
  on-dark-mute: "rgba(255, 255, 255, 0.75)"
  canvas: "#ffffff"
  surface-soft: "#f2f7f4"
  surface-dark: "#071d18"
  surface-elevated: "#0f2c25"
  hairline: "#d5e2dc"
  hairline-strong: "#234d40"
  accent-gold: "#938304"
  accent-gold-pale: "#fef9db"
  accent-mint: "#35c49b"
  link-blue: "#0056a7"
  bg-alt: "#fafdfb"

typography:
  hero-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 3.2rem
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: 0
  h1:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 2.5rem
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: 0
  h2:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 2.2rem
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  h3:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 1.3rem
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  body-lg:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 1.2rem
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body-md:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 0.92rem
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 0.85rem
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  caption-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 0.78rem
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  sub-heading:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif"
    fontSize: 0.85rem
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 1px
    textTransform: uppercase
  button:
    fontFamily: inherit
    fontSize: 1rem
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  default: 6px
  pill: 50px
  circle: 50%

spacing:
  xs: 0.5rem
  sm: 0.75rem
  md: 1rem
  lg: 1.5rem
  xl: 2rem
  xxl: 2.5rem
  section: 4rem
  section-mobile: 2.5rem

components:
  page-header:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    padding: 4rem 0 3rem
    borderBottom: "3px solid {colors.primary}"
  page-header-subtitle:
    textColor: "{colors.on-dark-mute}"
    typography: "{typography.body-lg}"
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.default}"
    padding: 0.75rem 1.5rem
    border: "2px solid {colors.primary}"
  button-primary-hover:
    backgroundColor: "{colors.primary-dark}"
    borderColor: "{colors.primary-dark}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.default}"
    padding: 0.75rem 1.5rem
    border: "2px solid {colors.primary}"
  button-gold:
    backgroundColor: "{colors.accent-gold}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.default}"
    padding: 0.75rem 1.5rem
    border: "2px solid {colors.accent-gold}"
  button-gold-hover:
    backgroundColor: "#7b6d03"
    borderColor: "#7b6d03"
  card-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    rounded: "{rounded.default}"
    border: "1px solid {colors.hairline}"
  card-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.default}"
  card-soft:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.body}"
    rounded: "{rounded.default}"
    border: "1px solid {colors.hairline}"
  card-hover:
    transform: "translateY(-5px)"
    boxShadow: "0 12px 25px rgba(0,0,0,0.06)"
    borderColor: "{colors.primary-light}"
  stat-number:
    textColor: "{colors.primary}"
    fontSize: 2.2rem
    fontWeight: 800
  value-circle:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.circle}"
    width: 60px
    height: 60px
  sub-heading:
    textColor: "{colors.primary}"
    typography: "{typography.sub-heading}"
  sub-heading-on-dark:
    textColor: "{colors.accent-mint}"
    typography: "{typography.sub-heading}"
  hero-badge:
    backgroundColor: "rgba(14, 115, 85, 0.35)"
    textColor: "{colors.primary-pale}"
    border: "1px solid {colors.primary-light}"
    rounded: "{rounded.pill}"
    padding: 0.35rem 0.9rem
    fontSize: 0.85rem
  hero-overlay:
    background: "linear-gradient(90deg, rgba(7,29,24,0.92) 0%, rgba(7,29,24,0.75) 50%, rgba(7,29,24,0.45) 100%)"
  hero-stats-bar:
    backgroundColor: "rgba(7,29,24,0.65)"
    backdropFilter: "blur(10px)"
    border: "1px solid {colors.hairline-strong}"
    rounded: "{rounded.default}"
    padding: 1.25rem
  top-bar:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark-mute}"
    borderBottom: "1px solid {colors.hairline-strong}"
  main-header:
    backgroundColor: "{colors.canvas}"
    borderBottom: "1px solid {colors.hairline}"
    boxShadow: "0 2px 10px rgba(0,0,0,0.05)"
    height: 75px
  nav-link:
    textColor: "{colors.ink}"
    fontSize: 1.02rem
    fontWeight: 600
  nav-link-hover:
    textColor: "{colors.primary}"
  dropdown-menu:
    backgroundColor: "{colors.canvas}"
    border: "1px solid {colors.hairline}"
    boxShadow: "0 10px 25px rgba(0,0,0,0.12)"
    rounded: "{rounded.default}"
  dropdown-link-hover:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.primary}"
  footer-top:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark-mute}"
    borderTop: "3px solid {colors.primary}"
  footer-title:
    textColor: "{colors.on-dark}"
    underlineColor: "{colors.primary}"
    underlineWidth: "40px x 2px"
  footer-link-hover:
    textColor: "{colors.primary-light}"
    paddingLeft: 3px
  footer-bottom:
    backgroundColor: "#030d0a"
    borderTop: "1px solid {colors.hairline-strong}"
---

## Overview

Atrium Medical Center reads like a trusted healthcare institution's digital presence — calm, authoritative, and clinically precise. The entire system sits on **pure white** (`{colors.canvas}` — `#ffffff`) with alternating bands of **soft pale green** (`{colors.surface-soft}` — `#f2f7f4` and `{colors.bg-alt}` — `#fafdfb`) and **deep teal green slabs** (`{colors.surface-dark}` — `#071d18`). There are two chromatic action colors — **Teal Green** (`{colors.primary}` — `#08533d`) for the primary CTA and **Warm Gold** (`{colors.accent-gold}` — `#938304`) as a secondary signal — drawn directly from the [Atrium Medical Center logo](/main-logo.png), whose mark centers on a deep forest-teal (`#004c35`) icon with an adjacent gold-olive (`#968f14`) accent. Type is the system-native sans-serif stack across every surface, set at weight 800/700 for headlines and 400 for body — clean, legible, and trustworthy.

The signature gesture is the **dark teal slab** — every page opens with a `{colors.surface-dark}` page-header band (accented by a `{colors.primary}` bottom border stripe) and closes with a matching footer band. The homepage hero uses a full-bleed video background with a dark gradient overlay, white text, and a translucent stats bar. There are no decorative flourishes — the brand mark in the header and footer is the only emblematic element. All visual weight is carried by color contrast, typographic hierarchy, card hover lifts, and generous whitespace.

The system breaks into three surface modes: a **white commercial body** for welcome content and service cards; a **soft pale green band** (`{colors.surface-soft}` / `{colors.bg-alt}`) for alternating sections like insurance plans, contact forms, and feature callouts; and a **deep teal slab** (`{colors.surface-dark}`) for page headers, the mission statement, and the footer. The teal green primary appears on filled CTAs, link text, stat numbers, section underlines, and footer accents — never as a full section background.

**Key Characteristics:**
- Pure white canvas (`{colors.canvas}`) with near-black body text (`{colors.body}`); pale green bands (`{colors.surface-soft}`, `{colors.bg-alt}`) alternate for section rhythm
- Teal green (`{colors.primary}`) is the primary CTA fill, link color, and accent; gold (`{colors.accent-gold}`) serves as a secondary CTA for tour bookings and contact actions
- System-native sans-serif stack across every surface at weights 400 / 600 / 700 / 800
- Every structural surface shares a consistent `{rounded.default}` (6px) border-radius — cards, buttons, inputs, dropdowns
- Dark teal slabs (`{colors.surface-dark}`) open and close every page — header band and footer
- Section rhythm: dark page-header → white body → pale green band → dark slab → pale green band → dark footer

## Colors

> **No Interaction sub-section.** Hover colors are silently filtered. Allowed sub-sections: Brand & Accent, Surface, Text, Semantic.

### Brand & Accent
- **Teal Green** (`{colors.primary}` — `#08533d`): the system's primary signal — primary CTA fill, link color, stat numbers, active nav indicator, underline accents. Derived from the logo's dominant dark teal (`#004c35`).
- **Dark Teal** (`{colors.primary-dark}` — `#053a2b`): pressed/hover state for the primary CTA.
- **Light Teal** (`{colors.primary-light}` — `#0e7355`): hover border accent on cards, hero badge border, footer link hover color.
- **Pale Green** (`{colors.primary-pale}` — `#e6f4ee`): hero badge text color, subtle chip backgrounds.
- **Warm Gold** (`{colors.accent-gold}` — `#938304`): secondary CTA fill ("Schedule a Tour", "Contact Us"), license tag emphasis. Drawn from the logo's gold-olive accent (`#968f14`).
- **Pale Gold** (`{colors.accent-gold-pale}` — `#fef9db`): pale gold background for special callouts.
- **Mint** (`{colors.accent-mint}` — `#35c49b`): used for emphasized words within hero title and C.A.R.E. value letter highlights on dark backgrounds.
- **Link Blue** (`{colors.link-blue}` — `#0056a7`): reserved for legal/regulatory inline links only.

### Surface
- **Canvas** (`{colors.canvas}` — `#ffffff`): the universal page background. White, full opacity.
- **Soft Green** (`{colors.surface-soft}` — `#f2f7f4`): pale green-gray section band for insurance, contact forms, stat cards, and alternating content rows.
- **Alt Green** (`{colors.bg-alt}` — `#fafdfb`): very pale green section band for services grid and values section — slightly warmer than `surface-soft`.
- **Dark Teal** (`{colors.surface-dark}` — `#071d18`): the deep brand slab used for page headers, mission section, top bar, footer, and hero overlay base.
- **Elevated Dark** (`{colors.surface-elevated}` — `#0f2c25`): slightly lighter dark surface for elevated dark cards or hover states.
- **Hairline** (`{colors.hairline}` — `#d5e2dc`): subtle green-gray border used on cards, dividers, and input outlines.
- **Strong Hairline** (`{colors.hairline-strong}` — `#234d40`): stronger border on dark backgrounds and footer bottom bar.

### Text
- **Ink** (`{colors.ink}` — `#0c1a15`): near-black used for headline text on white surfaces.
- **Body** (`{colors.body}` — `#1b2c26`): default body text color on light surfaces.
- **Mute** (`{colors.mute}` — `#607870`): muted secondary text — descriptions, metadata, labels.
- **Stone** (`{colors.stone}` — `#829990`): tertiary text for less prominent information.
- **Ash** (`{colors.ash}` — `#a5b8b0`): lightest text tier for disclaimers and fine print.
- **On Dark** (`{colors.on-dark}` — `#ffffff`): pure white for headline and body text on every dark teal slab.
- **On Dark Mute** (`{colors.on-dark-mute}` — `rgba(255, 255, 255, 0.75)`): muted white text on dark surfaces — subtitles, secondary info.

### Semantic
- No dedicated semantic error palette exists in the system; form validation and error states are not currently implemented.

## Typography

### Font Family

The voice is **single-stack**: the system-native sans-serif (`-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Helvetica Neue", sans-serif`) across every surface — hero, heading, body, caption. No custom or imported fonts. This choice prioritizes instant load performance, OS-level font smoothing, and familiar readability for a healthcare audience.

The system runs a broad weight range: **800** for hero titles and page H1s, **700** for H2s and section headings, **600** for navigation and buttons, and **400** for body copy. This weight contrast creates hierarchy without relying on size alone.

### Hierarchy

| Token | Size | Weight | Line Height | Use |
|---|---|---|---|---|
| `{typography.hero-title}` | 3.2rem | 800 | 1.15 | Homepage hero headline |
| `{typography.h1}` | 2.5rem | 800 | 1.2 | Page headers |
| `{typography.h2}` | 2.2rem | 700 | 1.25 | Section headings |
| `{typography.h3}` | 1.3rem | 700 | 1.3 | Card titles, form headers |
| `{typography.body-lg}` | 1.2rem | 400 | 1.6 | Lead paragraphs, page header subtitles |
| `{typography.body-md}` | 1rem | 400 | 1.6 | Default body text |
| `{typography.body-sm}` | 0.92rem | 400 | 1.6 | Card descriptions, service links |
| `{typography.caption}` | 0.85rem | 400 | 1.5 | Metadata, stat descriptions, footer text |
| `{typography.caption-sm}` | 0.78rem | 400 | 1.4 | Fine print, legal lines, hero stat sub-labels |
| `{typography.sub-heading}` | 0.85rem | 700 | 1.4 | Section eyebrow labels (uppercase, 1px tracking) |
| `{typography.button}` | 1rem | 600 | 1.4 | Primary, outline, and gold button labels |

### Principles

Atrium's typographic voice is **authoritative but approachable**. The heavy 800-weight hero and H1 titles communicate clinical confidence, while the 1.6 line-height on body copy ensures readability for users of all ages — a critical consideration for a hospital website where patients and their families may be under stress.

The uppercase `sub-heading` token (0.85rem, 700 weight, 1px letter-spacing) is the only place the system tightens tracking. It labels every major section ("What We Provide", "Who We Are", "Insurance Accepted") and uses the primary teal on light backgrounds or mint on dark backgrounds.

There are no decorative italic or serif faces. Emphasis is carried by weight (700 bold, 600 semibold) and by the primary teal color on links and inline highlights.

## Layout

### Spacing System

- **Base unit**: 0.5rem (~8px). The scale flows from tight metadata rows to generous section gaps.
- **Tokens (front matter)**: `{spacing.xs}` 0.5rem · `{spacing.sm}` 0.75rem · `{spacing.md}` 1rem · `{spacing.lg}` 1.5rem · `{spacing.xl}` 2rem · `{spacing.xxl}` 2.5rem · `{spacing.section}` 4rem (desktop) / 2.5rem (mobile)
- **Section padding**: `{spacing.section}` (4rem) vertical between major bands on desktop; collapses to `{spacing.section-mobile}` (2.5rem) below 768px.
- **Card internal padding**: `{spacing.xl}` (2rem) for service cards and stat cards; `{spacing.xxl}` (2.5rem) for dark welcome cards and form containers.
- **Gutter**: `{spacing.lg}` (1.5rem) between grid columns; `{spacing.xxl}` (3.5rem) between 2-column grid halves.

The 4rem section gap is the universal rhythm constant — it appears between every major homepage band and between content sections on interior pages.

### Grid & Container

- **Desktop max-width**: `1280px` content container (`--max-width`) with full-bleed section backgrounds.
- **Hero**: full-viewport-height video section with dark gradient overlay, white text content card on the left, and a translucent stats bar below the CTAs.
- **Content grid (`.grid-2`)**: 2-column layout (1.2fr 0.8fr or 1fr 1fr) at >992px, single-column stack below 992px. Gap: 3.5rem.
- **Services grid**: `repeat(auto-fit, minmax(280px, 1fr))` — responsive card grid that naturally adjusts from 4 columns to 1.
- **Footer grid**: 3-column layout (2fr 1fr 1fr) at >992px, single-column stack below 992px.
- **Values grid**: `repeat(auto-fit, minmax(220px, 1fr))` — 4-column on desktop, collapses responsively.

### Whitespace Philosophy

Whitespace is **clinical-clean** — generous around the hero headline and CTAs (3rem below the subtitle), tight around metadata stats and caption rows. Service cards leave breathing room (2rem padding) so each image and description reads as a self-contained offering. The fine-print disclaimer regions (legal lines, footer bottom) tighten line-height to 1.4 and shrink type to 0.78rem so the bulk of small print stays compact.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 — Flat | No border, no shadow. | Section bands (white, soft green, dark teal), full-bleed hero |
| 1 — Hairline | 1px solid `{colors.hairline}` (`#d5e2dc`) border, no shadow. | Cards, dropdown menus, form inputs, section dividers |
| 2 — Soft Lift | `0 10px 30px rgba(0,0,0,0.1)`. | Dark welcome card on homepage |
| 3 — Card Hover | `0 12px 25px rgba(0,0,0,0.06)` + `translateY(-5px)`. | Service card, value card, news card on hover |
| 4 — Dropdown | `0 10px 25px rgba(0,0,0,0.12)`. | Navigation dropdown menus |
| 5 — Drawer | `-5px 0 25px rgba(0,0,0,0.15)`. | Mobile navigation drawer |

The system is mostly flat — depth is communicated by **color contrast** (white card on pale green band) more than shadow. The Card Hover lift is the primary interactive feedback mechanism across the entire catalog of service cards, value cards, and news tiles.

### Header Depth

The sticky main header (`{colors.canvas}` background) uses a subtle `0 2px 10px rgba(0,0,0,0.05)` shadow and a 1px `{colors.hairline}` bottom border — enough to create separation from the page content without visual weight.

### Decorative Depth

The system has no decorative depth elements. The **logo lockup** in the header and footer is the only brand mark. There are no chevrons, slashes, abstract shapes, background patterns, or geometric flourishes. The brand's visual identity is carried exclusively by the teal-green color field, the gold accent on secondary CTAs, and the consistent dark-teal page-header → footer frame.

## Shapes

### Border Radius

| Token | Value | Use |
|---|---|---|
| `{rounded.default}` | 6px | Universal — cards, buttons, inputs, dropdowns, stat bars, form containers |
| `{rounded.pill}` | 50px | Hero badge "pill", value chips on mission section, search input on services page |
| `{rounded.circle}` | 50% | C.A.R.E. value letter circles (60×60px) |

The system uses a **single-radius philosophy**: every structural surface shares the same 6px `{rounded.default}`. There is no distinction between button radius and card radius — they share the same corner. The only exceptions are pill-shaped badges/chips (50px) and the circular value-letter avatars (50%).

This consistency is intentional for a healthcare brand: it avoids the visual noise of multiple radii and reinforces a calm, predictable, and trustworthy surface language.

### Photography Geometry

Hero imagery uses full-bleed video (16:9 cropped) with no corner radius — the video container extends edge-to-edge behind the dark gradient overlay. Service card images use a full-bleed top section (negative margins, 180px height) inside the 6px card container, with a hover scale(1.05) zoom. Profile images in the managed-care and about pages use rectangular 6px-rounded containers. There are no circular avatars outside the C.A.R.E. value letters.

## Components

> **No hover states documented in the front matter above** — the front-matter component entries document only Default states. Hover variants are listed separately where they exist. Variants live as separate component entries.

### Buttons

**`button-primary`** — the teal green filled CTA
- Background `{colors.primary}`, text `{colors.on-dark}`, type `{typography.button}` (1rem, 600 weight, no tracking), padding 0.75rem 1.5rem, border-radius `{rounded.default}`, 2px solid `{colors.primary}` border
- Hover state `button-primary-hover` — background `{colors.primary-dark}`, border `{colors.primary-dark}`
- Used for: "Explore Our Services", "View All Services", "Learn More About Our Hospital", "Submit Inquiry", "Verify Your Coverage"

**`button-outline`** — teal green outlined CTA
- Background transparent, text `{colors.primary}`, 2px solid `{colors.primary}` border, padding 0.75rem 1.5rem, border-radius `{rounded.default}`
- Hover: fills with `{colors.primary}`, text turns white
- Used for: secondary actions where gold is not needed, paired with primary as a visual alternative

**`button-gold`** — the warm gold filled CTA
- Background `{colors.accent-gold}`, text `{colors.on-dark}`, type `{typography.button}`, padding 0.75rem 1.5rem, border-radius `{rounded.default}`, 2px solid `{colors.accent-gold}` border
- Hover state `button-gold-hover` — background `#7b6d03`, border `#7b6d03`
- Used for: "Schedule a Tour", "Contact Us Today" — the secondary but emphasized action path

### Cards & Containers

**`card-light`** — the universal content card
- Background `{colors.canvas}`, border `1px solid {colors.hairline}`, border-radius `{rounded.default}`
- Hover state `card-hover`: `translateY(-5px)`, enhanced shadow, border shifts to `{colors.primary-light}`
- Used for: service cards, value cards, insurance plan cards, news tiles, form containers

**`card-dark`** — dark teal accent card
- Background `{colors.surface-dark}`, text `{colors.on-dark}`, border-radius `{rounded.default}`, no border
- Used for: welcome card on homepage (facility quick facts), "How to Apply" section in careers page

**`card-soft`** — pale green background card
- Background `{colors.surface-soft}`, border `1px solid {colors.hairline}`, border-radius `{rounded.default}`
- Used for: about-page stat specs card, referral information boxes

**`hero-text-card`** — the homepage hero text block
- No background — text sits directly on the video overlay
- Contains: hero badge pill + hero title + subtitle + dual CTA buttons + translucent stats bar
- Max-width 720px, positioned left on desktop

**`page-header`** — the recurring dark header band
- Background `{colors.surface-dark}`, text `{colors.on-dark}`, padding 4rem 0 3rem, bottom border 3px solid `{colors.primary}`
- Contains: H1 title + optional subtitle in `{colors.on-dark-mute}`
- Used on every interior page: about, services, careers, contact, legal pages

### Navigation

**`top-bar`** — the top-of-page utility bar
- Background `{colors.surface-dark}`, text `{colors.on-dark-mute}`, font-size 0.85rem, padding 0.4rem 0
- Bottom border: 1px solid `{colors.hairline-strong}`
- Holds: phone number, fax, email on the left; hospital license number on the right
- Right-side content hides below 992px

**`main-header`** — desktop top nav (sits below top bar)
- Background `{colors.canvas}`, height 75px, sticky positioning, z-index 100
- Shadow: `0 2px 10px rgba(0,0,0,0.05)`, bottom border: 1px solid `{colors.hairline}`
- Layout: logo lockup (52px height) flush left → center nav links (Home / About Us / Our Services / Careers / Contact Us) → right slot with "Schedule a Tour" CTA button + mobile hamburger
- Active nav link uses `{colors.primary}` on hover (no underline indicator — only color change)

**`nav-link`**
- Text `{colors.ink}`, font-weight 600, font-size 1.02rem, padding 0.5rem 0
- Hover: color shifts to `{colors.primary}`

**`dropdown-menu`** — the "Our Services" dropdown
- Background `{colors.canvas}`, border `1px solid {colors.hairline}`, box-shadow `0 10px 25px rgba(0,0,0,0.12)`, border-radius `{rounded.default}`
- Width 320px, animated opacity/visibility on parent hover
- Items: padding 0.5rem 1.25rem, text `{colors.body}`, font-size 0.92rem
- Item hover: background `{colors.surface-soft}`, text `{colors.primary}`

**Mobile Navigation**
- Fixed drawer (320px max-width, 85vw) slides in from right with `-5px 0 25px rgba(0,0,0,0.15)` shadow
- Header: logo + close button (×) in `{colors.primary}`
- Link list: font-weight 600, font-size 1.05rem, text `{colors.ink}`
- "Our Services" accordion expands inline with icon rotation
- Bottom section: address and phone in `{colors.mute}`
- Trigger: 3-bar hamburger icon in `{colors.primary}`

### Signature Components

**`hero-badge`** — the pill label above the hero title
- Background `rgba(14, 115, 85, 0.35)`, text `{colors.primary-pale}`, border `1px solid {colors.primary-light}`, border-radius `{rounded.pill}`
- Text: "Long-Term Acute Care Hospital (LTACH) • Stafford, TX"
- Positioned above the hero title with 1.25rem bottom margin

**`hero-stats-bar`** — the translucent stats band
- Background `rgba(7, 29, 24, 0.65)`, backdrop-filter `blur(10px)`, border `1px solid {colors.hairline-strong}`, border-radius `{rounded.default}`, padding 1.25rem
- 4-column grid (collapses to 2 on tablet, 1 on mobile)
- Each stat: strong number (1.35rem, white) + sub-label (0.78rem, `{colors.on-dark-mute}`)

**`hero-overlay`** — the video gradient overlay
- `linear-gradient(90deg, rgba(7,29,24,0.92) 0%, rgba(7,29,24,0.75) 50%, rgba(7,29,24,0.45) 100%)`
- Ensures white text readability against any video content

**`value-circle`** — the C.A.R.E. letter avatar
- Background `{colors.primary}`, text `{colors.on-dark}`, 60×60px circle, font-size 2rem, font-weight 800
- Used in the "Our Core Values" section with letters C, A, R, E
- Each sits inside a `card-light` with title and description below

**`value-chip`** — the mission section C.A.R.E. chip (alt version on homepage)
- Background `rgba(255,255,255,0.08)`, border `1px solid {colors.hairline-strong}`, border-radius `{rounded.pill}`, padding 0.75rem 1.5rem
- The emphasized letter within each chip uses `{colors.accent-mint}` (`#35c49b`)

**`footer-top`** — the main footer band
- Background `{colors.surface-dark}`, text `{colors.on-dark-mute}`, border-top 3px solid `{colors.primary}`
- 3-column grid (2fr 1fr 1fr) → single-column below 992px
- Columns: brand/contact info, "Who We Are" links, "Legal & Policy" links
- Footer title: white text, 40px-wide `{colors.primary}` underline pseudo-element
- Footer link hover: color shifts to `{colors.primary-light}`, shifts left 3px

**`footer-bottom`** — the footer baseline
- Background `#030d0a` (darker than `surface-dark`), border-top 1px solid `{colors.hairline-strong}`
- Contains: copyright line + "Designed & Developed" credit

## Do's and Don'ts

### Do
- Use `{colors.primary}` for the main CTA, section header underlines, stat numbers, value circles, footer accents, and link hover states
- Use `{colors.accent-gold}` for "Schedule a Tour" and "Contact Us" CTAs — the gold signals a different action class from the teal primary
- Set every H1 in weight 800 and every H2 in weight 700 — let weight contrast do the hierarchy work
- Use `{rounded.default}` (6px) universally on cards, buttons, inputs, and containers — single-radius consistency builds trust
- Pair white body bands with `{colors.surface-soft}` (`#f2f7f4`) or `{colors.bg-alt}` (`#fafdfb}\)) alternating bands; the pale green communicates health and care
- Open every interior page with the `page-header` dark teal band (3px `{colors.primary}` bottom border) and close with the dark footer
- Use the card hover lift (translateY(-5px) + shadow + primary-light border) as the primary interactive feedback for all card types
- Use the uppercase `sub-heading` token (0.85rem, 700 weight, 1px tracking) as a section eyebrow on every content section

### Don't
- Don't introduce saturated accent colors outside the teal-green family and the warm gold — no secondary blues, reds, or purples
- Don't apply decorative geometric flourishes, chevrons, abstract shapes, or background patterns — the logo lockup is the only mark
- Don't use multiple border-radius values for structural surfaces — 6px is the universal radius for cards, buttons, and inputs
- Don't use custom or imported web fonts — the system-native stack is intentional for performance and healthcare accessibility
- Don't run body type below 0.78rem — 0.78rem is the floor for legal fine print
- Don't use pure black (`#000000`) for body text — use `{colors.body}` (`#1b2c26`) or `{colors.ink}` (`#0c1a15`) for a softer, more approachable read
- Don't drop text opacity to create hierarchy — switch to `{colors.mute}` / `{colors.stone}` / `{colors.ash}` tokens instead
- Don't replace the Atrium Medical Center logo lockup with text-only branding; the logo is the primary brand identifier

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 576px | Single-column stack; hamburger nav; section padding 2.5rem; hero title 1.9rem; hero stats single column |
| Mobile-Large | 576–767px | Same column count; section padding still 2.5rem |
| Tablet | 768–991px | 2-column product grid collapses; hero title 2.4rem; hero stats 2×2; top-bar-right hidden |
| Desktop | 992–1279px | Full nav visible; `.grid-2` 2-column; footer 3-column |
| Desktop-Large | ≥ 1280px | Max-width 1280px container; full content width |

### Touch Targets

Every interactive element clears 44×44px on mobile. `button-primary` at 0.75rem vertical padding + 1.5rem horizontal padding meets WCAG-AAA touch target. Nav-link tap areas extend across the full 75px header row height. Hamburger icon uses invisible 44×44 hit box around the visible 25×3×3 bars.

### Collapsing Strategy

- **Top bar**: stays visible on every breakpoint; right-side content (license number) hides below 992px
- **Main header**: center nav links collapse into a hamburger drawer below 992px; "Schedule a Tour" CTA button stays visible until the drawer opens, then appears inside the drawer
- **Hero**: full-width video with overlay at every breakpoint; hero title scales down (3.2rem → 2.4rem → 1.9rem); stats bar collapses 4→2→1 columns
- **Content grid (`.grid-2`)**: 2-column on desktop collapses to single-column below 992px
- **Services grid**: auto-fit responsive columns (no fixed breakpoint — natural CSS grid wrapping)
- **Footer**: 3-column grid → single-column below 992px; footer links remain visible (no accordion)

### Image & Video Behavior

Hero video fills the full viewport width at every breakpoint with `object-fit: cover`. The gradient overlay is always present to ensure text readability. Service card images use a fixed-height (180px) full-bleed slot with hover zoom (scale 1.05). There are no art-direction crop swaps — the same images are used at every size. The logo lockup in the header adjusts height (52px desktop, ~44px mobile proportionally via `width: auto`).

## Iteration Guide

1. Focus on ONE component at a time; resist refactoring an entire section in one pass
2. Reference component names and tokens directly (`{colors.primary}`, `{typography.h2}`, `{rounded.default}`, `button-primary`) — do not paraphrase to hex/px in prose
3. Add new variants as separate component entries (`-hover`, `-active`, `-disabled`); never bury state inside prose
4. Default body to `{typography.body-md}`; reach for `{typography.caption}` for metadata rows; keep `{typography.sub-heading}` uppercase for section eyebrows
5. Keep `{colors.primary}` as the dominant signal; use `{colors.accent-gold}` sparingly — at most one gold CTA per section
6. When introducing a new section band, choose from `{colors.canvas}` / `{colors.surface-soft}` / `{colors.bg-alt}` / `{colors.surface-dark}` — four pre-defined surface modes is the entire surface vocabulary
7. All new CTAs should be one of three button types: `button-primary` (teal filled), `button-outline` (teal outlined), or `button-gold` (gold filled) — no fourth button variant
