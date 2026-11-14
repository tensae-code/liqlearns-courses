# The Chord Method

## Do it first

Bisection ignores the function's values; it only reads their signs. Grade 12's second method listens to the values too: if one end is barely positive and the other hugely negative, the root is surely near the small end.

## Sub lesson 1 — The chord's crossing — values, not only signs

Draw the **chord** — the straight segment joining the points (a, f(a)) and (b, f(b)). Where it crosses the x-axis, at **c = a − f(a)·(b − a) / (f(b) − f(a))**, stands the method's next estimate: the root as if the function were its chord. Test f(c) and **replace the end whose f has the same sign as f(c)** — the bracket narrows, always keeping opposite signs, but from the side the values accuse. The midpoint was democracy; the chord is cross-examination.

[Picture — The chord's crossing — values, not only signs]

## Sub lesson 2 — Speed and its condition — the honest slope

When the function is **nearly straight** across the bracket, the chord's crossing lands almost on the root: convergence in a few steps where bisection needed dozens. The method's assumption is exactly that honesty: a **strongly curving** function can make one bracket end **stick** (its f always losing the comparison), narrowing from one side only — slower, but still bracketed, still certain, because the sign discipline is never surrendered. The stopping rule serves both methods: when the bracket (or the step |c_new − c_old|) is under the demanded precision, report c with its bound.

[Picture — Speed and its condition — the honest slope]

## Say it to your companion

Tell your companion, in your own words: Draw the **chord** — the straight segment joining the points (a, f(a)) and (b, f(b)). Where it crosses the x-axis, at **c = a − f(a)·(b − a) / (f(b) − f(a))**, stands the method's next estimate: the root as if the function were its chord. Test f(c) and **replace the end whose f has the same sign as f(c)** — the bracket narrows, always keeping opposite signs, but from the side the values accuse. The midpoint was democracy; the chord is cross-examination. When the function is **nearly straight** across the bracket, the chord's crossing lands almost on the root: convergence in a few steps where bisection needed dozens. The method's assumption is exactly that honesty: a **strongly curving** function can make one bracket end **stick** (its f always losing the comparison), narrowing from one side only — slower, but still bracketed, still certain, because the sign discipline is never surrendered. The stopping rule serves both methods: when the bracket (or the step |c_new − c_old|) is under the demanded precision, report c with its bound. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The straight segment joining (a, f(a)) and (b, f(b)). Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Its crossing with the x-axis — the next estimate c. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The end whose f has the same sign as f(c) — so the bracket keeps opposite signs. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: They accuse the nearness — the root sits nearer the end whose |f| is smaller. Do this with a real example of your own and write or say how you know it is right.
