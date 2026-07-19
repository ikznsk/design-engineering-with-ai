# Screens — Astro Recipe
# Головний flow: Main Job — отримати Glow Report

> Джерела: sitemap.md, flows.md, jtbd.md
> Дата: 2026-07-10 · переписано 2026-07-19 під funnel-архітектуру (не app)
>
> **Що змінилось 2026-07-19:** продукт — лінійний funnel (onboarding → безкоштовний тизер → paywall → checkout → платний репорт), не app з навігацією між секціями. `glow-profile.html`, `glow-style.html`, `glow-routine.html` з попередньої версії видалені — Style/Career/Energy/Social Content тепер розділи всередині Glow Report (одного PDF/сторінки-звіту), не окремі екрани сайту. Деталі — CLAUDE.md → Core User Flow, sitemap.md.

---

## Ключові екрани головного flow

| Екран | Назва (з sitemap.md) | Job (з jtbd.md) | Місце у flow |
|-------|----------------------|-----------------|--------------|
| **welcome** | Welcome / Hook | Main Job — перша обіцянка | Старт, до введення даних |
| **onboarding-date** | Введення дати народження | Main Job — збір даних для карти | Крок 1.2 онбордингу |
| **onboarding-time** | Введення часу народження | Main Job — точність карти | Крок 1.3 онбордингу |
| **onboarding-place** | Введення місця народження | Main Job — збір даних для карти | Крок 1.4 онбордингу (місце = найскладніший стан) |
| **onboarding-question** | Питання "що зараз відбувається?" | Main Job + Emotional job — тригер кризи | Крок 1.5 онбордингу |
| **onboarding-question-2** | Додаткове питання (опціональне, зміст TBD) | Main Job + Emotional job | Крок 1.6 онбордингу, перед розрахунком |
| **results** | Результати — безкоштовний тизер | Main Job, Emotional job + R1, Конверсія | Після розрахунку карти. Одна сторінка зі скролом: 2.1 чарт+коротко (wow) → 2.2 CTA розблокувати репорт + прев'ю + відгуки |
| **checkout** | Email + оплата | Конверсія | Після натискання "Розблокувати репорт" |
| **report** | Glow Report | Main Job — глибина, R1–R4 (стиль, кар'єра, енергія, соушал контент) | Після успішної оплати |
| **share** | Мій Glow тип — картка | Social job | Доступно з results, без покупки |

> Профіль (5.1/5.2, [SIROTA]) — технічна необхідність без job, без persistent навігації сенс сумнівний. Відкладено на крок 8, не в головному flow.

---

## Таблиця екран × стан

| Екран | empty | error | loading | success |
|-------|-------|-------|---------|---------|
| **welcome** | — | — | — | ✓ |
| **onboarding-date** | ✓ поле порожнє | ✓ невалідна дата | — | ✓ дата введена |
| **onboarding-time** | — | — | — | ✓ (містить опцію "не знаю точний час") |
| **onboarding-place** | ✓ поле порожнє | ✓ місто не знайдено | ✓ пошук міста | ✓ місто обрано |
| **onboarding-question** | — | — | — | ✓ (пропуск = теж success, просто без відповіді) |
| **onboarding-question-2** | — | — | — | ✓ (опціональне, той самий патерн) |
| **results** | — | ✓ помилка розрахунку карти | ✓ розраховуємо чарт | ✓ тизер готовий |
| **checkout** | — | ✓ оплата не пройшла | ✓ обробка оплати | ✓ оплата пройшла → репорт |
| **report** | — | — | — | ✓ |
| **share** | — | — | — | ✓ |

**Пояснення порожніх станів:**
- welcome, onboarding-time, onboarding-question, onboarding-question-2, report, share: порожнього сценарію немає — welcome завжди показується, питання опціональні (пропуск ≠ порожній стан, це success), report існує лише після оплати (немає проміжного порожнього)
- results, checkout: попередній крок (розрахунок карти / клік "розблокувати") завжди щось передає — порожнього стану не буває, тільки loading/error/success

**Назви файлів:**
```
welcome.html
onboarding-date.html          onboarding-date-empty.html    onboarding-date-error.html
onboarding-time.html
onboarding-place.html         onboarding-place-empty.html   onboarding-place-error.html   onboarding-place-loading.html
onboarding-question.html
onboarding-question-2.html
results.html                  results-error.html             results-loading.html
checkout.html                 checkout-error.html            checkout-loading.html
report.html
share.html
```
