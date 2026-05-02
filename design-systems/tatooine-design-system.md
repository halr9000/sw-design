# Tatooine — Frontier Weathered Console

## 1. Visual Theme & Atmosphere

A sun-bleached, analog-retro interface that feels like it was built from salvaged moisture farm equipment and cantina cash registers. The aesthetic mixes 1970s CRT monitors, Western wanted posters, and weathered industrial design. Surfaces are dusty, paint is cracked, and everything looks like it has been exposed to twin suns for too long. The mood is pragmatic, frontier-tough, and charmingly low-tech — functional despite the sand in the gears.

**Mood:** weathered, analog, retro-tech, warm, dusty, lived-in, frontier, pragmatic.

---

## 2. Color Palette & Roles

| Role | Value | Usage |
|---|---|---|
| Background | `#F5E6D3` | Sun-bleached sand — primary canvas |
| Surface | `#EDE0D4` | Lighter sand panel — cards, inputs, raised sections |
| Foreground / Text | `#3E2723` | Dark leather brown — primary text |
| Text Muted | `#A1887F` | Dusty grey-brown — secondary info |
| Border | `#D7CCC8` | Cracked paint line — dividers |
| Border Strong | `#BCAAA4` | Focused or active border |
| Accent | `#E65100` | Twin suns orange — actions, warnings, heat alerts |
| Accent Hover | `#BF360C` | Deep burnt orange |
| Secondary | `#5D4037` | Leather brown — navigation, structural elements |

**Rule:** This is a light theme. The canvas is sun-bleached, not dark. Orange is the heat of the suns — use it for primary actions and thermal warnings. Brown leather tones provide structure and grounding. Nothing should feel digital or sterile; everything should feel like it has been hand-tooled and left in the desert for a season.

---

## 3. Typography Rules

- **Headlines:** `Sancreek` or `Arvo`, weight 400, uppercase, letter-spacing `0.02em`. Western slab-serif personality — like a cantina sign or moisture farm equipment stencil.
- **Body / UI:** `Inter`, weight 400, size 15px, line-height 1.6. Clean enough for readability but not clinical.
- **Data / Metrics:** `Courier Prime`, weight 400, size 14px, tabular numbers. Thermal printer / receipt feel.
- **Labels / Badges:** `Inter`, weight 600, 11px, uppercase, letter-spacing `0.08em`.

**Scale:** 11 / 12 / 14 / 15 / 18 / 24 / 32 / 40 / 56 (px).
**Text transform:** Headlines uppercase. Labels uppercase. Body sentence case.
**Serif usage:** Allowed for headlines only. UI and data stay clean sans/mono.

---

## 4. Iconography Principles

- Style: Bold, hand-stamped, weathered. Slightly irregular is acceptable.
- Base size: `24x24px`.
- Stroke: `2px`, strong and visible.
- Corners: `1px`–`2px` — slightly worn, not machine-perfect.
- Color: Foreground or Text Muted default; Accent orange for actions; Secondary brown for nav.
- Set: Equipment, trade, transport, environmental, creature, hazard.
- Avoid sleek, glossy, or neon iconography.

---

## 5. Layout & Spacing Grid

- **Base unit:** `8px`.
- **Gutters:** `8px` — relaxed, breathable.
- **Max content width:** `1200px` — modest, frontier-appropriate.
- **Padding scale:** 8 / 16 / 24 / 32 / 48 (px).
- **Border radius scale:** `2px`–`4px` — slightly rounded but visibly imperfect, like hand-cut metal.
- **Shadows:** Minimal or none. If needed, warm, low, and soft: `0 2px 4px rgba(62, 39, 35, 0.08)`.

---

## 6. Component Styling

**Buttons**
- Primary: Background Accent (`#E65100`), white or Background-contrast text, border-radius `4px`, padding `12px 20px`, font 13px uppercase weight 600.
- Secondary: Background Secondary (`#5D4037`), Background (`#F5E6D3`) text, border-radius `4px`.
- Tertiary / Ghost: Transparent, Text Muted, hover Foreground.

**Inputs**
- Background Surface, Foreground text, `2px` Border, border-radius `4px`.
- Placeholder: Text Muted.
- `:focus`: `2px` Accent (`#E65100`) border + subtle orange outline glow.

**Cards & Panels**
- Background Surface, `2px` Border, `4px` radius, no cold shadow.
- Optional: faint `background-image: linear-gradient(to bottom, transparent 98%, rgba(188,170,164,0.3) 100%)` to suggest dust accumulation at bottom edge.

**Tables**
- Header: Background Surface, uppercase labels 11px, `border-bottom: 2px solid #D7CCC8`.
- Rows: alternating Background / Surface.
- Cell padding: `12px 16px`.

**Modals / Overlays**
- Backdrop: `rgba(62, 39, 35, 0.85)` — warm dark occlusion, like stepping into a cantina from the desert.
- Modal: Surface, `4px` radius, `2px` Border.

---

## 7. Motion & Interaction Guidance

- **Easing:** `cubic-bezier(0.4, 0, 0.2, 1)` — mechanical but slightly sticky, like an old lever.
- **Durations:** `150ms` hover, `200ms` transitions, `250ms` modal. Nothing too fast — equipment has mass.
- **Page load:** Simple fade-in. No complex choreography. Frontier tech doesn't animate extravagantly.
- **Hover:** Buttons darken slightly. Inputs show a hand-tooled focus ring.
- **Scroll:** Standard scroll. No parallax, no smooth-scroll hijacking.
- **Data updates:** Numbers snap instantly or tick slowly like an analog meter. No neon, no glow.

---

## 8. Accessibility Foundations

- Contrast: Foreground on Background `8.5:1`. Orange on Background `4.6:1` — sufficient for UI components and large text. Do not use orange on Surface for small body copy.
- Focus indicators: `2px` orange outline, `2px` offset. Clearly visible on light sand.
- Do not rely on subtle dust-gradient decorations for conveying information.
- Reduced motion: No changes needed — animations are already minimal.

---

## 9. Agent Guide / Summary

Render Acme Platform as a Tatooine moisture farm or trading post console. Light, sun-bleached sand palette with dark leather-brown text. Twin suns orange for primary actions and heat alerts. Typography should carry Western character — slab-serif headlines, typewriter data fonts. Borders are `2px` and slightly rough; corners are modestly rounded (`4px` max). No neon, no glow, no sleek shadows. Everything looks salvaged, repaired, and dust-caked. The interface should feel like it was built yesterday from parts that broke twenty years ago.