# Republic — Galactic Design System

## 1. Visual Theme & Atmosphere

A dignified, democratic design system that balances classical authority with forward-looking optimism. Inspired by the architecture of the Senate rotunda and the clean lines of diplomatic vessels. The aesthetic communicates trust, openness, and institutional permanence — a visual covenant between tradition and progress.

**Mood:** dignified, democratic, classical-modern, hopeful, formal.

---

## 2. Color Palette & Roles

| Role | Value | Usage |
|---|---|---|
| Background | `#FFFFFF` | Pristine white — open and transparent governance |
| Surface | `#F5F7FA` | Soft blue-gray for cards, panels, alternate sections |
| Foreground / Text | `#1A2332` | Deep navy — authority without aggression |
| Text Muted | `#5A6A7F` | Secondary labels, timestamps, metadata |
| Text Dim | `#8A9AAF` | Tertiary information, placeholders |
| Border | `#D6DDE8` | Subtle structural dividers |
| Border Strong | `#B8C4D4` | Active states, focused inputs |
| Accent | `#0055A4` | Republic blue — primary actions, links, identity |
| Accent Hover | `#004080` | Deepened blue for hover |
| Premium / Gold | `#B8960C` | Senate gold — sparingly for premium tiers, seals, achievements |

**Rule:** Republic blue carries the democratic identity. Gold is ceremonial — use only for premium indicators, official seals, or tier badges. No other chromatic accents.

---

## 3. Typography Rules

- **Headlines (Display):** `Crimson Pro` or `Playfair Display`, weight 600–700, sentence case. Classical serif authority for major headings.
- **Headlines (UI):** `Inter`, weight 600, 18–24px, sentence case. Clean sans for interface hierarchy.
- **Body / UI:** `Inter`, weight 400–500, 15–16px, line-height 1.6.
- **Data / Code:** `SF Mono` or `JetBrains Mono`, weight 400.
- **Labels / Badges:** `Inter`, weight 500, 11–12px, uppercase, letter-spacing 0.04em.

**Scale:** 11 / 12 / 14 / 15 / 16 / 18 / 24 / 32 / 40 / 56 / 72 (px).  
**Headlines above 24px use serif.** UI headlines and all body use sans.  
**Text transform:** Labels and badges only are uppercase. Headlines and body are sentence case.

---

## 4. Component Stylings

**Buttons**
- Primary: `#0055A4` fill, `#FFFFFF` text, radius `6px`, padding 10/20, weight 600.
- Secondary: `#FFFFFF` fill, `#1A2332` text, 1px `#D6DDE8` border, radius `6px`.
- Ghost: transparent, `#0055A4` text, underline on hover.

**Cards**
- `#FFFFFF` or `#F5F7FA` background, 1px `#D6DDE8` border, radius `8px`.
- Hover: border shifts to `#B8C4D4`, subtle background tint to `#F5F7FA`. No shadow lift.

**Inputs**
- 1px `#D6DDE8` border, radius `6px`, padding 10/14, background `#FFFFFF`.
- Focus: 2px `#0055A4` ring, 2px offset.
- Placeholder: `#8A9AAF`.

**Tables**
- Header: 12px uppercase, weight 600, letter-spacing 0.04em, `#5A6A7F` text, bottom border 1px `#D6DDE8`.
- Row separators: 1px `#D6DDE8`. Hover row: `#F5F7FA` background.

**Badges / Tags**
- Background `#EEF2F7`, text `#0055A4`, radius `4px`, 11px weight 500.
- Premium / Official: background `#FDF8E8`, text `#B8960C`, border 1px `#E8D89A`.

---

## 5. Layout Principles

- **Max width:** 1200px marketing, 1400px app shells, 24px gutter.
- **Base unit:** 4px. Spacing scale: 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96.
- **Grid:** 12-column, generous whitespace. Republic layouts breathe.
- **Section rhythm:** 80px–96px vertical padding for marketing. 48px for dense app interfaces.
- **Alignment:** Left-aligned text by default. Centered only for hero statements and ceremonial declarations.

---

## 6. Depth & Elevation

**Border-based depth.** Shadows are extremely restrained:
- Cards and static surfaces: **no shadow.**
- Dropdowns / popovers: `0 2px 8px rgba(26, 35, 50, 0.06)` + 1px `#D6DDE8` border.
- Modals: `0 4px 24px rgba(26, 35, 50, 0.08)`.

**No shadow on buttons.** Depth comes from color contrast and border weight, not simulated light.

---

## 7. Do's and Don'ts

**Do:**
- Use serif typefaces for display headlines above 24px — classical authority is the Republic's visual signature.
- Keep Republic blue `#0055A4` as the primary interactive color on all actions.
- Use gold `#B8960C` sparingly and ceremonially — seals, premium badges, diplomatic indicators.
- Maintain generous whitespace; crowding suggests bureaucracy, not governance.
- Use rounded corners (6–8px) on interactive elements — approachability is a civic virtue.

**Don't:**
- Use pure black (`#000000`) for text — `#1A2332` is warmer and more dignified.
- Add aggressive accent colors (red, orange) — these belong to the military, not the Senate.
- Use sharp corners (0px radius) — the Republic is institutionally approachable.
- Drop shadows on cards or buttons — keep surfaces honest and flat.
- Use dark mode as a default — the Republic operates in the light.

---

## 8. Responsive Behavior

- Top navigation collapses to a slide-over drawer at 768px — elegant, not abrupt.
- Serif headlines scale down: 56px → 40px → 32px → 28px across breakpoints.
- Tables stack to card-based key-value pairs below 640px.
- Senate rotunda-inspired hero layouts collapse to single-column gracefully, maintaining vertical rhythm.

---

## 9. Agent Prompt Guide

> "Design in the Republic style: dignified, democratic, classical-modern. White `#FFFFFF` background, surfaces `#F5F7FA`, text `#1A2332`. Primary accent: Republic blue `#0055A4`. Ceremonial gold `#B8960C` for premium badges only. Crimson Pro or Playfair Display serif for headlines above 24px; Inter for body and UI. 6px radius on buttons and inputs, 8px on cards. 1px `#D6DDE8` borders. No shadows on static surfaces; minimal shadow on dropdowns only. Generous whitespace, 12-column grid, left-aligned text. No pure black, no aggressive colors, no dark mode default. Classical authority meets civic optimism."