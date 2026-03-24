# Experiment: hooks-reddit-001

**Status:** Complete
**Date:** March 2026
**Type:** Hook generation — Reddit research method vs. brief-only

---

## Hypothesis

Hooks generated from real Reddit language will outperform hooks written from a product brief alone, across all 5 scoring dimensions.

---

## Setup

- **Product:** Meal prep subscription
- **Subreddits scanned:** r/mealprep, r/EatCheapAndHealthy, r/1200isplenty
- **Posts analysed:** 50 per subreddit (150 total)
- **Method A:** Hooks written from product brief only (control)
- **Method B:** Hooks written using Creative Hook Agent (Reddit research → 3 iterations)
- **Scoring:** 5 dimensions, max 10/10 each

---

## Results

| Dimension | Method A (Brief only) | Method B (Reddit research) |
|---|---|---|
| Specificity | 6.2 | 9.8 |
| Emotional Pull | 7.1 | 9.5 |
| Audience Relevance | 6.8 | 9.9 |
| Clarity | 8.0 | 9.7 |
| Scroll-Stop Power | 5.9 | 9.6 |
| **Average** | **6.8** | **9.7** |

---

## Key Learning

Reddit research dramatically improved specificity and audience relevance. The biggest gain was in **scroll-stop power** (+3.7) — the research surfaced a specific moment (Tuesday 9pm + Uber Eats) that the brief never would have.

The phrase *"I know what I should eat, I just don't make it happen"* appeared in 34% of comments. Mirroring this language back in Hook 4 was the single highest-relevance hook produced.

---

## Output

See [`sample_output.md`](../../creative-hook-agent/examples/sample_output.md) for the full working script and final hooks.

---

## What This Changes

- Reddit research is now the default first step in all hook briefs
- "Brief-only" hooks are no longer submitted without at least one round of Reddit validation
- The Tuesday 9pm Uber Eats hook is being tested live in paid — results by April 2026
