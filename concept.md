# Concept — Astro Recipe

> Lesson 6. Voice already exists (voice.md); this document earns the *look*.
> Date: 2026-07-20 · **Updated 2026-07-27** with the visual exploration (moodboards, Mobbin, Neptunian direction, elevated-taste calibration). The taste below supersedes the 2026-07-20 version.
> Reference files: `concept/references.md`, `concept/moodboard-analysis.md`, `concept/neptunian-ui-references.md`, `concept/elevated-references.html`, `research/mobbin-visual-research.md`.

---

## Designer's taste

### The guiding vibe (Iryna, 2026-07-26)
**Neptunian / Pisces** — illusory, dreamy, translucent, iridescent, "between dream and waking, from another dimension." Warm and luminous, never dark. This is the branding spine; the interface underneath stays functional (atmosphere in the background, content on solid ground). See `concept/moodboard-analysis.md`.

### Named references — UI / interaction taste (Iryna, confirmed 2026-07-27)
1. **mymind** — *most similar.* Restrained editorial: one soft aura orb, a warm serif set tight, huge negative space. Restraint IS the design.
2. **ABY Journal** — *closer.* Warm iridescent reading-cards, elegant and fully legible — the answer to "long text on a dreamy ground."
3. **Elevated tier / ceiling:** Cosmos, OFF+BRAND, Dot (iridescence contained to one object against calm space); Vyrao, Ffern (luxury brand-world, no SaaS smell); Refik Anadol, Universal Everything (the iridescent-*art* ceiling — for the glow moment only, not the whole UI). See `concept/elevated-references.html`.

### Named references — text / type / document (from 2026-07-20, still hold)
4. **CHANI** — text-quality + type benchmark: expressive serif display + warm humanist sans body + monospace uppercase labels; hand-drawn squiggle dividers; warm off-white ground. (Profiled from a real recording in `research/mobbin-visual-research.md`.)
5. **Glow** (wellness-app genre, also the niche name) — soft warm palette, calm-not-clinical, generous white space.
6. **Professional astrologer reports** — editorial, document-like, section-per-planet keepsake worth paying for. Applies to `report.html`.

### Anti-references (now CONFIRMED by Iryna, not inferred)
- **Aura Health, Opal, Air** — cheap SaaS glassmorphism / "vibecoder" gradient+glass. Technically dreamy, but they cheapen. Rejected on taste 2026-07-27.
- **Dark purple-cosmic starfield + neon** (Nebula, Moonly) — the templated astrology trap.
- **Cold grayscale editorial SaaS** (Co-Star's chill) — steal its structure, not its coldness.
- **Model reflex:** cream + terracotta "cozy" default; grey gradients instead of real photo/atmosphere; screens with no icons.

### The craft bar (what separates elevated from cheap — the taste test for every decision)
- **Type does the work, not the effect** — a real serif at editorial scale leads; the gradient is never the design.
- **One contained atmospheric move** — a single aura orb / one misty photo against space, not a wall of gradient with glow on everything.
- **Art direction / photography > CSS** — styled texture and light a gradient can't fake.
- **Matte, desaturated, restrained** — dusty mauve, sand, oyster, dawn-peach; high-shine blue-purple is the cheap tell.
- **Negative space as luxury** — elevated pages are ~70% empty.

---

## Attributes — pairs of opposites

Each pair: the data line it comes from, and the technique it borrows.

### 1. Expressive display serif ↔ neutral system type
**Data:** personas.md → Masha, Trust triggers #1: "text reads like a real astrologer, not a template."
**Technique:** expressive high-contrast serif for titles + the wow-moment line; quiet humanist sans for body; monospace uppercase for labels/eyebrows. Evidence: CHANI, mymind, Cosmos, Tolan all lead with serif.

### 2. Warm misted ground ↔ soft cool iridescent accent
**Data:** report.html describes Masha's own style as "a warm, earthy palette" (Venus in Taurus); against Glow's soft cool register (jtbd.md Emotional job, "permission to be yourself").
**Technique (resolved):** warm misted off-white base (not stark paper), near-black warm ink, and **one** iridescent accent (blush / lavender / peach — oil-on-water) reserved for CTA + selected tier + the glow. Never a full palette of iridescent, never purple-cosmic.

### 3. Editorial density (report) ↔ airy app spacing (onboarding / results)
**Data:** CLAUDE.md → Monetization: the report is the paid deliverable — must read as worth paying for, not a fifth free app screen. Against jtbd.md → Emotional job: onboarding must feel unhurried.
**Technique:** professional-report pacing (denser text, generous line-height, section-per-planet, fixed eyebrow taxonomy) for `report.html`; keep the free-flow screens airy with lots of negative space (mymind restraint).

### 4. Iridescence contained to one object ↔ no illustration at all
**Data:** CLAUDE.md → Critical Product Insight: the chart shows potential, not level — don't oversell mysticism. Plus Iryna's craft bar: "one contained atmospheric move."
**Technique:** aura / iridescence haloes a single object (the chart, one orb), never page-wide decoration. Chart itself rendered as thin line-art, not a glossy 3D toy.

### 5. Dream at full ↔ dream at low (the Neptunian saturation gradient)
**Data:** CLAUDE.md → wow-moment (results teaser) must deliver awe; against the report/reading needing legibility.
**Technique:** iridescent aura behind the **chart reveal / wow-moment** (dream up); desaturated ground + text on solid/frosted cards for **reading and report** (dream down). Rules in `concept/neptunian-ui-references.md`.

### 6. Elevated restraint ↔ cheap glassmorphism
**Data:** Iryna's taste — mymind/ABY in, Aura/Opal/Air out (2026-07-27).
**Technique:** one contained atmospheric move + editorial serif + matte palette + heavy negative space. Never full-bleed gradient + frosted cards + glow-on-everything (the vibecoder tell).

---

## Directions

Three luminous directions built in `concept/directions.html` (v2, re-grounded in the moodboards — iridescent, dreamy, not matte).

**Chosen (Iryna, 2026-07-28): Direction 02 — Liquid Aura.**
One oil-on-water iridescent field plus a soft aura ring behind the chart, on calm cool space — the version she flagged closest, pushed more luminous. World: pale cool ground `#EDEEF3` with iridescent lavender/blush/aqua fields; periwinkle accent `#6E5FE0` (deep `#5A4BD4` for AA); warm violet-black ink `#241F2E`. Type: **Hedvig Letters Serif** (display) + **Figtree** (body) + **Martian Mono** (data/labels). Signature: the chart sits inside a soft aura halo; all content rides a frosted near-white panel so it stays legible (dream at full behind the chart, dream at low under text — Attribute 5). The proof stand is `concept.html`.

**Recorded alternates (can return to — likely per-surface, not discarded):**
- **01 Moon Dream** — pastel iridescent cloud-sky + Rozha One fashion serif. The dreamiest; a candidate mood for the free wow-moment / chart reveal.
- **03 Golden Hour** — warm sacred luminosity, golden light + ring-of-light halo, Bodoni Moda + antique gold. A candidate warmth for the paid report's keepsake feel.

---

## Applied refinements (Steps 5–7, 2026-07-28)

Painted `results.html` (+ states) and `report.html` in the Liquid Aura language. Two system elements were promoted during the Step-7 review (Iryna's feedback: the aura must read like the moodboard gradients; add richness / images / interesting layout):

- **Iridescent aura gradient (`--iris`)** — an authored oil-on-water / MOON-DREAM mesh (layered radial lavender→blush→peach→aqua + soft grain), replacing the earlier muddy stock photo behind the chart. This is now the canonical "aura" surface (the `dream at full` moment) — used behind the results chart and in the report header. Ties directly to the moodboards (`moodboard-analysis.md`) and Attribute 5.
- **Section emblems** — a small iridescent tile + Solar icon per Glow dimension (Style/Career/Energy/Social), giving the report an image layer and a more dynamic layout. Resolves the ad-hoc section accent bar flagged in the Step-7 defect table; each emblem uses a slice of the `--iris` palette (Attribute 4: iridescence contained to one object).

Step-7 defect fixes also applied across all screens: darkened `--muted` (#6E6678) for AA contrast on small labels; one blur token (`--blur:13px`); Solar chevron for the scroll hint; `:focus-visible` rings; responsive collapse of the review nav under 760px. Left as-is by decision: em-dash density (established Lesson-5 product copy — text is not changed in this lesson).
