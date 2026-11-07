# Lesson plan — Reciprocal Equations

**One thing:** reciprocal polynomials — the ones whose coefficients read the same forwards and backwards — and the special way their equations are solved: roots come in reciprocal pairs, odd degree always hides the root −1, and even degree folds in half with the substitution y = x + 1/x.

**Stage:** Algebra (Stage 6). **Level 154** (Venezuela merge, 2026-11-07).

**Why this lesson exists:** Venezuela's Grade 11 book (*La Matemática y el Vivir Bien*, Lesson 3, printed pp. 75–77) teaches reciprocal equations as a named class inside its polynomials lesson: the definition p(1/x) = p(x)/xⁿ, that is, symmetric coefficients; the theorem that an odd-degree reciprocal polynomial always has the root −1; and the even-degree method — divide by x² and substitute y = x + 1/x. No other read book in the library names this class, and no existing lesson is about it: the polynomial-division lesson covers dividing and the root theorems, and the quadratic-equations lesson covers degree 2, but the symmetry trick itself has no home. So under the everything-goes-in ruling (2026-11-06) it gets its own lesson. It stands alone: polynomial-division is a soft hint before it, never a gate.

## The climb

1. **What a reciprocal polynomial is** — the coefficients are palindromic: aₖ = aₙ₋ₖ for every k; equivalently xⁿ·p(1/x) = p(x). Examples: 2x³ + 3x² + 3x + 2 and 3x⁴ + 4x³ − 14x² + 4x + 3.
2. **Roots come in reciprocal pairs** — if r ≠ 0 is a root, then p(1/r) = p(r)/rⁿ = 0, so 1/r is a root too. Finding one root hands you another one free.
3. **Odd degree: the root −1 is guaranteed** — 1/x has the fixed point −1, and in odd degree the pairing r ↔ 1/r leaves −1 over: every odd-degree reciprocal equation has the root −1. Divide it out (Ruffini) and solve what remains: 2x³ + 3x² + 3x + 2 = (x + 1)(2x² + x + 2), and the quadratic's discriminant is negative, so −1 is the only real root.
4. **Even degree: fold it in half** — x = 0 is never a root (the constant term is not 0), so divide by x² and group the symmetric terms: a(x² + 1/x²) + b(x + 1/x) + c = 0. With y = x + 1/x and x² + 1/x² = y² − 2, the quartic becomes a quadratic in y.
5. **The full solve** — 3x⁴ + 4x³ − 14x² + 4x + 3 = 0 folds to 3y² + 4y − 20 = 0, giving y = 2 and y = −10/3; back-substituting gives x = 1 (double), x = −1/3 and x = −3 — and the pairs check themselves: −3 ↔ −1/3, and 1 ↔ 1.

## Add-on slots

- slot-reciprocal-0 (IMAGE): the coefficient list 3, 4, −14, 4, 3 written in a row with curved arrows joining the matching pairs (3↔3, 4↔4) and −14 alone in the middle. What the student does: reads the list forwards and backwards aloud and says why the polynomial is reciprocal.
- slot-reciprocal-1 (GIF, 1–2 s): the quartic 3x⁴ + 4x³ − 14x² + 4x + 3 folding — the x² term stays in the middle while x⁴ pairs with 3 and x³ pairs with 4x — until it becomes 3(x² + 1/x²) + 4(x + 1/x) − 14. What the student does: points to each pair as it folds and names the partner term.
- slot-reciprocal-2 (IMAGE): a number line with the roots −3 and −1/3 joined by an arc labelled "reciprocals", and 1 marked twice with the note "pairs with itself". What the student does: checks that −3 × −1/3 = 1 in the product sense — each is 1 over the other — and finds the reciprocal partner of 2 and of −1/2.
