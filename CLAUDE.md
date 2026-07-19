# Astro Recipe — Product Brief

## Concept
An astrology website that turns a user's natal chart into a personal instruction manual for how to live in their own nature — not against it.
The chart is read in combination the way a professional astrologer would, and turned into concrete Glow guidance: how to dress, how to position your career and talents, what to post and how, what drains and restores your energy.

## Problem
Apps like Co-Star and The Pattern are too abstract and generic:
- Readings are vague and apply to everyone
- They describe WHO you are but not WHAT TO DO
- No practical application — you read it and move on
- Nobody reads planets in combination — only in isolation
- Generic self-improvement advice (Nebula's "spend time with yourself") is not a natal chart reading

## Solution
Natal chart as a Glow operating system. Algorithmic interpretation that reads planetary positions, aspects, houses, and signs in combination — the way a professional astrologer would — and turns it into specific, applied guidance: natural aesthetics, career positioning and talents, social content style, energy management.

Note: specific planetary reading methodology is TBD — will be defined by the astrology prompt system.

## Niche (confirmed)
**Glow — жити в своїй природі, а не проти неї.**
People keep trying to improve themselves — change their style, build routines, "be more themselves" — but nothing sticks because all tools are either too abstract or too generic. Astro Recipe gives a concrete, personalized instruction based on the natal chart.

This niche covers Style/Fashion and Self-improvement simultaneously. Zero direct competitors (Amelie does it as a $197 course, not self-serve). Demand confirmed via Nebula Personal Plan (46.9k enrolled, bad product) and TikTok "2025 glow up astrology" trend.

Previous framing: "personal brand & aesthetic" — now refined to Glow (broader: style + career/talents + social content + energy).

## Core User Flow
1. User enters birth date + time + place
2. Onboarding asks: "what's happening in your life right now?" (main trigger question) + one additional optional question (content TBD)
3. Website calculates natal chart → results page shows the chart with a brief summary — the wow moment (free, no email/payment yet)
4. User scrolls down → sees the option to unlock the full report, with previews of other people's reports and testimonials from happy customers
5. Email + payment collected at this step (checkout) → full report delivered/unlocked

**Email placement (decision, 2026-07-17):** collect email at step 5 (report checkout), not earlier. Keeps steps 1–4 — the free wow-moment — frictionless, and matches the confirmed competitor pattern (research.md → "Freemium as entry point": no player takes payment/email upfront without a demo first). Report delivery needs an email anyway, so this isn't extra friction, just the natural place to ask. Optional post-MVP idea: a lightweight "email me my chart" capture right after step 3, before the paywall, to remarket people who saw the teaser but didn't buy — not required for MVP.

**Resolved (2026-07-17):** yes — the full report contains all four Glow dimensions (style + career/talents + social content + energy, possibly as tiered plans per Monetization). This replaces the earlier plan of separate in-site screens per dimension: the site itself is just onboarding → free teaser → paywall/checkout; the four dimensions live inside the purchased report, not as navigable site screens. sitemap.md and ia.html are updated to match.

## Audience
- **Primary:** solopreneurs and content creators, 24–35, digital nomad / traveller context (Bali, SEA), English-speaking — runs their own business or personal brand, not employed in a structured job
- Жінки — основна частина; але є чоловіки (творчі, емоційно доступні)
- Already familiar with MBTI / Human Design / Enneagram — not first-time self-discovery
- Frustrated with vague astrology — want concrete, applied guidance for how they present themselves and work, not just who they are
- CIS market: reference and research, not primary MVP target
- **Trigger:** arrive during a specific life crisis or decision — not abstract curiosity (confirmed: compensatory control mechanism, Graham Tyson 1982)

**Decision (2026-07-17):** audience narrowed from generic self-improvement seeker to solopreneur/content creator specifically — earlier surfaced as Secondary personas "Творчий хлопець" and "Ангеліна" (personas.md) and as "Ніша 2 — Content Creation / Personal Brand Strategy" (research.md, Доресерч). Old research on the broader audience stays as-is for reference; this narrows who Astro Recipe is *for*, it doesn't invalidate it.

## Platform
Website (not a mobile app) — mobile-first web → responsive desktop

## Differentiation
- Reads the chart in combination, not in isolation — the way a real astrologer does (specific combinations TBD)
- Gives concrete Glow instructions — not "you are creative", but "here's what to do"
- Niche focus (Glow: style + career/talents + social content + energy) — deep expertise, not shallow coverage
- Honest about what charts can and can't show (potential ≠ level of development)

## Critical Product Insight
The chart shows POTENTIAL, not the person's current level of development. A great Neptune can manifest as creativity or alcoholism — it depends on the person, not the chart. Two "compatible" people can be on completely different levels of consciousness. An honest product acknowledges this — it's a differentiator from naive astrology.

## Key Planets for This Niche
- **Venus** — aesthetics, beauty, what attracts, style preferences
- **Rising sign (Ascendant)** — how you're perceived, first impression, energetic signature
- **Midheaven (MC)** — public image, brand essence, career direction, how you're meant to be seen
- **Saturn** — where talent meets discipline, likely bottlenecks in executing tasks, structure that actually holds
- **Moon** — emotional comfort, what feels authentic in self-expression
- **Mercury** — communication style, what type of content resonates
- **Neptune** — inner image, spiritual aesthetic, creative channel

## Onboarding Insight
Do NOT just collect birth data. Ask "what's happening in your life right now?" — the person arrives in a moment of crisis or decision and wants to feel understood, not processed.

## Primary Persona
**Маша** — 27–34, digital nomad / traveller, solopreneur or content creator running her own thing, already knows astrology superficially, wants concrete actions for how she works and shows up publicly — not just who she is. Arrives during a crisis or major decision. Frustrated: "I know my chart but what do I DO with it?"

## Main Job
Коли я постійно намагаюсь себе покращити — змінити стиль, ввести рутину, бути більш собою — але нічого не приживається і відчуваю що роблю щось не так, я хочу зрозуміти через свою карту яка моя природна мова (енергія, естетика, ритм), щоб перестати воювати з собою і почати жити так, що це відчувається як я.

## MVP Top-3 Jobs
1. Glow Profile — перестати воювати з собою, зрозуміти свою природу через карту (core)
2. Wow-момент впізнавання себе — перший екран результату (конверсія)
3. Стиль, кар'єра/таланти і соушал контент що реально мої — конкретні інструкції, не generic advice (диференціація)

## Real Use Cases (from product owner)
- Людина хоче зрозуміти свій стиль і особисту естетику через карту
- Контент-мейкер хоче вирівняти контент-стратегію зі своєю картою — тепер core use case, не гіпотеза
- Соло-підприємець хоче зрозуміти кар'єрне позиціонування, свої таланти і потенціал, де можуть бути затики у виконанні задач
- Перевірка сумісності партнера на 2–3 побаченні (люди роблять це в ChatGPT)
- Вибір дня для бізнес-дії — підприємці (electional astrology, окремий сигнал, все ще не в MVP)

## Closest Competitor
**Amelie (ameliesadvice.com)** — AstroGlow 101, 4-week course, $197. "Вивчи метод читання карти щоб розвиватись без астролога." Psychology + wellness + astrology. Most similar approach to Astro Recipe.

## Monetization
One-time report, paid at checkout (product owner, Notion notes, 2026-07-17): free teaser page (chart + brief wow-moment summary) → pay to unlock the full report. Possibly tiered plans, e.g. "Style only" vs "Style + career positioning + social media (how to run it, content type)". Product owner's own framing: "це комплексна інструкція" (it's a comprehensive instruction) — leans toward the bundle being the primary offer, tiers still open.
Price signals: one-time report $7–50 range (Matrix Destiny, Astrology Hub, Gallup), course $197 (Amelie), subscription ~$12/mo (CHANI) — still useful as external price anchors even though the model itself (one-time report) is now decided.

## Wireframes
`wireframes/` — low-fi HTML, grayscale, semantic markup, real domain text (Урок 4). Main flow fully built and linked: welcome → onboarding (date/time/place/questions) → results (free teaser: chart + brief) → checkout (email + payment) → report (paid, 4 sections: style/career/energy/social content) → share. All states (empty/error/loading) covered per `_screens.md`. Profile screens (5.1/5.2, [SIROTA]) intentionally not built — need unconfirmed without persistent navigation. See `_critique.md` for the audit.

## Voice
Product copy is English (audience is English-speaking). `voice.md` — 4 principles (concrete action not character description, specific chart placement not abstract trait, honest about limits, advice tied to this person's chart), dictionary, forbidden list (no AI clichés, no "successfully", no exclamation marks/emoji in system messages), microcopy rules by element type. `microcopy.md` is the source of truth — every interface line, by screen. All 18 `wireframes/*.html` rewritten to this voice (Урок 5, 2026-07-19).

## Name
**Astro Recipe** (working title)

## Tech Stack
TBD

## Status
Brief v0.9 — Voice established and applied to all wireframes, product copy is English (Урок 5, 2026-07-19).
Brief v0.8 — Glow niche confirmed, audience narrowed to solopreneurs/content creators, platform confirmed as website (not app). Product is a funnel, not an app: onboarding → free teaser page (chart + brief) → scroll → paywall (report previews + testimonials) → checkout → paid Glow Report. The four Glow dimensions (style, career/talents, energy, social content) live inside the Report, not as separate site screens. sitemap.md, flows.md, ia.html, jtbd.md all synced to this (2026-07-17). Wireframes (Урок 4) done for the whole main flow — 18 HTML files, grayscale, all states, linked, audited (2026-07-19).
