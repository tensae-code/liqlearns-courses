# The Bisection Method

## Do it first

The first refining method Grade 12 teaches is the tortoise of numerical methods: it cannot be fooled, it cannot be hurried, and its error is known to the digit at every step.

## Sub lesson 1 — Halve and keep the sign change

Given a **bracket [a, b]** (f of opposite signs at its ends), bisection computes the **midpoint** c = (a + b) / 2 and tests f(c): the half-interval whose ends **still change sign** becomes the new bracket — if f(a)·f(c) < 0, the root is in [a, c]; else in [c, b]. Each step halves the cage. The root itself is never computed — it is **cornered**, until the cage is smaller than the demanded precision and any point of it (the midpoint, say) may be reported as the root, with the cage's width as its error bound.

In your mind's eye: halve and keep the sign change.

## Sub lesson 2 — The arithmetic of certainty — error and step count

After **n steps**, the bracket's width is **(b − a) / 2ⁿ** — certainty you can count in advance: to squeeze [0, 1] below 10⁻³ needs 10 steps (2¹⁰ = 1024). Bisection will never run away, never divide by a slope, never be fooled by the function's shape — its price is this **fixed, unhurried rate** (one binary digit of precision per step), which faster methods beat when they behave and disgrace themselves when they don't. The method is the chapter's benchmark of honesty: certainty first, speed as a luxury.

In your mind's eye: the arithmetic of certainty — error and step count.

## Say it to your companion

Tell your companion, in your own words: Given a **bracket [a, b]** (f of opposite signs at its ends), bisection computes the **midpoint** c = (a + b) / 2 and tests f(c): the half-interval whose ends **still change sign** becomes the new bracket — if f(a)·f(c) < 0, the root is in [a, c]; else in [c, b]. Each step halves the cage. The root itself is never computed — it is **cornered**, until the cage is smaller than the demanded precision and any point of it (the midpoint, say) may be reported as the root, with the cage's width as its error bound. After **n steps**, the bracket's width is **(b − a) / 2ⁿ** — certainty you can count in advance: to squeeze [0, 1] below 10⁻³ needs 10 steps (2¹⁰ = 1024). Bisection will never run away, never divide by a slope, never be fooled by the function's shape — its price is this **fixed, unhurried rate** (one binary digit of precision per step), which faster methods beat when they behave and disgrace themselves when they don't. The method is the chapter's benchmark of honesty: certainty first, speed as a luxury. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Halves the bracket and keeps the half whose ends still change sign. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: By the sign of f at the midpoint — f(a)·f(c) < 0 keeps [a, c]. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — it is cornered; a cage-point is reported with the cage's width as error bound. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A bracket from separation — f of opposite signs at the ends. Do this with a real example of your own and write or say how you know it is right.
