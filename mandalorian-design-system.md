# Mandalorian — Clan Design System

## 1. Visual Theme & Atmosphere

A battle-worn, pragmatic design system forged from utility and honored tradition. Surfaces carry the patina of use — beskar steel, weathered leather, sun-bleached canvas. The aesthetic communicates competence, clan loyalty, and unspoken toughness. Nothing is decorative without purpose; every scratch tells a story. This is the UI of warriors who respect the work, not the polish.

**Mood:** battle-worn, pragmatic, clan-oriented, rugged, utilitarian.

---

## 2. Color Palette & Roles

| Role | Value | Usage |
|---|---|---|
| Background | `#1C1C1E` | Deep forge-dark — primary canvas |
| Surface | `#2A2A2C` | Beskar steel panels, cards, nav |
| Surface Elevated | `#3A3A3C` | Active selections, hover states |
| Foreground / Text | `#E4E0D8` | Warm bone-white — aged, not sterile |
| Text Muted | `#8A8580` | Secondary labels, battle-log timestamps |
| Text Dim | `#6A6560` | Tertiary information, disabled states |
| Border | `#4A4A4C` | Welded-seam dividers |
| Border Strong | `#5A5A5C` | Active borders, selected clan tabs |
| Accent / Clan Mark | `#D4652A` | Burnt orange — clan sigil color, identity, primary actions |
| Accent Hover | `#B85520` | Darkened orange for pressed/hover |
| Leather / Earth | `#6B4E3D` | Deep leather brown for premium surfaces, heritage elements |
| Sand / Neutral | `#C4B9A8` | Desert sand for subtle highlights, canvas textures |

**Rule:** Burnt orange is the clan mark — it appears on primary actions, active navigation, clan badges, and critical callouts. Brown and sand are atmospheric, never competing with orange. The palette is earth-forged: everything looks like it survived a sandstorm.

---

## 3. Typography Rules

- **Headlines:** `Barlow Condensed` or `Oswald`, weight 600–700, uppercase, letter-spacing 0.04em. Sturdy, compact, built for impact.
- **Body / UI:** `Inter`, weight 400–500, 14–16px, line-height 1.55.
- **Data / Metrics / Clan Codes:** `JetBrains Mono` or `Share Tech Mono`, weight 400, uppercase for codes.
- **Labels / Badges:** `Barlow Condensed`, weight 500, 11–12px, uppercase, letter-spacing 0.06em.
- **Clan Sigils / Ornamental:** Custom sigil icons or geometric marks — never text-as-decoration.

**Scale:** 11 / 12 / 14 / 16 / 20 / 28 / 36 / 48 / 64 (px).  
**Headlines are always uppercase.** Body is sentence case. Clan designations and ranks are uppercase mono.

---

## 4. Component Stylings

**Buttons**
- Primary: `#D4652A` fill, `#1C1C1E` text, radius `4px`, padding 10/20, weight 600, uppercase.
- Secondary: `#2A2A2C` fill, `#E4E0D8` text, 1px `#4A4A4C` border, radius `4px`.
- Ghost: transparent, `#E4E0D8` text, underline in `#D4652A` on hover.
- **Texture note:** Primary buttons may carry a subtle brushed-metal texture at 4% opacity.

**Cards**
- `#2A2A2C` background, 1px `#4A4A4C` border, radius `4px`.
- Hover: background shifts to `#3A3A3C`, border to `#5A5A5C`. No shadow — surfaces are solid.
- Optional: very subtle top-edge highlight `#5A5A5C` at 1px to suggest a beveled plate.

**Inputs**
- 1px `#4A4A4C` border, radius `4px`, padding 10/14, background `#1C1C1E`.
- Focus: 1px `#D4652A` border, no glow.
- Placeholder: `#6A6560`.

**Clan Badges / Rank Insignia**
- Circular or hexagonal containers, `#2A2A2C` background, 2px `#D4652A` border.
- Radius depends on shape: `50%` for circular sigils, `4px` for hexagonal marks.
- Mono typeface for rank codes inside.

**Tables / Battle Logs**
- Header: 12px uppercase, weight 600, `#8A8580` text, bottom border 2px `#4A4A4C`.
- Rows: 1px `#3A3A3C` separators. Hover: `#2A2A2C` background.
- Timestamps and coordinates in mono.

---

## 5. Layout Principles

- **Max width:** 1280px, but content often feels wider — use full-bleed sections with contained text.
- **Base unit:** 8px. Spacing scale: 8 / 16 / 24 / 32 / 48 / 64 / 96.
- **Grid:** 12-column, 20px gutter. Practical, not precious.
- **Section rhythm:** 48px–64px vertical. Mandalorian layouts are information-dense — warriors don't scroll for fluff.
- **Asymmetry:** Slight intentional asymmetry is permitted and even preferred. Perfect symmetry is for droids.

---

## 6. Depth & Elevation

**Sculpted flatness.** No simulated drop shadows — depth is physical:
- Background contrast (`#1C1C1E` vs. `#2A2A2C` vs. `#3A3A3C`) suggests stacked armor plates.
- 1px–2px borders are the primary separation method.
- Optional 1px top highlight on cards to suggest a beveled edge — like folded beskar.
- **No blur, no glow, no glassmorphism.** Surfaces are solid metal, not holograms.

---

## 7. Do's and Don'ts

**Do:**
- Use burnt orange `#D4652A` as the clan identity mark on all primary actions and active states.
- Keep corners at 4px radius — sharp enough to be serious, rounded enough to be hand-worn.
- Use mono typefaces for all data, timestamps, coordinates, and clan codes.
- Suggest texture through subtle opacity layers — brushed steel, canvas weave, leather grain at 2–4%.
- Use asymmetry in layouts where it serves information hierarchy.
- Keep everything information-dense; white space is earned, not assumed.

**Don't:**
- Use pristine glossy finishes or glass effects — nothing in this system is untouched.
- Add bright primary colors (blue, green, yellow) — this is not a civilian interface.
- Use excessive rounded corners (above 6px) — curves suggest comfort, not combat.
- Apply drop shadows or elevation layers — depth comes from material contrast, not light simulation.
- Use decorative illustrations without purpose — every visual element must serve a function or carry clan meaning.

---

## 8. Responsive Behavior

- Navigation becomes a bottom-bar or compact top bar at 768px — battle-readiness means thumb-accessible controls.
- Headlines scale aggressively: 64px → 48px → 36px → 28px.
- Tables collapse to mission-brief cards below 640px, preserving mono data fields.
- Clan sigils and rank badges maintain minimum 40px touch targets.

---

## 9. Agent Prompt Guide

> "Design in the Mandalorian style: battle-worn, pragmatic, clan-honored. Background `#1C1C1E`, surfaces `#2A2A2C`, text `#E4E0D8`. One clan mark: burnt orange `#D4652A` for all primary actions and identity. Leather brown `#6B4E3D` and sand `#C4B9A8` as atmospheric earth tones only. Barlow Condensed or Oswald headlines, ALL UPPERCASE. Inter body. JetBrains Mono for all data, timestamps, and clan codes. 4px radius on everything. 1px `#4A4A4C` borders. No shadows, no glass, no gloss — depth from stacked color layers. Subtle 2–4% texture opacity for metal and leather. Asymmetrical layouts allowed. Information-dense, utilitarian, earned whitespace only."