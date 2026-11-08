# Reciprocal Equations

## You do it first

Look at the polynomial 3x⁴ + 4x³ − 14x² + 4x + 3. Before you solve anything, look only at its numbers: 3, 4, −14, 4, 3.

Do you see it? Read them backwards and nothing changes. That little symmetry — invisible if you only stare at the x's — is a machine for solving the equation. This lesson is that machine.

## Sub lesson 1 — What a Reciprocal Polynomial Is

### What a reciprocal polynomial is

A polynomial is **reciprocal** when its coefficients read the same forwards and backwards: the first equals the last, the second equals the second-to-last, and so on. Venezuela's Grade 11 book defines it in the language of the function itself: p is reciprocal when

**p(1/x) = p(x)/xⁿ**

where n is the degree — replacing x by 1/x gives back the same polynomial, divided by xⁿ. The two statements are the same fact: flip the polynomial over (that is what 1/x does) and the coefficients land in reverse order, so the polynomial survives exactly when its coefficient list is a palindrome. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed p. 75.)

Examples: 2x³ + 3x² + 3x + 2 (coefficients 2, 3, 3, 2) and 3x⁴ + 4x³ − 14x² + 4x + 3 (coefficients 3, 4, −14, 4, 3) are reciprocal. One zero anywhere breaks the pattern unless its mirror position is also zero.

## Sub lesson 2 — Roots in Reciprocal Pairs

### Roots come in reciprocal pairs

Here is the first gift. Suppose r ≠ 0 is a root of a reciprocal equation. Then by the definition,

p(1/r) = p(r)/rⁿ = 0/rⁿ = 0,

so **1/r is a root too**. Roots of a reciprocal equation arrive in mirror pairs r and 1/r. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed p. 75.)

Two consequences follow at once. If you find one root by any method at all, its reciprocal is a second root with no extra work. And x = 0 can never be a root of a reciprocal equation whose constant term is not 0 — because p(0) is the constant term itself. That second fact is what licenses the division by x² in the even-degree method below.

## Sub lesson 3 — Odd Degree — the Root −1

### Odd degree: the root −1 is guaranteed

The map x → 1/x has fixed points where x = 1/x, namely x = 1 and x = −1. In a reciprocal equation of **odd** degree, the roots pair off as r with 1/r — and an odd count of roots leaves one root unpaired, sitting at a fixed point. The book shows it is −1 that always occurs: **every odd-degree reciprocal polynomial has the root −1.** (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed p. 76.)

So an odd-degree reciprocal equation opens itself:

Solve 2x³ + 3x² + 3x + 2 = 0. The root −1 is guaranteed — check: −2 + 3 − 3 + 2 = 0. Divide by (x + 1) with Ruffini's synthetic division: the coefficients 2, 3, 3, 2 give the quotient 2x² + x + 2. Its discriminant is 1² − 4·2·2 = −15, negative, so it has no real roots. The equation's only real root is **x = −1**, and the symmetry handed it to us before any hunting. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed p. 76.)

## Sub lesson 4 — Even Degree — Folding in Half

### Even degree: fold it in half

For even degree there is no guaranteed root, but there is something better: the equation **folds**. Divide by x² (legal, since 0 is not a root) and group each term with its mirror:

3x⁴ + 4x³ − 14x² + 4x + 3 = 0
⟹ 3(x² + 1/x²) + 4(x + 1/x) − 14 = 0.

Now substitute **y = x + 1/x**. The second group is y, and the first is one step away:

x² + 1/x² = (x + 1/x)² − 2 = y² − 2.

The quartic becomes a quadratic: 3(y² − 2) + 4y − 14 = 0, that is **3y² + 4y − 20 = 0**, with roots y = 2 and y = −10/3. Unfold each value of y:

- x + 1/x = 2 ⟹ x² − 2x + 1 = 0 ⟹ x = 1 (a double root);
- x + 1/x = −10/3 ⟹ 3x² + 10x + 3 = 0 ⟹ x = −1/3 or x = −3.

The roots are 1 (twice), −1/3 and −3 — and the pairing checks them: −3 and −1/3 are reciprocals, and 1 pairs with itself. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed p. 77.)

## Do it yourself

1. Which of these are reciprocal? (a) x⁴ − 3x³ + 2x² − 3x + 1 (b) 5x³ + x² + x + 5 (c) 2x⁵ + 7x⁴ − x³ + 7x² + 2x. Read each coefficient list backwards before you answer.
2. A reciprocal equation has root x = 5. Name another root, and say which printed page's fact you used.
3. Solve 3x³ + 2x² + 2x + 3 = 0 by opening it with its guaranteed root, then dividing out.
4. Solve x⁴ − 5x³ + 8x² − 5x + 1 = 0 by the fold: divide by x², set y = x + 1/x, and unfold. (Check your roots with the pairing test before you trust them.)
5. Explain, in one sentence each, why x = 0 is never a root of these equations, and why an odd-degree reciprocal equation cannot dodge the root −1.
