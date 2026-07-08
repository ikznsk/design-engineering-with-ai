# Astro Recipe

> Your natal chart as a personal instruction manual for your style, aesthetic and personal brand.

An astrology app that turns a birth chart into concrete, actionable guidance — built on real Western astrology algorithms, not generic horoscope copy.

---

## Brief

| | |
|---|---|
| **Problem** | Co-Star & The Pattern describe who you are, not what to do. Nobody reads the whole chart in combination. |
| **Solution** | Natal chart reading that works like a professional astrologer — Venus + Rising + Midheaven → how to look, what to express, which aesthetic to build. |
| **Audience** | 24–35, digital nomad / traveller context (Bali, SEA), English-speaking, self-discovery oriented. |
| **Platform** | Mobile-first web → desktop. |
| **Niche** | Personal brand & aesthetic through the birth chart (style × content creation intersection). |
| **Status** | Research done — moving to IA |

Full brief → [CLAUDE.md](./CLAUDE.md)

---

## People

**Primary persona — Маша, "Шукачка інструкції"**
27–34, digital nomad, знає астрологію поверхово, хоче конкретних дій.
Приходить у момент кризи або великого рішення. → [personas.md](./personas.md)

**Main Job**
Коли я застрягла і не розумію чому знову роблю одне й те саме — хочу отримати пояснення через свою конкретну карту, щоб мати ясність і знати що змінити. → [jtbd.md](./jtbd.md)

**MVP Top-3 Jobs**
1. Ясність через карту + конкретні дії (core)
2. Wow-момент впізнавання себе (конверсія)
3. Відповідь на конкретне питання (диференціація)

---

## Repo structure

```
research/
├── research.md          # Competitor map, patterns, gaps, доресерч
├── research.html        # ← Головний документ: весь ресерч в одному місці
├── influencers.md       # Influencer & course creator research
├── video-analysis.md    # CHANI / AstroBella / Nebula product breakdown
└── screens/             # UI screenshots — 26 competitors

personas.md              # 4 персони (primary: Маша, 3 secondary)
jtbd.md                  # Jobs + матриця + висновок про MVP

wireframes/              # Low-fi flows (не починали)
concept/                 # Visual direction (не починали)
tokens/                  # Design tokens (не починали)
components/              # UI components (не починали)
design-system/           # Design system (не починали)
handoff/                 # Dev specs (не починали)
```

---

## Status by phase

| Phase | Status | Артефакт |
|---|---|---|
| Brief | ✅ Done | CLAUDE.md |
| Research — конкуренти | ✅ Done | research.md, research.html |
| Research — інфлюенсери | ✅ Done | influencers.md |
| Research — продукти | ✅ Done | video-analysis.md |
| Research — ніші | ✅ Done | research.html → Ніші |
| Research — психологія | ✅ Done | research.html → Психологія |
| Персони | ✅ Done | personas.md |
| JTBD | ✅ Done | jtbd.md |
| IA — Sitemap | ⬜ Not started | sitemap.md |
| IA — Flows | ⬜ Not started | flows.md |
| Wireframes | ⬜ Not started | |
| Concept | ⬜ Not started | |
| Design system | ⬜ Not started | |
| Handoff | ⬜ Not started | |

---

## Key findings

- **Gap:** ніхто не дає реально персоналізований аналіз (по всій карті) + конкретні дії + в одній ніші
- **Ніша:** особистий бренд і естетика через карту (Venus + Rising + Midheaven) — конкурентів нуль
- **Тригер:** людина приходить у момент кризи/рішення, не з цікавості (compensatory control)
- **Еталон якості тексту:** CHANI. Еталон actionability: AstroBella "How to show up" format
- **Closest competitor:** Amelie (ameliesadvice.com) — AstroGlow 101, $197
