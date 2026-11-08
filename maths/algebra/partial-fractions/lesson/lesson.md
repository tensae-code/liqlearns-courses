# Partial Fractions — the lesson

Course: Maths · Unit: Unit 6 — Algebra · Lesson: Partial Fractions
Built from: South Sudan, Secondary Additional Mathematics, Student's Book 4 (Unit 4) — Pakistan, Class 11 Mathematics (Unit 5) and Class 10 Mathematics (Unit 4) — Bangladesh, Class 9 (Ch. 4 §10.8) — Jordan, Grade 12 Student's Book, Term 1 — Kuwait, Grade 12 Term 2 student book (scientific track) (§5-6)

## Do it first
Add these into one fraction: 1/(x + 1) + 2/(x − 1). Over the common denominator (x + 1)(x − 1) = x² − 1 the top becomes (x − 1) + 2(x + 1) = 3x + 1. So 1/(x + 1) + 2/(x − 1) = (3x + 1)/(x² − 1). Now the reverse question, which is this whole lesson: handed the single fraction (3x + 1)/(x² − 1), could you have split it back into those two pieces? You could — and the pieces are far easier to integrate and to work with than the whole. Splitting is called resolving into **partial fractions**.

## Sub lesson 1 — Distinct Linear Factors
**Proper before you split.** A rational fraction N(x)/D(x) is **proper** when the numerator's degree is below the denominator's, and **improper** when it is not. Partial fractions are written for proper fractions; an improper one is divided first (that is Level 58's work) into a polynomial plus a proper remainder-fraction. Pakistan's Class 11 book opens its unit exactly here — proper and improper, reduction by long division, and the point that the split is an *identity*, true for every x (Unit 5, pp.78–87) — and its Class 10 book does the same before its four rules (Unit 4, pp.74–84). South Sudan's Secondary 4 Additional book opens its unit by saying what partial fractions are and why they help integration (Unit 4, pp.126–127).

**Distinct linear factors.** Factorise the denominator. Each distinct linear factor gets one piece with a constant on top. For (3x + 1)/(x² − 1) = A/(x + 1) + B/(x − 1), multiply through by (x² − 1): 3x + 1 = A(x − 1) + B(x + 1). Two clean ways to the constants, both taught in South Sudan's book (pp.128–135): *substitution* — put in the value that kills a piece: x = 1 gives 4 = 2B, so B = 2; x = −1 gives −2 = −2A, so A = 1. Or *comparing coefficients* — the x-terms give A + B = 3 and the constants give −A + B = 1, the same A = 1, B = 2. The split is 1/(x + 1) + 2/(x − 1) — exactly the pair you rejoined in Do it first, and exactly Bangladesh's Class 9 worked example (§10.8, pp.107–111). Pakistan's Class 10 book calls substitution the "zero's method" and works (5x + 4)/((x − 4)(x + 2)) = 4/(x − 4) + 1/(x + 2) (Unit 4). One honest warning from South Sudan: a worked example in its book (printed pp.130–131) prints its working in a tangle — learn the method from the clean working here; that example's final answers, A = 3/4 and B = −1/4, were checked and stand.

## Sub lesson 2 — A Repeated Linear Factor

**A repeated linear factor.** A factor that appears twice demands two pieces — one over the factor, one over its square. Bangladesh's book works the full case: (x + 2)/((x − 1)²(x + 1)) = −1/[4(x − 1)] + 3/[2(x − 1)²] + 1/[4(x + 1)] (§10.8, pp.107–111). Note the shape: pieces over (x − 1), over (x − 1)², and over (x + 1) — miss the squared piece and no values of the constants can ever fit. Pakistan carries this as its Case II in both its Class 10 rules and its Class 11 cases.

## Sub lesson 3 — A Quadratic Factor

**A quadratic factor.** An irreducible quadratic factor — one that will not split into linear factors over the real numbers — gets a piece with a **linear** numerator: (Ax + B)/(quadratic). Pakistan's Class 11 book runs the full set of four cases: I distinct linear, II repeated linear, III non-repeated irreducible quadratic, IV repeated irreducible quadratic (Unit 5, pp.78–87). A clean Case III: 1/(x(x² + 1)) = 1/x − x/(x² + 1) — check by rejoining: (x² + 1 − x²)/(x(x² + 1)) = 1/(x(x² + 1)). South Sudan treats quadratic factors, repeated linear and irreducible quadratic together (Unit 4, pp.136–142).

## Sub lesson 4 — Divide First When Improper

**Improper? Divide first.** (3x² + 1)/(x² − 1): the degrees are equal, so divide — the quotient is 3 with remainder 4, giving 3 + 4/(x² − 1), and only then split the proper part: 4/(x² − 1) = 2/(x − 1) − 2/(x + 1). Bangladesh works this very example and a second, (x³ + 1)/(x² + 1) = x − (x − 1)/(x² + 1), where the leftover piece's numerator is already linear over an irreducible quadratic (§10.8, pp.107–111).

## Sub lesson 5 — Integration and Recombining

**Why bother — integration.** A split fraction integrates piece by piece into logarithms. Kuwait's Grade 12 book integrates by partial fractions in §5-6 (pp.42–49) — for **distinct linear factors only**; its book teaches no repeated or quadratic case, and this lesson claims no more for it. Its worked result 2 ln|x + 3| + 3 ln|x − 5| + C comes from splitting (5x − 1)/((x + 3)(x − 5)) = 2/(x + 3) + 3/(x − 5). Jordan's Grade 12 book teaches partial fractions as a lesson of its own (Term 1, L2, p.23) and then uses them inside integration (integration by partial fractions, p.45). South Sudan likewise applies its splits to integration (Unit 4, pp.143–146) — and closes the circle by expressing partial fractions back as a single fraction (pp.147–148), the rejoining check you met at the start.

> Tip — from us, not from the books: after every split, spend twenty seconds rejoining your pieces over a common denominator. If the top does not come back to the original numerator, the constants are wrong — and you will know it now, not three pages later.

## Say it to your companion
Say the shapes whole: "Distinct linear factors: a constant over each." "A repeated factor: a piece for every power." "An irreducible quadratic: A x plus B on top." "Improper: divide first." Then your companion names a denominator — (x − 2)(x + 5), (x + 1)², x(x² + 4), (x² − 1) with numerator x³ — and you set up the pieces, letters and all, without solving.

## Do It Yourself
1. Split (7x + 1)/((x − 1)(x + 2)) into partial fractions, by substitution.
2. Split 1/((x − 3)(x + 3)) into partial fractions.
3. Set up, then solve: (3x + 5)/((x − 2)²) — write both pieces a repeated factor demands, and find their constants... check first whether a single squared denominator needs a piece over (x − 2) as well as over (x − 2)².
4. Split (x³ + 1)/(x² + 1) by dividing first, following Bangladesh's worked example.
5. Recombine 2/(x + 3) + 3/(x − 5) into a single fraction, and name the integral of the single fraction.
