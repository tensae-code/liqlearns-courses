# Hands-on — Numerical Methods

## Activity 1 — Trap the root (10 minutes)

For f(x) = x² − 5, the learner tabulates f at x = 2, 2.1, 2.2, 2.3, 2.4, 3 and marks every sign change. The bracket narrows from [2, 3] to [2.2, 2.3] (f(2.2) = −0.16, f(2.3) = 0.29). The learner states the root to one decimal place — 2.2 — and says what the bracket guarantees and what it does not.

## Activity 2 — Two Newton steps (10 minutes)

Starting at x₀ = 2 for x² − 5 = 0, the learner computes x₁ = 2 − (−1)/4 = 2.25 and x₂ = 2.25 − 0.0625/4.5 ≈ 2.2361, checking each new value by squaring it (2.25² = 5.0625; 2.2361² ≈ 5.0001). The learner says why each tangent step lands closer than the bracket did.

## Activity 3 — The rearrangement race (15 minutes)

For x² − 5 = 0, iterate two rearrangements from x₀ = 2, four steps each: (a) x = 5/x, giving 2, 2.5, 2, 2.5, … — it cycles and never settles; (b) x = (x + 5/x)/2, giving 2, 2.25, 2.2361, … — it converges. The learner computes |g′| at the root for each ((a) |−5/x²| = 1 at x = √5 — not less than 1; (b) |(1 − 5/x²)/2| = 0 at x = √5) and matches the prediction to the race's result.
