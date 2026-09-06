---
name: Ritun iOS System
colors:
  surface: '#faf9fe'
  surface-dim: '#dad9df'
  surface-bright: '#faf9fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f8'
  surface-container: '#eeedf3'
  surface-container-high: '#e9e7ed'
  surface-container-highest: '#e3e2e7'
  on-surface: '#1a1b1f'
  on-surface-variant: '#414755'
  inverse-surface: '#2f3034'
  inverse-on-surface: '#f1f0f5'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bc1'
  primary: '#0058bc'
  on-primary: '#ffffff'
  primary-container: '#0070eb'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#006e28'
  on-secondary: '#ffffff'
  secondary-container: '#6ffb85'
  on-secondary-container: '#00732a'
  tertiary: '#bc000a'
  on-tertiary: '#ffffff'
  tertiary-container: '#e2241f'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#72fe88'
  secondary-fixed-dim: '#53e16f'
  on-secondary-fixed: '#002107'
  on-secondary-fixed-variant: '#00531c'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4aa'
  on-tertiary-fixed: '#410001'
  on-tertiary-fixed-variant: '#930005'
  background: '#faf9fe'
  on-background: '#1a1b1f'
  surface-variant: '#e3e2e7'
typography:
  large-title:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Display', system-ui, sans-serif
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 41px
    letterSpacing: 0.37px
  title-1:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Display', system-ui, sans-serif
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: 0.36px
  title-2:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Display', system-ui, sans-serif
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.26px
  title-3:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Display', system-ui, sans-serif
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 25px
    letterSpacing: -0.45px
  headline:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.43px
  body:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.43px
  callout:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 21px
    letterSpacing: -0.32px
  subheadline:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.24px
  footnote:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: -0.08px
  caption-1:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0px
  caption-2:
    fontFamily: -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 13px
    letterSpacing: 0.07px
  quran-display:
    fontFamily: '''Amiri'', ''Traditional Arabic'', serif'
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: 0px
  quran-verse:
    fontFamily: '''Amiri'', ''Traditional Arabic'', serif'
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: 0px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  layout-margin-mobile: 16px
  layout-margin-tablet: 20px
  card-padding-sm: 12px
  card-padding-md: 16px
  card-padding-lg: 20px
  row-gap-sm: 8px
  row-gap-md: 12px
  row-gap-lg: 16px
  section-gap: 24px
  safe-bottom-tab: 49px
---

## Brand & Style

This design system translates the disciplined clarity of Apple Human Interface Guidelines into a dedicated mobile experience focused on intentionality, discipline, and reverence. The interface remains quiet and respectful, placing divine text and intentional habit-building at the focal point without superfluous decoration.

### Personality & Emotional Response
- **Serene & Focused:** Pure, uncrowded canvases that encourage calm recitation without anxiety or visual clutter.
- **Native & Seamless:** Feels indistinguishable from Apple's first-party iOS system software—instant familiarity, natural physical physics, crisp typography, and fluid micro-interactions.
- **Trustworthy & Precise:** Clear status indicators, predictable controls, and tactile feedback when reciting to unlock.

### Visual Style
- **Style Archetype:** Modern iOS HIG Minimalist with subtle translucent optical materials (`UIBlurEffectStyleSystemMaterialLight`).
- **Surface Philosophy:** Grouped table hierarchy utilizing high-contrast light system grays (`#F2F2F7`) as base canvas, paired with pure white cards (`#FFFFFF`), whisper-thin hairline separators (`#E5E5EA`), and featherweight ambient drop shadows.

## Colors

The palette is derived directly from the system tint primitives of iOS, applied with disciplined functional specificity.

### Functional Roles
- **System Blue (`#007AFF`):** Primary action tint. Used for actionable text buttons, navigation bar items, progress indicators, and interactive links.
- **System Green (`#34C759`):** Secondary success and validation tint. Exclusively communicates active toggles, completed recitations, verification streaks, and unlock affirmations.
- **System Red (`#FF3B30`):** Destructive actions, recording states, live microphone indicators, and error boundaries.
- **System Gray (`#8E8E93`):** Neutral metadata, secondary labels, unselected tab items, and unfilled tracks.

### System Surface Tiers
- **System Background (`#F2F2F7`):** Primary canvas background for grouped lists and app navigation views.
- **Secondary System Background / Card Surface (`#FFFFFF`):** High-elevation content groups, floating cards, sheets, and active modals.
- **Hairline Border & Separator (`#E5E5EA`):** 0.5pt (retina hairline) boundary lines and in-cell dividers.
- **Label Primary (`#000000` / `rgba(0,0,0,0.88)`):** First-order headlines, Quranic translations, and primary inputs.
- **Label Secondary (`rgba(60,60,67,0.60)`):** Subtitles, meta-tags, and contextual instructional text.
- **Label Tertiary (`rgba(60,60,67,0.30)`):** Placeholders, subtle timestamps, and disabled glyphs.

## Typography

The typography follows the native iOS dynamic type specifications with explicit optical tracking values.

- **System Typography:** Resolves through native system font stacks (`-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'SF Pro Display'`).
- **Script Typography (Quranic Text):** Utilizes `Amiri`, an authentic Naskh-style Arabic typeface. Amiri maintains deliberate line heights (never below 2.0x of font size) to ensure vowel markings (tashkeel) and diacritics render clearly without clipping.
- **RTL Alignment:** Quranic text elements use strict `dir="rtl"` with center or right alignment, while accompanying English translations retain native left-aligned system body styling.

## Layout & Spacing

Ritun adheres to the standardized grouped iOS container paradigm with a single-column, touch-first interface optimized for one-handed operation.

### Margins & Grid Model
- **Screen Margins:** Fixed 16px lateral padding on mobile viewports (<600px) and 20px on tablet interfaces.
- **Rhythm:** An 8-point base grid drives vertical layout rhythms, with 4px micro-spacers for in-cell alignments.
- **Grouped Sectioning:** Grouped lists and card decks maintain 24px bottom margins between logical sections, mirroring iOS Settings architecture.
- **Safe Area Insets:** Strict observance of top status bar safe areas and bottom navigation indicators. Content scrolls underneath navigation and tab bars with 44px top offset and 49px bottom offset respectively.

## Elevation & Depth

This system avoids synthetic drop shadows, harsh borders, or opaque cards. Depth is modeled after physical glass and subtle paper layers over soft system canvas.

### Surface Tiers & Shadow Metrics
- **Base Canvas (Level 0):** Solid `#F2F2F7`. Flat, inert backdrop.
- **Card Surface (Level 1):** Solid `#FFFFFF` elevated via:
  - **Hairline Stroke:** `1px` (or `0.5px` on high-DPI retina displays) solid `#E5E5EA`.
  - **Soft Shadow:** `box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05)`.
- **Active / Floating Modal (Level 2):** Pure `#FFFFFF` elevated via:
  - **Card Stroke:** `1px` solid `rgba(0, 0, 0, 0.06)`.
  - **Floating Shadow:** `box-shadow: 0 4px 14px rgba(0, 0, 0, 0.08)`.

### Frosted Translucency (Materials)
- **Top Navigation Bar & Bottom Tab Bar:** `background-color: rgba(249, 249, 249, 0.78); backdrop-filter: blur(20px) saturate(180%); -webkit-backdrop-filter: blur(20px) saturate(180%);`
- **Divider Hairline:** `border-bottom: 0.5px solid rgba(60, 60, 67, 0.29)`.

## Shapes

Corner curvature conforms strictly to iOS continuous squircle curvature (continuous corner smoothing).

- **Primary Cards & Modals:** 16px corner radius (`rounded-2xl`).
- **Inner Controls, Text Fields & Segmented Controls:** 12px corner radius (`rounded-xl`).
- **Buttons & Chips:** 10px corner radius for standard elements; pill-shaped (`9999px`) exclusively for circular recording buttons, tag pills, and audio scrubbers.
- **In-Cell Separators:** Hairline separators inset by 16px from the leading edge to align with label content, extending completely to the trailing margin.

## Components

### 1. Cards (Grouped Card Containers)
- **Background:** `#FFFFFF`
- **Border Radius:** 16px
- **Border:** 0.5px (or 1px) solid `#E5E5EA`
- **Shadow:** `0 1px 3px rgba(0,0,0,0.05)`
- **Behavior:** Houses recitation prompts, progress trackers, and verse insights. When grouped into multi-row cells, items use full-bleed dividers with 16px leading margins.

### 2. Buttons
- **Primary Action (Filled):** Background `#007AFF`, text `#FFFFFF`, height 50px, font weight 600, border radius 12px. Active press state dims brightness by 15% without expanding.
- **Secondary Action (Tinted):** Background `rgba(0, 122, 255, 0.12)`, text `#007AFF`, height 44px, border radius 10px.
- **Plain Action:** Transparent background, text `#007AFF`, font weight 400.
- **Destructive/Record Button:** Pulsing circular action button (72px x 72px) with `#FF3B30` core, surrounded by an ambient ring `rgba(255, 59, 48, 0.2)` during active speech analysis.

### 3. Native iOS Switch / Toggles
- **Track (Inactive):** `#E9E9EA`
- **Track (Active):** `#34C759`
- **Thumb:** `#FFFFFF`, diameter 27px, shadow `0 3px 8px rgba(0, 0, 0, 0.15)`.

### 4. Text Input & Search Fields
- **Background:** `rgba(118, 118, 128, 0.12)` (System Fill)
- **Border Radius:** 10px
- **Height:** 36px (Search), 44px (Standard Form Field)
- **Typography:** Body 17px with placeholder colored in Label Tertiary (`rgba(60, 60, 67, 0.3)`).

### 5. Quran Verse Display Tile
- **Background:** Pure `#FFFFFF`
- **Text Alignment:** Centered or right-to-left
- **Typography:** Displaying Amiri at 24px-30px, colored in `#000000` with 52px line-height.
- **Translation Text:** Subordinate text displayed below in System Subheadline (15px), colored in Label Secondary (`rgba(60,60,67,0.60)`).
- **Status Indicator:** A subtle micro-pill at the top right showing recitation target state (`#34C759` checkmark badge or audio waveform).

### 6. Navigation & Tab Bars
- **Navigation Bar:** Large title transitions dynamically into an inline title on scroll. Features standard iOS back arrow glyphs and text actions in `#007AFF`.
- **Bottom Tab Bar:** 49px fixed height, containing unselected icons in `#8E8E93` and active selection in `#007AFF` or `#34C759`.