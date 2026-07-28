# Reference Sites — found via the vibe adjectives

> Companion to `concept/vibe-adjectives.md`. Live websites that already run the devices in our Neptunian kit.
> Date: 2026-07-28.

## Method + how much to trust this

Design galleries (Godly → now `recent.design`, Land-book, SiteInspire, Awwwards) all block automated fetching — 403s or empty results. So this list was not harvested from galleries; it was **assembled from candidates and then verified against each site's own HTML + CSS**.

For each site I counted the actual devices in the shipped code: `backdrop-filter`, `blur()`, `linear/radial/conic-gradient`, grain/noise, `mix-blend-mode`, and the real font stack. That is evidence the *technique* is there — Impeccable's "a reference is a working system, not a mood." It is **not** evidence the page is beautiful; that judgment is mine and yours to check by opening it.

⚠️ Zero counts ≠ absence. Sites whose visuals run in WebGL/canvas (igloo.inc, activetheory.net, lusion.co, tolan.ai) show 0 CSS signals because the technique lives in shaders. Probe reads inline CSS + first 4 stylesheets only. Aesop and Calm returned 403 — open manually.

---

## Register A — vivid iridescent dream

| Site | Verified devices | Type stack | Why it's here |
|---|---|---|---|
| **[chani.com](https://chani.com)** | blur ×7, backdrop-filter ×4, gradient ×5, **mix-blend ×11** | Caraque (display serif) + Apercu Mono | Same category *and* same vibe. Highest blend-mode use of anything probed — that's how they get colour to sit *inside* light instead of on top of it. Serif + mono pairing is exactly our "expressive" modifier. |
| **[superpower.com](https://superpower.com)** | **blur ×29, backdrop-filter ×22**, gradient ×4, grain ×1 | NB International + Adelle Sans | The most committed translucency system I found anywhere. Health, not astrology — borrow the *system*, ignore the category. This is what "translucent" looks like when it's a design system, not a decoration. |
| **[press.stripe.com](https://press.stripe.com)** | **grain ×8**, gradient ×3 | Ivar Display / Headline / Text | ⭐ The single most useful reference for our hardest screen. Iridescent grainy covers + long-form reading that stays legible, all in one expressive serif family. This is the paid-report problem already solved. |
| **[mymind.com](https://mymind.com)** | **gradient ×21** (most of any site probed), no blur | FK Roman Standard + Inter | Warm-pastel dream built *entirely* from gradients with zero blur — proof the vibe doesn't require blur. Also a reading/saving product, so its content density is relevant. |
| **[thepattern.com](https://www.thepattern.com)** | blur ×8, backdrop ×4, blend ×7 | DM Sans + Helvetica | Direct competitor, same device kit. Study what makes it feel *less* premium than CHANI despite similar techniques — that gap is our brief. |
| **[hume.ai](https://hume.ai)** | backdrop ×2, blur ×2, gradient ×2 | Fellix + PP Fraktion Mono | Aura-glow as a whole brand identity. Emotion-AI, so the "read the invisible about a person" job is adjacent to ours. |
| **[family.co](https://family.co)** | backdrop ×2, gradient ×6 | Family (custom) + LFE Sans | Iridescent glass on a *transactional* product (crypto wallet). Shows the dream surviving contact with numbers and buttons — relevant to checkout. |
| **[rosebud.app](https://rosebud.app)** | gradient ×8, blur ×1 | Circular + **Merriweather** | Journaling + AI reflection. Closest to our emotional job. Serif for the reading surface, sans for UI — the split we'll likely need. |
| **[spline.design](https://spline.design)** | backdrop ×4, blur ×4 | Brockmann + Spline Sans | Pastel 3D blobs = the "chrome-liquid" board objects, rendered as product UI. |
| **[arc.net](https://arc.net)** | all four devices present (blur, gradient, grain, blend) | ABC Oracle + ABC Favorit Mono | The complete kit at low intensity — a calibration point for "how little is enough." |

**WebGL-class (probe blind, open manually):** [igloo.inc](https://igloo.inc) · [lusion.co](https://lusion.co) · [activetheory.net](https://activetheory.net) · [tolan.ai](https://tolan.ai) — this is where **aqueous** actually lives. Water, caustics and liquid chrome are not CSS; they're shaders or video. Budget accordingly, or fake it with a looping video behind a translucent layer.

---

## Register B — muted warm dream / sacred minimal

| Site | Verified devices | Type stack | Why it's here |
|---|---|---|---|
| **[wthn.com](https://wthn.com)** | **grain ×6**, gradient ×3, blur ×1 | **Saol** (display serif) + Founders Grotesk | ⭐ Best Register B find. Sacred + warm + grainy, and the grain is what keeps it from being the cream-and-serif default. Acupuncture as ritual — same "ancient system, modern application" positioning as us. |
| **[o-p-e-n.com](https://o-p-e-n.com)** | backdrop ×2, blur ×2, gradient ×2 | Monument Grotesk | Meditation as ritual with warm gradient grounds. Ritual pacing without a single sacred cliché. |
| **[byredo.com](https://www.byredo.com)** | **grain ×6**, gradient ×2, blur ×1 | byredoSans + byredoStencil | Warm-neutral luxury where grain does the work photographs usually do. Proof "expensive" here is a *texture* decision, not a colour one. |
| **[remedyplace.com](https://www.remedyplace.com)** | backdrop ×4, blur ×3, gradient ×2 | Beausite Classic / Beausite Slick | Ceremonial + clinical at once — our "honest about limits" tone in visual form. |
| **[theclass.com](https://theclass.com)** | blur ×1, gradient ×1 | **Collier** (serif) + Indivisible | Ritual movement. Restrained expressive serif — the "timeless cut" Board 4 implies. |
| **[othership.us](https://www.othership.us)** | blur ×1, gradient ×1 | **DM Serif Display** + Founders Grotesk | Ritual (sauna/breathwork) done warm. Note: DM Serif is on Impeccable's overused-faces list — take the composition, not the font. |
| **[ouraring.com](https://ouraring.com)** | blur ×2, gradient ×2 | **Editorial New** + Akkurat | Warm neutral applied to *personal data readouts* — the closest thing to "how do I render a chart without going cosmic." |
| **[sanctuaryworld.co](https://www.sanctuaryworld.co)** | backdrop ×2, gradient ×4 | AlternateGotNo3D + DM Sans | Astrology competitor in the warm register. Reference for what to beat. |
| **[cosmos.so](https://www.cosmos.so)** | blur ×2, backdrop ×1, blend ×1 | cosmosOracle + basisMono | Quiet, luminous, image-forward. Good model for the report's gallery/preview sections. |

**Blocked by Cloudflare, still worth opening:** [aesop.com](https://www.aesop.com) (403) · [calm.com](https://www.calm.com) (403).

---

## Open these six first

1. **[press.stripe.com](https://press.stripe.com)** — solves our hardest problem (dream + long-form legibility) already.
2. **[chani.com](https://chani.com)** — same category, closest total match, best blend-mode craft.
3. **[superpower.com](https://superpower.com)** — translucency as a real system, at scale.
4. **[wthn.com](https://wthn.com)** — Register B *with material*, not cream-and-serif.
5. **[mymind.com](https://mymind.com)** — the vibe with no blur at all. Cheapest path to it.
6. **[o-p-e-n.com](https://o-p-e-n.com)** — ritual pacing, warm ground, zero cliché.

---

## What the search actually revealed

**Grain is the load-bearing device, not blur.** Every reference that reads "expensive" rather than "trendy" — Stripe Press, Byredo, Wthn — leans on noise texture. Every one that reads dated leans on blur alone. Board 2's posters agree: they're grained, not blurred. Adjective #8 was underrated in my own ranking.

**Serif + mono is the recurring pair,** not serif + sans. CHANI (Caraque + Apercu Mono), Hume (Fellix + PP Fraktion Mono), Arc (Oracle + Favorit Mono), Cosmos (Oracle + basisMono). Mono reads as *notation* — data, coordinates, timestamps — which is exactly what a natal chart is. It buys credibility that a second sans never would.

**Nobody has fused the two registers.** Every site found is cleanly one or the other: iridescent-dreamy *or* sacred-warm. The moodboards ask for both, gradiented across the funnel. **That gap is Astro Recipe's visual position** — not a problem to solve, an opening to take.

**Aqueous stayed unfound in CSS.** It exists only in WebGL work. Decide early whether water is a real build target or a video texture, because it changes the tech stack.

→ Next: pull palettes and blur/opacity values from the top six into `concept/directions.html` and the Урок 8 token pass.
