# Imperial — Galactic Design System

## 1. Visual Theme & Atmosphere

An austere, totalitarian design system built on absolute geometric discipline. Every element submits to the grid. The aesthetic communicates unyielding authority, calculated efficiency, and cold intimidation — the visual signature of a galactic empire that tolerates no deviation. Surfaces are matte and oppressive; light is a controlled resource, not an ambient quality.

**Mood:** authoritarian, precise, cold, imposing, severe.

---

## 2. Color Palette & Roles

| Role | Value | Usage |
|---|---|---|
| Background | `#0A0A0C` | Deepest space black — primary canvas |
| Surface | `#141416` | Elevated panels, cards, nav containers |
| Foreground / Text | `#E8E8EB` | Stark, bone-white primary text |
| Text Muted | `#6B6B70` | Secondary labels, metadata, timestamps |
| Border | `#2A2A2E` | Structural dividers, hairline rules |
| Border Strong | `#3A3A40` | Active states, selected borders |
| Accent / Alert | `#C8102E` | Imperial red — warnings, primary CTAs, critical actions ONLY |
| Accent Hover | `#A00D24` | Darkened red for hover states |

**Rule:** Imperial red is a controlled substance. It appears only on primary actions, error states, and system alerts. Never as background fill, never as decorative highlight. The palette is achromatic by design; red is the color of consequence, not branding.

---

## 3. Typography Rules

- **Headlines:** `Space Grotesk` or `Inter`, weight 600–700, uppercase, letter-spacing `0.08em`. All headlines speak in commands.
- **Body / UI:** `Inter`, weight 400–500, size 14–16px, line-height 1.5.
- **Data / Metrics:** `JetBrains Mono` or `SF Mono`, weight 400, tabular numbers.
- **Labels / Badges:** `Inter`, weight 600, 11–12px, uppercase, letter-spacing `0.1em`.

**Scale:** 11 / 12 / 14 / 16 / 20 / 28 / 40 / 56 / 72 (px).  
**Text transform:** Headlines and labels are UPPERCASE by default. Body remains sentence case.  
**No serif typefaces.** No italics for emphasis — use weight 700.

---

## 4. Component Stylings

**Buttons**
- Primary: `#C8102E` fill, `#FFFFFF` text, radius `0px`, padding 10/20, weight 600, uppercase, letter-spacing 0.06em.
- Secondary: `#141416` fill, `#E8E8EB` text, 1px `#2A2A2E` border, radius `0px`.
- Ghost: transparent, `#E8E8EB` text, 1px `#2A2A2E` border on hover.

**Cards**
- `#141416` background, 1px `#2A2A2E` border, radius `0px`.
- Hover: border shifts to `#3A3A40`. No lift, no shadow.

**Inputs**
- 1px `#2A2A2E` border, radius `0px`, padding 10/14.
- Focus: 1px `#6B6B70` border, no glow, no ring.
- Background: `#0A0A0C` or `#141416`.

**Tables**
- Header: uppercase, 12px, weight 600, letter-spacing 0.06em, bottom border 1px `#3A3A40`.
- Row separators: 1px `#2A2A2E`. Alternating rows are identical — no zebra striping.

**Badges / Tags**
- Background `#1F1F23`, text `#6B6B70`, 1px `#2A2A2E` border, radius `0px`, 10px uppercase.

---

## 5. Layout Principles

- **Max width:** 1280px, centered.
- **Base unit:** 8px. Spacing scale: 8 / 16 / 24 / 32 / 48 / 64 / 96.
- **Grid:** 12-column, 24px gutter. Elements snap to grid — no organic misalignment.
- **Section padding:** 64px vertical minimum. Breathing room is permitted, but it is regimented breathing room.
- **Symmetry:** Prefer centered and balanced compositions. Asymmetry is a sign of disorder.

---

## 6. Depth & Elevation

**Flat.** Absolutely flat. No box-shadows on any surface.  
Depth is expressed exclusively through:
- Background color contrast (`#0A0A0C` vs. `#141416`)
- Border weight (`#2A2A2E` vs. `#3A3A40`)
- Opacity shifts on text hierarchy

**No elevation tokens.** There are no floating layers in the Empire — only stacked plates of durasteel.

---

## 7. Do's and Don'ts

**Do:**
- Use red as punctuation, not paragraph — one accent per view maximum.
- Keep every corner at `0px` radius. Sharpness is strength.
- Use uppercase and wide letter-spacing for all labels, nav items, and headings.
- Align everything to the 8px grid with mathematical precision.
- Use mono typefaces for data, metrics, and system readouts.

**Don't:**
- Add a second accent color. Blue, green, gold — these are the colors of rebellion.
- Use rounded corners on any element. Curves imply weakness.
- Apply drop shadows, glows, or blurs. Light does not bleed under Imperial control.
- Use gradients on backgrounds or buttons. Surfaces are uniform.
- Introduce decorative illustrations, organic shapes, or playful iconography.

---

## 8. Responsive Behavior

- Navigation collapses to a full-screen overlay at 768px — not a drawer, a takeover.
- Headlines scale down one step per breakpoint but remain uppercase.
- Tables transform to stacked data rows below 640px, retaining mono typeface for values.
- Touch targets maintain minimum 44px — the Empire is ruthless, not inaccessible.

---

## 9. Agent Prompt Guide

> "Design in the Imperial style: totalitarian, cold, and geometrically precise. Background `#0A0A0C`, surfaces `#141416`, text `#E8E8EB`. One accent only: Imperial red `#C8102E` for CTAs and alerts. Space Grotesk or Inter headlines, ALL UPPERCASE with wide letter-spacing. JetBrains Mono for data. Zero border-radius everywhere. 1px hairline borders `#2A2A2E`. No shadows, no gradients, no second accent color. Flat surfaces, rigid 8px grid, 12-column layout. Sharp corners are mandatory. Red is the color of consequence — use sparingly."