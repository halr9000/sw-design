# Star Wars Design System Prompts

[![Live Demo](https://img.shields.io/badge/-Live%20Demo-4fc3f7?style=for-the-badge&labelColor=111118)](https://halr9000.github.io/sw-design/)

A collection of detailed, AI-ready design system prompts themed around locations and factions from the Star Wars universe. Each prompt follows a structured 9-section format inspired by [designprompts.dev](https://www.designprompts.dev), designed to be dropped directly into AI assistants like Claude, ChatGPT, or v0 to generate cohesive, themed UI designs.

---

## Repository Structure

```
sw-design/
├── design-systems/          # AI-ready design system prompt files (.md)
│   ├── imperial-design-system.md
│   ├── republic-design-system.md
│   ├── mandalorian-design-system.md
│   ├── hoth-design-system.md
│   ├── bespin-design-system.md
│   ├── coruscant-design-system.md
│   └── tatooine-design-system.md
└── examples/                # Sample HTML pages built from each design system
    ├── imperial/            # ISB Sector 7G Threat Assessment Terminal
    ├── republic/            # Galactic Senate 853rd Session Archives
    ├── mandalorian/         # The Covert: Bounty & Contract Registry
    ├── hoth/                # Echo Base Tactical Operations Center
    ├── bespin/              # Cloud City Tibanna Gas Consortium & Resort
    ├── coruscant/           # The Works Underground Data Exchange
    └── tatooine/            # Mos Eisley Salvage, Trade & Transport Registry
```

Each `examples/` subfolder contains:

- `index.html` — Fully styled sample page implementing the design system
- `images/hero.jpg` — Hero image slot (see image prompts below for generation)

---

## What Is This?

These prompts define complete design systems — not just color palettes, but typography rules, component specifications, spacing grids, motion principles, iconography guidelines, and accessibility requirements — all filtered through a specific Star Wars aesthetic.

Each prompt targets a standard "Acme Platform" demo page as its canvas, giving the AI a consistent baseline to apply the system against.

---

## Design Systems

| File | Theme | Mood | Live Example |
|---|---|---|---|
| `imperial-design-system.md` | Galactic Empire | Authoritarian, cold, geometric, severe | [ISB Sector 7G →](https://halr9000.github.io/sw-design/examples/imperial/) |
| `republic-design-system.md` | Galactic Republic | Democratic, noble, structured, resilient | [Galactic Senate Archives →](https://halr9000.github.io/sw-design/examples/republic/) |
| `mandalorian-design-system.md` | Mandalorian Culture | Battle-worn, pragmatic, utilitarian, rugged | [The Covert →](https://halr9000.github.io/sw-design/examples/mandalorian/) |
| `hoth-design-system.md` | Hoth Ice Base | Frigid, survivalist, clinical, tactical | [Echo Base Ops →](https://halr9000.github.io/sw-design/examples/hoth/) |
| `bespin-design-system.md` | Cloud City | Elegant, luxurious, serene, ethereal | [Cloud City Consortium →](https://halr9000.github.io/sw-design/examples/bespin/) |
| `coruscant-design-system.md` | Galactic Capital | Cyber-noir, high-density, neon-lit, dynamic | [The Works Underground →](https://halr9000.github.io/sw-design/examples/coruscant/) |
| `tatooine-design-system.md` | Desert Planet | Sun-bleached, scavenged, rugged, utilitarian | [Mos Eisley Exchange →](https://halr9000.github.io/sw-design/examples/tatooine/) |

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

## Hero Image Prompts

Each example page includes a `images/hero.jpg` slot. Generate a **square image** (1:1, e.g. 1024×1024) using these prompts:

### Imperial — `examples/imperial/images/hero.jpg`
>
> Two Imperial Star Destroyers holding formation over a grey industrial planet, dramatic deep space backdrop, cool blue starlight, a small TIE fighter silhouette against the hull of the nearest Destroyer, hyper-detailed sci-fi concept art, cinematic widescreen crop, dark and severe palette — blacks, greys, and a single point of red light

### Republic — `examples/republic/images/hero.jpg`
>
> The Galactic Republic Senate rotunda chamber viewed from above, thousands of floating senatorial pods extending into a vast circular void, warm golden-white light from the central podium, blue holographic displays scattered throughout, regal and optimistic atmosphere, digital painting, cinematic aerial perspective

### Mandalorian — `examples/mandalorian/images/hero.jpg`
>
> A lone Mandalorian warrior in battered beskar armour standing in a forge-lit underground cavern, orange forge glow reflecting off the helmet visor, rough stone walls with Mandalorian sigil carved in durasteel, atmospheric smoke, dramatic side lighting, hyper-detailed concept art, dark warm palette

### Hoth — `examples/hoth/images/hero.jpg`
>
> Rebel Alliance Echo Base operations center carved into an ice cavern on Hoth, orange-uniformed soldiers at tactical consoles, blue holographic displays, AT-AT walkers visible through a viewport in the ice wall advancing across a frozen tundra, tense atmosphere, cold blue-white environment with warm orange uniform accents, cinematic sci-fi concept art

### Bespin — `examples/bespin/images/hero.jpg`
>
> Cloud City floating above the amber-golden cloud layer of Bespin at sunset, elegant Art Deco white towers and transparent skylights catching the twin-sun light, deep amber and rose sky fading to violet at the edges, serene and luxurious atmosphere, matte painting style, warm gold and sky-blue palette

### Coruscant — `examples/coruscant/images/hero.jpg`
>
> Coruscant lower levels at night, Level 1313, neon purple and cyan signs reflecting off rain-slicked durasteel floors, endless layers of city extending downward into darkness, shadowy figures of aliens and humans in hooded cloaks, cyberpunk noir atmosphere, glowing advertisements in alien script, hyper-dense urban environment, digital painting

### Tatooine — `examples/tatooine/images/hero.jpg`
>
> Mos Eisley spaceport marketplace at golden hour, twin suns low on the horizon casting long warm shadows, weathered sand-coloured adobe buildings, a mix of aliens and humans trading in a dusty open market, various droids and a dewback in the background, a YT-1300 freighter visible in a docking bay, warm amber and ochre palette, lived-in frontier atmosphere

---

## Inspiration

Methodology inspired by [designprompts.dev](https://www.designprompts.dev).
