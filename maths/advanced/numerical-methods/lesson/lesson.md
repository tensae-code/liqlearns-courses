# Numerical Methods

## You do it first

Try to solve x² − 5 = 0 exactly. You can — the root is √5. Now try x⁵ − x − 1 = 0, or cos x = x. No formula exists. Yet the roots are real numbers, and engineers need them to several decimal places.

This lesson is the toolkit for that situation, as Rwanda's Senior Five **Advanced** book teaches it: estimate, trap, then close in. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 4, printed pp. 105–126.)

## Linear interpolation and extrapolation

Between two known points (x₁, y₁) and (x₂, y₂), the straight line joining them gives an estimate for any x in between:

    y ≈ y₁ + (x − x₁) × (y₂ − y₁)/(x₂ − x₁)

Estimating **between** the known points is **interpolation**; estimating **beyond** them, on the same line extended, is **extrapolation** — quicker to say than to trust, because nothing guarantees the curve keeps following the line outside the known stretch. Applied to a function table with the target value 0, interpolation also gives a first estimate of a root: if f(2) = −1 and f(3) = 4 for f(x) = x² − 5, the crossing sits at about x = 2 + (0 − (−1)) × 1/5 = 2.2. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 4, printed pp. 105–112. The book's worked interpolation example on p. 111 prints two decimal slips in its intermediate lines; its final value is correct, and the method is taught here in corrected form.)

## Locating a root by sign change

If f is continuous and f(a) and f(b) have **opposite signs**, then f must cross zero somewhere between a and b: **a root lies in (a, b)**. Two ways to work the trap:

- **Analytically (tabulation):** evaluate f at a sequence of points and watch for the sign change, then re-tabulate inside the smaller bracket. For x² − 5: f(2) = −1, f(3) = +4 — root in (2, 3); f(2.2) = −0.16, f(2.3) = +0.29 — root in (2.2, 2.3); each round of tabulation buys another decimal place.
- **Graphically:** sketch or plot y = f(x) and read off where the graph crosses the x-axis; the crossing's neighbours with opposite signs give the bracket.

The sign-change test locates; it does not by itself refine quickly — that is what the next two methods are for. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 4, printed pp. 111–118. The book's graphical example on p. 115 closes by naming an interval copied from the previous example; the root value it finds, ≈ 3.2, is correct, and the interval is taught corrected here — it belongs to that example's own bracket.)

## Newton–Raphson

Stand at a guess x₀ on the curve y = f(x). The tangent there meets the x-axis at a better guess. Repeating gives the **Newton–Raphson iteration**:

    xₙ₊₁ = xₙ − f(xₙ)/f′(xₙ)

For x² − 5 = 0, f′(x) = 2x, starting at x₀ = 2:

    x₁ = 2 − (−1)/4 = 2.25
    x₂ = 2.25 − 0.0625/4.5 ≈ 2.2361      (√5 = 2.23607…)

Two steps, four correct decimals — the method roughly doubles the correct digits at each step near the root. Its dangers are the mirror of its speed: a start where f′(x) ≈ 0 throws the next guess far away, and a careless start can cycle or land on a different root. Bracket first, then Newton. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 4, printed pp. 118–122.)

## Fixed-point iteration: x = g(x)

Rearrange the equation into the form **x = g(x)** and iterate: x₁ = g(x₀), x₂ = g(x₁), … If the values settle, they settle on a root, because a settled value satisfies x = g(x), which is the original equation in disguise.

The catch — the heart of the book's treatment — is that **the rearrangement decides everything**. For x² − 5 = 0:

- g(x) = 5/x: from 2 the iterates run 2, 2.5, 2, 2.5, … — a cycle that never settles.
- g(x) = (x + 5/x)/2: from 2 the iterates run 2, 2.25, 2.2361, … — straight to √5.

The test that predicts the behaviour is the derivative at the root: iteration converges when **|g′(x)| < 1** near the root. Here |−5/x²| = 1 at x = √5 — not less than 1, and the first rearrangement fails; |(1 − 5/x²)/2| = 0 at x = √5, and the second flies. Same equation, same start — different rearrangement, different fate. Comparing rearrangements before iterating is the skill. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 4, printed pp. 122–126.)

> **Tip — from us, not from the books:** never iterate blind. First trap the root in a sign-change bracket — then whichever closing method you choose, you can always check its answer against the bracket, and a runaway iteration is caught at once instead of being copied down as an answer.

## Say it to your companion

Explain to your companion why a sign change guarantees a root but no sign change does not guarantee there is none. Then have them explain why x = 5/x and x = (x + 5/x)/2, rearrangements of the same equation, behave so differently.

## Do It Yourself

1. f(1) = −3 and f(2) = 5 for a continuous f. What can you conclude, and what is the interpolated estimate of the root?
2. Use two Newton–Raphson steps from x₀ = 3 to estimate the root of x² − 7 = 0. Check by squaring.
3. For x² − 2 = 0, iterate g(x) = 2/x and g(x) = (x + 2/x)/2 twice each from x₀ = 1. Which rearrangement would you keep, and what does |g′(√2)| say?
