# Star Wars Design System Prompts

A collection of detailed, AI-ready design system prompts themed around locations and factions from the Star Wars universe. Each prompt follows a structured 9-section format inspired by [designprompts.dev](https://www.designprompts.dev), designed to be dropped directly into AI assistants like Claude, ChatGPT, or v0 to generate cohesive, themed UI designs.

---

## What Is This?

These prompts define complete design systems — not just color palettes, but typography rules, component specifications, spacing grids, motion principles, iconography guidelines, and accessibility requirements — all filtered through a specific Star Wars aesthetic.

Each prompt targets a standard "Acme Platform" demo page as its canvas, giving the AI a consistent baseline to apply the system against.

---

## Prompts

| File | Theme | Mood |
|---|---|---|
| `imperial-design-system.md` | Galactic Empire | Authoritarian, cold, geometric, severe |
| `republic-design-system.md` | Galactic Republic | Democratic, noble, structured, resilient |
| `mandalorian-design-system.md` | Mandalorian Culture | Battle-worn, pragmatic, utilitarian, rugged |
| `hoth-design-system.md` | Hoth Ice Base | Frigid, survivalist, clinical, tactical |
| `bespin-design-system.md` | Cloud City | Elegant, luxurious, serene, ethereal |
| `coruscant-design-system.md` | Galactic Capital | Cyber-noir, high-density, neon-lit, dynamic |
| `tatooine-design-system.md` | Desert Planet | Sun-bleached, scavenged, rugged, utilitarian |

---

## Prompt Structure

Every prompt is divided into 9 sections:

1. **Visual Theme & Atmosphere** — Core mood, aesthetic principles, and environmental inspiration
2. **Color Palette & Roles** — Named tokens with hex values and strict usage rules
3. **Typography Rules** — Font choices, weights, scales, letter-spacing, and text transforms
4. **Iconography Principles** — Style, stroke weight, sizing, and purpose
5. **Layout & Spacing Grid** — Base grid unit, gutters, max-widths, and container rules
6. **Component Styling** — Detailed specs for buttons, inputs, cards, tables, forms, and modals
7. **Motion & Interaction Guidance** — Transition timing, easing, hover/focus behavior, and loading patterns
8. **Accessibility Foundations** — Contrast requirements, focus states, keyboard navigation, and ARIA
9. **Agent Guide** — A condensed directive summary for AI assistants to execute the system

---

## How to Use

Copy the full contents of any `.md` file and paste it into your AI assistant as a system prompt or initial message. Then ask it to design or redesign a UI page — the assistant will apply the design system consistently.

**Works well with:**
- [Claude](https://claude.ai)
- [ChatGPT](https://chat.openai.com)
- [v0 by Vercel](https://v0.dev)
- Any AI assistant that accepts long system prompts

---

## Design Philosophy

These prompts were built to go beyond surface-level theming. The goal is not just "make it look like Star Wars" — it's to capture the *functional logic* of each environment:

- The **Empire** doesn't decorate. Red is a controlled substance — consequence, not branding.
- The **Republic** balances structure with humanity. Serifs signal tradition; blues signal trust.
- The **Mandalorian** aesthetic is earned, not designed. Nothing is decorative.
- **Hoth** is a survival interface. Thermal orange means danger. Sensor blue means alive.
- **Bespin** floats. Translucency, light weights, generous whitespace. If it looks grounded, it's wrong.
- **Coruscant** never sleeps. Everything glows. Density is a feature.
- **Tatooine** was built from parts. If it looks new, it's wrong.

---

## Adding New Prompts

When creating a new prompt, follow the 9-section structure above. Choose a Star Wars location or faction with a visually distinct identity and define it at the token level — specific hex values, exact font names, precise spacing units, and clear rules for when each element may and may not be used.

---

## Inspiration

Methodology inspired by [designprompts.dev](https://www.designprompts.dev).