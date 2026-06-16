# Brand DNA — Zoey's Brand Foundation

> All pages and scenes share these core constraints. No matter the design style, never violate this file.

---

## 🎨 Core Three Colors

| Color | Hex | Inspired By | Usage |
|-------|-----|-------------|-------|
| Deep Teal | `#1B8A8A` | Gemini duality, depth + curiosity | Primary, headings, links, key accents |
| Warm Gold | `#E8C547` | Blonde hair, warmth, stage lights | Emphasis, decorations, badges, highlights |
| Soft Rose | `#D4637A` | Playfulness, drama, creative energy | Punctuation, CTA, tags, underline accents |

Color ratio: Teal 60% · Gold 30% · Rose 10% (Rose is always punctuation, never dominant)

---

## 👩 Personal Visual Identity

Zoey's visual identity elements:

- **Blonde-to-black gradient hair** — Long hair with fading blonde dye revealing dark roots, the signature look
- **Dual energy** — Gemini: one side analytical (ML engineer), one side expressive (actress, musician)
- **Active & exploratory** — Always in motion: skiing, coding, performing, crafting

### IP Avatars
- **Avatar V1** — `assets/Avatar.png` — Blonde hair, gold background, teal crayon doodles. Primary hero avatar, energetic and striking.
- **Avatar V2** — `assets/Avatar Version 2.png` — Dark hair, warm cream background, rose doodles. Secondary/about section avatar, softer and warmer.
- Both are illustrated in a hand-drawn crayon style — warm, personal, not AI-stock-photo feeling.

### Usage Rules
- Use V1 for hero / first impression contexts
- Use V2 for secondary / deeper-in-the-page contexts (about, sidebar)
- Never modify the illustrations' proportions, colors, or style
- Real photos are also acceptable — candid and energetic, not corporate headshots

---

## 🔤 Typography

### Core Principle
- **Headings: serif for personality, body: sans-serif for clarity** — the mix creates rhythm
- **English + Chinese mix welcome** — English for labels/decoration, Chinese for content when needed
- **Extreme size contrast** — Big should be really big, small should be truly small

### Recommended Font Stack

| Context | Font | Notes |
|---------|------|-------|
| English display/headings | `Fraunces` (italic) | Elegant serif with character |
| English handwritten/casual | `Caveat` | Hand-drawn feel for annotations |
| English monospace/terminal | `Fira Code` | Technical/terminal scenes only |
| Chinese headings (primary) | `Noto Serif SC` (900) | Serif weight for impact |
| Chinese body | `Noto Sans SC` + system stack | Cross-platform sans-serif |
| System fallback | `-apple-system, 'PingFang SC', 'Helvetica Neue', sans-serif` | Fastest local rendering |

### Type Scale (fluid sizing)
- Hero headline: `clamp(2.8rem, 7vw, 5.5rem)`
- Section title: `clamp(1.6rem, 4vw, 2.6rem)`
- Card title: `1.15rem ~ 1.4rem`
- Body: `16px`
- Caption/helper: `0.78rem ~ 0.85rem`
- Large decorative numbers: `clamp(3rem, 8vw, 7rem)` + `opacity: 0.12~0.2`

---

## ✨ Vibe Keywords

The design should feel:

- **Smart but not cold** — ML engineer who also performs on stage
- **Adventurous and curious** — Always learning, always exploring
- **Warm and real** — Human, approachable, not corporate
- **Not like AI generated** — Highest priority constraint
- **Has taste** — Precise spacing, considered color, intentional details
- **Dual nature** — Analytical + creative, technical + artistic, focused + playful (Gemini energy)
- **Personal brand clarity** — One look and you know it's Zoey's

---

## 🎨 Extended Palette

When three colors aren't enough:

- Backgrounds always warm: `#fefcf6` (main), `#f8f5ed` (deeper cream)
- Text never pure black: use `#1A1A2E` (ink) or `#1a1a1a`
- Secondary text: `#4A4A5A`, `#555`, `#888`
- Never use pure black `#000` or pure white `#fff`
- Dark mode base: `#151821`, `#0d1117` (cool-blue dark, full-screen HTML only — no dark backgrounds on 3:4 card formats)
- Terminal green: `#4ade80` (terminal-style scenes only)
- Use radial gradients for depth, not flat colors

---

## 🚫 Universal Don'ts

| Type | Forbidden |
|------|-----------|
| Color | Blue-purple gradients, cyan, neon, pure black/white, generic cold-gray AI palette, dark cards (3:4 only — full-screen HTML exempt) |
| Fonts | Inter/Roboto/Arial and other overused fonts (unless explicitly terminal-style), monospace as "tech aesthetic" |
| Layout | Everything centered, cookie-cutter card grids, cards inside cards |
| Animation | bounce/elastic, animate width/height, infinite loop animations |
| Decoration | Glassmorphism, uniform rounded-rect + shadow everywhere, gradient text, AI glow effects |
| Overall | Looking like an AI-generated template, generic SaaS landing page feel |
| Borders | Gold decorative borders must be 40px — no thinner |
| Spacing | Line-height/letter-spacing must be visually checked — no awkward rhythm allowed |
| Images | AI stock photos, over-filtered images, meaningless decorative images |
| Defaults | Browser default blockquote, default border-left quotes, unstyled ul/ol, default tables — all components must be custom styled |

### Self-Check Questions
After finishing a design, ask yourself:
1. If I screenshot this and post it online, would someone comment "looks AI-generated"?
2. Can you tell at a glance this is Zoey's?
3. Is there any part that feels "seen it a thousand times"?

---

## 📐 Spacing System

- Between sections: `clamp(80px, 12vh, 160px)`
- Between content blocks: `clamp(40px, 6vw, 100px)`
- Card inner padding: `clamp(28px, 3vw, 44px)`
- Element gap: `clamp(24px, 3vw, 48px)`
- All use `clamp()` for fluid sizing
- `max-width: 1300px` + `margin: 0 auto` for content width

---

## 📱 Responsive Rules

- Breakpoints: 900px (two-col → single-col), 600px (font scale down)
- Mobile is "rearranged" not "shrunk"
- Respect `prefers-reduced-motion`
- Mobile never hides content — adapt, don't amputate

---

## 🔍 Detail Specs

- **Text selection highlight**: `::selection { background: #E8C547; color: #1a1a1a; }`
- **Link hover**: Gold underline or background block, not color change
- **Gradient hair motif**: When used decoratively, a subtle dark-to-gold gradient (bottom-to-top) can echo the hair fade — use sparingly

---

*This is the foundation. Every scene file builds on top of this.*
