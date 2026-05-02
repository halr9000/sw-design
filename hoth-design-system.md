# Hoth — Tactical Ice Base Interface

## 1. Visual Theme & Atmosphere

A frigid, survivalist interface designed for military field operations in extreme cold. The aesthetic borrows from medical monitors, tactical radar displays, and ice-encrusted equipment. Everything feels filtered through a frost layer — clinical, isolated, and built for function over comfort. Subtle scan-line textures and condensation borders reinforce the sense of operating in an unforgiving environment.

**Mood:** frigid, stark, clinical, survivalist, tactical, isolating.

---

## 2. Color Palette & Roles

| Role | Value | Usage |
|---|---|---|
| Background | `#0B1120` | Arctic night — deep blue-black canvas |
| Surface | `#162032` | Ice-steel panels, tactical modules |
| Foreground / Text | `#E2E8F0` | Frost white — primary text, headings |
| Text Muted | `#475569` | Cold grey-blue — secondary labels, timestamps |
| Border | `#334155` | Ice-fracture dividers |
| Border Strong | `#475569` | Active field borders, selected units |
| Accent / Alert | `#F97316` | Thermal orange — heat signatures, warnings, critical alerts |
| Accent Secondary | `#38BDF8` | Sensor blue — comms active, scanning, life-support OK |
| Accent Hover | `#C2410C` | Darkened thermal orange for interaction |

**Rule:** Thermal orange is reserved for alert states, critical actions, and heat-source indicators only. Sensor blue indicates healthy/active systems. The palette should feel hypothermic — if a color feels warm or inviting, it does not belong here.

---

## 3. Typography Rules

- **Headlines:** `JetBrains Mono` or `Space Grotesk`, weight 700, uppercase, letter-spacing `0.12em`. Headlines read like stamped supply crate labels or field manual headers.
- **Body / UI:** `Inter`, weight 400, size 14px, line-height 1.5.
- **Data / Metrics:** `JetBrains Mono`, weight 400, tabular numbers, size 13px. Temperature, coordinates, unit counts.
- **Labels / Badges:** `Inter`, weight 600, 11px, uppercase, letter-spacing `0.1em`.

**Scale:** 11 / 12 / 13 / 14 / 18 / 24 / 32 / 48 (px).
**Text transform:** Headlines and labels are UPPERCASE by default. Body remains sentence case.
**No decorative serifs.** No italic emphasis — use weight 700 or Accent Secondary color.

---

## 4. Iconography Principles

- Style: Sharp, utilitarian, military stencil-inspired.
- Base size: `24x24px`.
- Stroke: `1.5px`, consistent, no fill.
- Corners: `0px` — absolutely sharp.
- Color: Foreground or Text Muted by default; Accent orange for alerts; Sensor blue for active/online states.
- Set: Navigation, equipment, environmental, personnel, medical.
- No rounded social icons. No playful illustration.

---

## 5. Layout & Spacing Grid

- **Base unit:** `8px`.
- **Gutters:** `4px` — tight, tactical packing.
- **Max content width:** `1280px` — wide but not expansive; interfaces should feel like a cramped command center viewport.
- **Padding scale:** 8 / 12 / 16 / 24 / 32 / 48 (px).
- **Border radius scale:** `0px` universally — everything is a frozen block.
- **Shadows:** None. Use `1px` Border or `1px` Border Strong to create elevation.

---

## 6. Component Styling

**Buttons**
- Primary: Background Accent (`#F97316`), Foreground text (`#0B1120`), border-radius `0px`, padding `12px 20px`, font 12px uppercase weight 600.
- Secondary: Background Surface, Foreground text, `1px` Border, border-radius `0px`.
- Tertiary / Ghost: Transparent background, Text Muted, hover Foreground.

**Inputs**
- Background Background, Foreground text, `1px` Border, border-radius `0px`.
- Placeholder: Text Muted.
- `:focus`: `1px` Border Strong (`#475569`) + `outline: 2px solid #38BDF8; outline-offset: 2px;`.

**Cards & Panels**
- Background Surface, `1px` Border, no shadow, border-radius `0px`.
- Optional: `border-left: 2px solid` Accent or Accent Secondary to indicate status.

**Tables**
- Header: Background Surface, uppercase labels 11px.
- Rows: alternating Background / slightly elevated Surface.
- Cell padding: `12px 16px`.
- Selected row: `border-left: 2px solid #38BDF8`.

**Modals / Overlays**
- Backdrop: `rgba(11, 17, 32, 0.9)` with `backdrop-filter: blur(2px)` (frosted viewport).
- Modal surface: Surface, `1px` Border Strong, no radius.

---

## 7. Motion & Interaction Guidance

- **Easing:** `cubic-bezier(0.4, 0, 0.2, 1)` — mechanical, abrupt.
- **Durations:** Fast. `100ms` for hover states, `150ms` for panel transitions, `200ms` for modal open/close.
- **Page load:** Elements do not fade in gracefully — they snap into place like a monitor warming up.
- **Hover:** Buttons darken. Links underline instantly with `1px` Foreground.
- **Scroll:** No parallax. No smooth-scroll easing. Raw, immediate.
- **Data updates:** Numbers tick rapidly (tabular font prevents jitter). Sensor blips pulse Accent Secondary twice then hold steady.

---

## 8. Accessibility Foundations

- Minimum contrast ratios: Foreground on Background `15:1+`. Accent orange on Background `4.5:1`.
- Never rely on color alone for status — pair with text labels or iconography. A thermal reading must show the number *and* the orange alert state.
- Focus indicators: `2px` Sensor blue outline, `2px` offset. Always visible.
- Reduced motion: Disable blip animations; static hold states only.

---

## 9. Agent Guide / Summary

Apply the Hoth interface to every Acme Platform element. Replace the default warmth with arctic severity. Use `0px` border-radius universally. Typography must feel stamped or stenciled — uppercase, widely tracked, utilitarian. Color must remain hypothermic: deep blue-blacks, frost whites, cold greys. Orange is thermal alarm; blue is active sensor. No rounded corners, no soft shadows, no friendly gradients. This is a command console built inside a frozen bunker.