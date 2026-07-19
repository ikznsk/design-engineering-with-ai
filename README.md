# Astro Recipe

> Your natal chart as a personal instruction manual for how to live in your own nature — style, career, content, energy.

An astrology website that turns a birth chart into concrete, actionable guidance — built on real Western astrology algorithms, not generic horoscope copy.

---

## Brief

| | |
|---|---|
| **Problem** | Co-Star & The Pattern describe who you are, not what to do. Nobody reads the whole chart in combination. |
| **Solution** | Natal chart reading that works like a professional astrologer — Venus + Rising + Midheaven + Saturn → how to look, how to position your career, what to post, what drains/restores energy. |
| **Audience** | Solopreneurs & content creators, 24–35, digital nomad / traveller context (Bali, SEA), English-speaking. |
| **Platform** | Website (not an app) — mobile-first web → desktop. |
| **Niche** | Glow — style + career/talents + social content + energy through the birth chart. |
| **Status** | Personas + JTBD + IA + Wireframes + Voice done (Lesson 5), main flow only |

Full brief → [CLAUDE.md](./CLAUDE.md)

---

## People

**Primary persona — Маша, "Шукачка своєї природи"**
27–34, digital nomad, солопренер/контент-крейтор, знає астрологію поверхово, хоче конкретних дій.
Приходить у момент кризи або великого рішення. → [personas.md](./personas.md)

**Main Job**
Коли я постійно намагаюсь себе покращити — змінити стиль, зрозуміти кар'єру, бути більш собою — але нічого не приживається і відчуваю що роблю щось не так, я хочу зрозуміти через свою карту яка моя природна мова, щоб перестати воювати з собою і почати жити так, що це відчувається як я. → [jtbd.md](./jtbd.md)

**MVP Top-3 Jobs**
1. Glow Profile — зрозуміти свою природу через карту (core)
2. Wow-момент впізнавання себе (конверсія)
3. Стиль, кар'єра/таланти і соушал контент що реально мої (диференціація)

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

voice.md                 # Voice principles, dictionary, forbidden list, microcopy rules (Урок 5)
microcopy.md             # Весь текст інтерфейсу, по екранах — джерело правди

wireframes/              # Low-fi flows — головний flow готовий, текст англійською за voice.md (Уроки 4–5): онбординг → тизер → checkout → репорт → share
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
| IA — Sitemap | ✅ Done | sitemap.md |
| IA — Flows | ✅ Done | flows.md |
| IA — консолідація | ✅ Done | ia.html |
| Wireframes | ✅ Done (головний flow) | wireframes/ |
| Voice | ✅ Done | voice.md, microcopy.md |
| Concept | ⬜ Not started | |
| Design system | ⬜ Not started | |
| Handoff | ⬜ Not started | |

---

## Key findings

- **Gap:** ніхто не дає реально персоналізований аналіз (по всій карті) + конкретні дії + в одній ніші
- **Ніша:** Glow — стиль + кар'єра/таланти + соушал контент + енергія через карту (Venus + Rising + Midheaven + Saturn) — конкурентів нуль
- **Аудиторія:** солопренери й контент-крейтори — звужено 2026-07-17 (раніше: будь-хто в self-improvement)
- **Тригер:** людина приходить у момент кризи/рішення, не з цікавості (compensatory control)
- **Еталон якості тексту:** CHANI. Еталон actionability: AstroBella "How to show up" format
- **Closest competitor:** Amelie (ameliesadvice.com) — AstroGlow 101, $197
