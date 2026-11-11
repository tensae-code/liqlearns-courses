# Roots and Coefficients of a Cubic Equation

You do it, we guide you. Start with a cubic whose roots you
already know, and watch its coefficients confess where they
came from.

## Sub lesson 1 — The Three Relations

Take the cubic with roots 1, 2 and 3. Its factors are
(x − 1)(x − 2)(x − 3), and multiplying out:

(x − 1)(x − 2) = x² − 3x + 2, and (x² − 3x + 2)(x − 3) =
**x³ − 6x² + 11x − 6**.

Now compare the coefficients with the roots α = 1, β = 2,
γ = 3:

- α + β + γ = 1 + 2 + 3 = **6** — the x² coefficient with
  its sign flipped (−(−6)).
- αβ + βγ + γα = 2 + 6 + 3 = **11** — the x coefficient,
  sign unchanged.
- αβγ = 1 × 2 × 3 = **6** — the constant term with its sign
  flipped (−(−6)).

This is true for every cubic. For

**x³ + bx² + cx + d = 0** with roots α, β, γ:

- **α + β + γ = −b**
- **αβ + βγ + γα = c**
- **αβγ = −d**

If the x³ coefficient is not 1 — for ax³ + bx² + cx + d =
0 — divide through by a first, which gives the general
form: sum = **−b/a**, sum of pairs = **c/a**, product =
**−d/a**. (The quadratic case you may know — α + β = −b/a,
αβ = c/a — is the same pattern with one root fewer; this
lesson is that pattern grown by one root.)

## Sub lesson 2 — Building a Cubic from Its Roots

The relations run backwards. Given roots α, β, γ, first
form the three sums, then write:

**x³ − (sum)x² + (pairs)x − (product) = 0.**

Roots −1, 2 and 5: sum = −1 + 2 + 5 = 6; pairs =
(−1)(2) + (2)(5) + (5)(−1) = −2 + 10 − 5 = 3; product =
(−1)(2)(5) = −10. The cubic is

**x³ − 6x² + 3x + 10 = 0.**

Check it by expanding the factors: (x + 1)(x − 2)(x − 5) =
(x + 1)(x² − 7x + 10) = x³ − 6x² + 3x + 10. It agrees — the
check is part of the method, not an extra. Notice the sign
pattern in the built equation: minus, plus, minus, marching
with sum, pairs, product.

## Sub lesson 3 — Using the Relations

The relations answer questions about roots **without
solving the cubic**.

**Finding a missing root.** x³ − 4x² + x + 6 = 0 has roots
2 and −1 and a third root γ. The sum of the roots is 4, so
2 + (−1) + γ = 4 and **γ = 3**. Check with the product:
2 × (−1) × 3 = −6 = −d. It agrees.

**Finding an unknown coefficient.** x³ − 2x² + kx + 6 = 0
has roots 1, 3 and γ. The product gives 1 × 3 × γ = −6, so
γ = −2. Then the pairs give k = (1)(3) + (3)(−2) + (−2)(1)
= 3 − 6 − 2 = **−5**.

**Sums of squares.** α² + β² + γ² is not a fourth relation
to memorise; it is built from the first two:

**α² + β² + γ² = (α + β + γ)² − 2(αβ + βγ + γα).**

For the roots 1, 2, 3: 6² − 2 × 11 = 36 − 22 = 14 — and
indeed 1 + 4 + 9 = 14.

That is the whole lesson: three relations — sum, pairs,
product — read off the coefficients, run backwards to build
an equation from roots, and used to recover unknowns the
equation would rather keep hidden.

## Do It Yourself

1. For x³ − 7x² + 14x − 8 = 0, write down the sum, the sum
   of pairs and the product of the roots (7; 14; 8). Then
   guess three whole-number roots and test your guess
   against all three (1, 2 and 4).
2. Build the monic cubic with roots 0, 2 and 4
   (x³ − 6x² + 8x = 0) and check it by expanding
   x(x − 2)(x − 4).
3. The cubic x³ − 5x² + 8x − 4 = 0 has roots 1 and 2 and a
   third root γ. Find γ from the sum (γ = 2), then confirm
   with the product (1 × 2 × 2 = 4 = −d) and the pairs
   (2 + 4 + 2 = 8).
4. Explain to a friend why the product of the roots of a
   monic cubic is −d and not d. Use the factored form
   (x − α)(x − β)(x − γ) and follow the constant term
   through the multiplication.
