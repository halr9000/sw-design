# Coruscant — Neon-Noir Urban Core

## 1. Visual Theme & Atmosphere

A dense, overwhelming interface designed for the vertical chaos of an ecumenopolis. The aesthetic fuses cyberpunk signage, Senate data dashboards, and speeder traffic streams into a single layered experience. Information is stacked, compressed, and always glowing. Light comes from neon, not the sun. The mood is sleepless, kinetic, and impossibly vertical — every pixel should feel like it is competing for attention in a canyon of holograms.

**Mood:** dense, neon-noir, overwhelming, kinetic, sleepless, high-tech, layered.

---

## 2. Color Palette & Roles

| Role | Value | Usage |
|---|---|---|
| Background | `#0A0A0A` | Absolute void — the space between buildings |
| Surface | `#171717` | Carbon-fibre panel — cards, modules, nav |
| Foreground / Text | `#F5F5F5` | Harsh white — primary text, cutting through noise |
| Text Muted | `#737373` | Drowned grey — secondary info, metadata |
| Border | `#262626` | Grid line — structural dividers |
| Border Strong | `#404040` | Active border, selected state |
| Accent | `#A855F7` | Hologram purple — ads, nightlife, Senate highlights, primary CTAs |
| Accent Secondary | `#22D3EE` | Neon cyan — traffic, data streams, power, links |
| Alert | `#EAB308` | Speeder taxi yellow — warnings, urgent notifications |

**Rule:** Purple and cyan must glow. Use `box-shadow` and text shadows to simulate neon emission. Yellow is emergency-only — taxi cabs and collision alerts. The canvas is absolute black so that every other color reads as emitted light, not reflected paint.

---

## 3. Typography Rules

- **Headlines:** `Inter` or `Space Grotesk`, weight 800, uppercase, letter-spacing `-0.02em`, tight and compressed. Headlines should feel like building signage — maximum impact, minimum space.
- **Body / UI:** `Inter`, weight 400, size 13px, line-height 1.4. Dense. Information-rich.
- **Data / Metrics:** `JetBrains Mono`, weight 400, size 12px, tabular numbers. Packed into dashboards.
- **Labels / Badges:** `Inter`, weight 600, 10px, uppercase, letter-spacing `0.08em`.

**Scale:** 10 / 11 / 12 / 13 / 14 / 18 / 24 / 32 / 48 (px).
**Text transform:** Headlines and labels uppercase. Body sentence case but highly abbreviated where possible.
**No wide serifs.** Condensed, tall, or compressed forms preferred for headlines.

---

## 4. Iconography Principles

- Style: Geometric, signage-inspired, neon-fill friendly.
- Base size: `20x20px` — compact for dense UIs.
- Stroke: `1px`, sharp corners.
- Color: Foreground or Text Muted default; Accent purple with glow for primary; Accent cyan with glow for active.
- Fill: Icons may use solid fill with `box-shadow: 0 0 6px currentColor` to simulate neon tubes.
- Set: Transit, commerce, communication, utilities, entertainment, alerts.

---

## 5. Layout & Spacing Grid

- **Base unit:** `4px` — extreme granularity for dense packing.
- **Gutters:** `2px`–`4px` — minimal breathing room.
- **Max content width:** `1600px` — wide dashboards with multiple simultaneous panels.
- **Padding scale:** 4 / 8 / 12 / 16 / 24 / 32 / 48 (px).
- **Border radius scale:** `2px` universally — slight rounding to avoid raw pixel harshness, but nothing soft.
- **Shadows:** Neon glows only. `box-shadow: 0 0 8px rgba(168, 85, 247, 0.4)` for purple emphasis. `0 0 6px rgba(34, 211, 238, 0.5)` for cyan data.

---

## 6. Component Styling

**Buttons**
- Primary: Background Accent (`#A855F7`), white text, border-radius `2px`, padding `10px 16px`, font 12px uppercase weight 600, `box-shadow: 0 0 12px rgba(168,85,247,0.4)`.
- Secondary: Background Surface, Foreground text, `1px` Border, `2px` radius.
- Tertiary: Transparent, Accent Secondary text, hover glow.

**Inputs**
- Background Background, Foreground text, `1px` Border, border-radius `2px`.
- `:focus`: `1px` Accent Secondary + `box-shadow: 0 0 8px rgba(34,211,238,0.3)`.

**Cards & Panels**
- Background Surface, `1px` Border, `2px` radius, no conventional shadow unless glowing for emphasis.
- Dashboard panels may stack vertically with `1px` Border separators.

**Tables**
- Header: Background Surface, uppercase labels 10px, `border-bottom: 1px solid Border Strong`.
- Cell padding: `8px 10px` — compact.
- Row hover: Background slightly elevated (`#1f1f1f`).

**Modals / Overlays**
- Backdrop: `rgba(10, 10, 10, 0.92)` — near-total occlusion.
- Modal: Surface, `2px` radius, `1px` Border Strong, optional purple top border `3px`.

---

## 7. Motion & Interaction Guidance

- **Easing:** `cubic-bezier(0.32, 0, 0.67, 0)` — snappy, electronic, abrupt stops.
- **Durations:** `80ms` hover, `120ms` panel shifts, `200ms` modal open.
- **Page load:** Hard cuts and rapid slides. No gentle fades. Panels snap in from off-canvas.
- **Hover:** Buttons intensify glow. Links underline with a cyan `1px` line that draws left-to-right over `150ms`.
- **Scroll:** No smooth scroll. Raw, immediate. Fixed headers and sidebars remain locked.
- **Data updates:** Ticker-style scrolling for feeds. Numbers flip like split-flap displays. Neon blinks for alerts.

---

## 8. Accessibility Foundations

- Contrast: Foreground on Background `19:1`. Purple on Background `7:1` — excellent. Cyan on Background `10:1`.
- Glow shadows are decorative; ensure color contrast stands alone without them.
- Focus indicators: `2px` cyan outline, `2px` offset. High visibility against black.
- Avoid purple/cyan adjacency for colorblind users — pair with text labels or icon shape differences.
- Reduced motion: Disable ticker scrolls, neon blinks, and slide entrances. Instant state changes only.

---

## 9. Agent Guide / Summary

Convert Acme Platform into a Coruscant city-management dashboard. Absolute black canvas. Neon purple and cyan as the only living colors — they must glow. Typography is compressed, dense, uppercase, and aggressive. Layouts are wide, multi-paneled, and vertically stacked with razor-thin borders. Rounding is `2px` max. Motion is electronic and snappy. No white backgrounds, no warm tones, no breathing room. This is an interface that never sleeps, built for a planet where the sun is a rumor and every pixel is a light source.