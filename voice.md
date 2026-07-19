# Voice — Astro Recipe

> Lesson 5. Voice is rules, not mood.
> Date: 2026-07-19 · translated to English 2026-07-19 (product copy is English-first — audience is English-speaking, per CLAUDE.md)
> Sources: CLAUDE.md, personas.md, jtbd.md, research.md, microcopy.md

---

## Principles

### 1. Every insight ends in a concrete action, not a character description

**Rule:** no line about the person stops at "you are like this" — a statement about who they are is always followed by what to do about it.

**Example:** "Sticking point: Saturn in the 10th house often means fear of looking unready. Concrete step: set yourself a deadline for one public move this week, even an imperfect one." (report.html)

**Counter-example:** "You're a creative, deep person."

**Explanation:** CLAUDE.md → Problem: "They describe WHO you are but not WHAT TO DO"; `research.md` → video-analysis, CHANI: "describes WHO you are, not WHAT TO DO" — this is a direct product differentiator, not a stylistic preference.

---

### 2. Every claim is anchored to a specific chart placement, not an abstract trait

**Rule:** whenever the text claims something about the person, it names a specific planet, sign, or house — never just a personality trait.

**Example:** "Mercury in Gemini makes you quick — you grab new information faster than anyone around you." (results.html)

**Counter-example:** "You're a fast, communicative person."

**Explanation:** `personas.md` → Masha, "Trust triggers": "References to specific planetary positions in her chart (Venus in Taurus, not just 'Venus')". This is precisely what makes her trust the text instead of reading it as a generic sun-sign horoscope.

---

### 3. Honest about limits — the chart shows potential, not a guarantee

**Rule:** the text never promises an outcome or rates the person's level of development — it only points a direction and leaves the action to them.

**Example:** report.html's tone — "you'd do well to position yourself as someone who follows through" (a direction, not a guarantee or a verdict)

**Counter-example:** "Become a woman he never forgets" (Nebula, real competitor quote)

**Explanation:** CLAUDE.md → Critical Product Insight: "The chart shows POTENTIAL, not the person's current level of development"; `research.md` → Nebula: "Critical problem... 'Become a woman he never forgets' — regressive framing." This is a direct point of difference from a competitor that manipulates through the promise of an outcome.

---

### 4. Advice is always tied to this person's chart, never generic

**Rule:** no piece of advice should hold true for just anyone — if a line could be handed to a different person unchanged, it isn't specific enough yet.

**Example:** "Block out at least one hour a day when you're genuinely unreachable" (tied to this person's Moon in Cancer specifically)

**Counter-example:** "Spend time each day appreciating yourself for the unique individual you are" (Nebula, real quote)

**Explanation:** `research.md` → Nebula: "Tasks are generic... not tied to actual planetary positions"; CLAUDE.md → Problem: "Generic self-improvement advice (Nebula's 'spend time with yourself') is not a natal chart reading."

---

## Dictionary

**Address:** "you", informal and direct — consistent on every screen, no exceptions. Contractions are fine ("you're", "it's") — the product talks like a sharp friend, not a form.

| Concept | Term | Why this one |
|---|---|---|
| Move to the next onboarding step | **Next** | One consistent label across every onboarding screen (date, time, place, questions) |
| Paid deliverable (4 sections: style/career/energy/content) | **Glow Report** | Locked in by the 2026-07-17 funnel decision. "Glow Profile" was the pre-pivot name — removed everywhere it survived (welcome.html). |
| Free chart calculation (before checkout) | no product name — just "your chart" / "calculate your chart" | Calling it "Glow Report" would blur the free step with the paid one |
| The calculated birth chart | **chart** (not "natal chart" after first mention) | First reference spells out "natal chart" once for clarity; every later mention just says "chart" — repeating the full term reads stiff |
| Retrying after a failure | context-specific: "Try again" / "Recalculate my chart" / "Try paying again" | **Deliberately not unified** — naming exactly what's being retried follows Principle 1 (concrete action). Three different buttons, three different actions. |

**Loanwords:** "checkout" is fine (standard, neutral payment term). Don't introduce new ones without a reason.

---

## Forbidden

| Never write | Where it showed up | Before → After |
|---|---|---|
| The AI cliché "something went wrong" | Found in `results-error.html` | "Something went wrong while calculating" → "We couldn't calculate your chart. The most common cause is inaccurate birth details" (state the actual fact instead of a vague "something") |
| Motivational tone | "Start your journey", "Become the best version of yourself" | never use — replace with the concrete action ("Calculate my chart") |
| Exclamation marks for excitement | "Welcome!", "All done!" | drop the "!": "Payment went through. Your report has been emailed to you" |
| Emoji in system messages | 🎉 ✅ in success/error states | replace with a plain text fact, no emoji (the "!" glyph in the error icon is an exception — it's a structural indicator, not decoration) |
| The word "successfully" | "Payment went through successfully" | → "Payment went through" (state the fact, no decorative adverb) |
| Apologies in error states | "Sorry, something's wrong" | → straight to "what happened + what to do", no "sorry" |

---

## Microcopy by element type

- **Button** — an action verb, the result is visible: "Unlock my Glow Report", not "OK" or a bare "Next" without context (exception: navigational "Next" in onboarding, where the form right above it already gives the context).
- **Screen heading** — names what this place is, in dictionary terms: "Get your full Glow Report", not just "Results".
- **Form field** — the label says what to enter ("When were you born?"), the hint says why/how ("We need your exact date to place every planet"), the validation error says exactly what to fix ("April 31st doesn't exist — April has 30 days").
- **Empty state** — why it's empty + what to do next: "Enter your birth date to continue."
- **Error** — what happened + what to do, no apologies, no jokes: "Your bank declined the payment. Try a different card..."
- **Loading** — stays silent or says exactly what's loading: "Processing your payment...", not a spinner with no text.
- **Success** — state the fact + the next step, no celebration: "Payment went through — your report is on its way to your inbox", not "Congrats on your purchase!"
- **Destructive action** — warn what will happen and that it can't be undone, before the click. Nothing destructive exists in the MVP flow yet (paying is a commitment, not a destructive action) — this rule is recorded for later use (e.g. deleting data, cancelling a subscription).
