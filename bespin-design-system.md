# Bespin — Cloud City Elegance

## 1. Visual Theme & Atmosphere

A warm, retro-futuristic design system evoking the golden-age elegance of a floating metropolis. The aesthetic merges 1930s Art Deco with 1980s science-fiction luxury — brass fixtures, sunset gradients, and airy proportions. Surfaces feel like polished wood and burnished metal; light behaves like late-afternoon sun filtering through clouds. Every element should suggest expensive taste and optimistic ambition.

**Mood:** elegant, retro-futuristic, warm, luxurious, airy, optimistic, art deco.

---

## 2. Color Palette & Roles

| Role | Value | Usage |
|---|---|---|
| Background | `#1C1917` | Deep warm charcoal — like a private lounge wall |
| Surface | `#292524` | Warm bronze panel — cards, nav, elevated sections |
| Foreground / Text | `#FAFAF9` | Warm white — primary text |
| Text Muted | `#A8A29E` | Soft taupe — secondary descriptions, timestamps |
| Border | `#44403C` | Bronze trim — dividers, hairlines |
| Border Strong | `#57534E` | Active or focused border |
| Accent | `#F59E0B` | Amber gold — primary actions, luxury highlights, key data |
| Accent Hover | `#D97706` | Deepened amber for hover |
| Secondary Accent | `#67E8F9` | Sky cyan — atmospheric references, secondary info, links |

**Rule:** Amber gold is the signature of wealth and action. Use it sparingly on primary CTAs, active navigation, and highlighted metrics. Sky cyan is atmospheric — use it for links, hover states, and weather/environmental readouts. The overall warmth must feel like a sunset, not a campfire.

---

## 3. Typography Rules

- **Headlines:** `Playfair Display` or `Crimson Pro`, weight 600, sentence case, letter-spacing `-0.02em`. Elegant, editorial, with classical serifs that speak of old money and new technology.
- **Body / UI:** `Inter` or `Source Sans 3`, weight 400, size 16px, line-height 1.6. Generous and breathable.
- **Data / Metrics:** `JetBrains Mono`, weight 400, size 14px, tabular numbers.
- **Labels / Badges:** `Inter`, weight 500, 12px, uppercase, letter-spacing `0.06em`.

**Scale:** 12 / 14 / 16 / 18 / 20 / 28 / 40 / 56 / 72 (px).
**Text transform:** Headlines are sentence case. Labels and badges are uppercase.
**Serifs allowed ONLY in headlines.** UI elements remain sans-serif for clarity.

---

## 4. Iconography Principles

- Style: Rounded, art-deco influenced, slightly ornamental but clean.
- Base size: `24x24px`.
- Stroke: `1.5px`, rounded caps and joins.
- Corners: `4px` soft radius.
- Color: Foreground or Text Muted by default; Accent amber for primary actions; Sky cyan for links.
- Set: Elegant navigation, hospitality, administrative, environmental.
- Avoid sharp military or industrial iconography.

---

## 5. Layout & Spacing Grid

- **Base unit:** `8px`.
- **Gutters:** `8px` — generous, breathable.
- **Max content width:** `1400px` — spacious layouts befitting a luxury setting.
- **Padding scale:** 8 / 16 / 24 / 32 / 48 / 64 / 96 (px).
- **Border radius scale:** 4 / 8 / 12 / 16 / 24 (px). Cards and modals get `8px` or `12px`. Buttons get `8px`.
- **Shadows:** Soft, warm, diffused. `0 4px 20px rgba(0,0,0,0.15)` for cards. `0 2px 8px rgba(0,0,0,0.1)` for buttons.

---

## 6. Component Styling

**Buttons**
- Primary: Background Accent (`#F59E0B`), Background-contrast text (`#1C1917`), border-radius `8px`, padding `14px 24px`, font 14px weight 600.
- Secondary: Background Surface, Foreground text, `1px` Border, border-radius `8px`.
- Tertiary / Ghost: Transparent, Text Muted, hover Foreground + underline.

**Inputs**
- Background Background, Foreground text, `1px` Border, border-radius `8px`.
- Placeholder: Text Muted.
- `:focus`: `1px` Border Strong + `box-shadow: 0 0 0 3px rgba(245, 158, 11, 0.2)`.

**Cards & Panels**
- Background Surface, `1px` Border, `8px` border-radius, soft warm shadow.
- Hover: subtle lift `translateY(-2px)` + shadow intensifies slightly.

**Tables**
- Header: Background Surface, uppercase labels 12px, `border-bottom: 1px solid Border Strong`.
- Rows: alternating subtle tone shifts.
- Cell padding: `16px`.

**Modals / Overlays**
- Backdrop: `rgba(28, 25, 23, 0.85)` with `backdrop-filter: blur(8px)`.
- Modal surface: Surface, `12px` radius, warm shadow.

---

## 7. Motion & Interaction Guidance

- **Easing:** `cubic-bezier(0.25, 0.1, 0.25, 1)` — smooth, gliding, unhurried. Like an airspeeder banking through clouds.
- **Durations:** `200ms` for hover, `300ms` for panel transitions, `400ms` for modal entrance.
- **Page load:** Elements fade up gently with `translateY(12px -> 0)` and opacity `0 -> 1`. Stagger by `50ms` per section.
- **Hover:** Buttons gain a warm glow (`box-shadow: 0 0 12px rgba(245,158,11,0.3)`). Cards lift `2px`.
- **Scroll:** Smooth scrolling enabled. Subtle parallax on hero imagery (0.5x rate) if applicable.
- **Data updates:** Numbers count up smoothly over `600ms`. Charts animate with graceful curves.

---

## 8. Accessibility Foundations

- Contrast: Foreground on Background `16:1`. Amber on Background `4.6:1` — sufficient for large text and UI components, but never use amber on Surface for small text (contrast drops too low).
- Focus rings: `3px` amber glow at `20%` opacity. Visible and elegant.
- Reduced motion: Disable parallax, fade-ins become instant, hover lifts become static color changes only.

---

## 9. Agent Guide / Summary

Transform Acme Platform into a Cloud City administrative dashboard. Use warm, deep charcoals and bronzes as the canvas. Let amber gold and sky cyan provide elegant punctuation. Typography should feel editorial — serif headlines, generous sans-serif body text. Rounded corners (`8px`–`12px`) and soft warm shadows are mandatory. No sharp angles, no cold mechanical precision. This is luxury administration at 60,000 feet. Every interaction should glide.