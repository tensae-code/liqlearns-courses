# Taylor and Maclaurin Series — the lesson

Course: Maths · Stage: Stage 12 — Advanced Mathematics · Lesson: Taylor and Maclaurin Series
Built from: Pakistan, Mathematics Class 12 (§2.17 — the sole full source for this lesson)

## Do it first
Add these on a calculator, one at a time: 1, then +1, then +1/2, then +1/6, then +1/24, then +1/120. The running totals go 1, 2, 2.5, 2.667, 2.708, 2.717 — settling on 2.718…, the number e. A string of plain powers and factorials has rebuilt eˣ at x = 1. Pakistan's Class 12 book teaches exactly this rebuilding — a function copied by an endless polynomial — in §2.17 of its differentiation chapter (Ch.2, ch-pp.74–81). This lesson follows that one section, honestly and whole: it is the lesson's only full source.

## Then the explanation
**The Maclaurin template.** A **Maclaurin series** writes a function as a polynomial centred at 0:

f(x) = f(0) + x f′(0) + (x²/2!) f″(0) + (x³/3!) f‴(0) + …

Every coefficient is a derivative of f at 0, divided by the factorial of its power. The factorials are not decoration: they are what makes each term match the function's own rate of change, then its rate of rate of change, at the centre. Pakistan's book builds the section on this template (Ch.2 §2.17, ch-pp.74–81).

**eˣ and aˣ.** For f(x) = eˣ, every derivative is eˣ, so every derivative at 0 is 1, and the series is the cleanest of all:

eˣ = 1 + x + x²/2! + x³/3! + x⁴/4! + … for every x.

Your Do it first was this series at x = 1. For aˣ the derivatives at 0 bring down powers of ln a, giving aˣ = 1 + x ln a + (x ln a)²/2! + (x ln a)³/3! + … — the eˣ series with x replaced by x ln a, which is exactly right, since aˣ = e^(x ln a). The book gives both expansions in the Maclaurin half of the section (ch-pp.74–78).

**sin x.** The derivatives of sin x cycle: sin, cos, −sin, −cos. At 0 they give 0, 1, 0, −1, so only odd powers survive, with alternating signs:

sin x = x − x³/3! + x⁵/5! − x⁷/7! + … for every x (in radians).

Near 0, sin x ≈ x is the first term doing duty alone — good while x stays small, which is why the centre matters, as the Taylor half of the lesson will show (ch-pp.74–78).

**1/(1+x) and (1+x)ⁿ.** Two series in the section carry a condition. The geometric-style expansion

1/(1+x) = 1 − x + x² − x³ + x⁴ − … holds only for |x| < 1:

at x = 2 the partial sums jump 1, −1, 3, −5 and never settle. The binomial expansion (1+x)ⁿ = 1 + nx + n(n−1)x²/2! + n(n−1)(n−2)x³/3! + … ends by itself when n is a whole number; for any other n it is endless and again needs |x| < 1. The book teaches both in the same Maclaurin run (ch-pp.74–78).

Tip — from us, not from the books. Before you use any series, ask two questions: what is the centre, and how far from it am I? A series is a local copy of its function — superb near its centre, and, outside its stated range, not a copy at all.

**Taylor series: a centre that is not 0.** A **Taylor series** is the same build about a general centre a: f(x) = f(a) + (x−a) f′(a) + (x−a)² f″(a)/2! + … (Maclaurin is the case a = 0.) The book — which prints the heading as "TAILOR SERIES", a misprint for Taylor — works ln(1+x) about x = 2 (ch-pp.78–81). Put u = x − 2, so 1 + x = 3 + u = 3(1 + u/3), and ln(1+x) = ln 3 + ln(1 + u/3): expanding the second logarithm gives

ln(1+x) = ln 3 + (x−2)/3 − (x−2)²/18 + (x−2)³/81 − …

**Computing a number: sin 31°.** The section's closing use is numerical. Maclaurin about 0° would need many terms for 31°, so centre at 30°, where sin 30° = 1/2 and cos 30° = √3/2 are known exactly. The step is h = 1° = π/180 ≈ 0.01745 radians, and sin(30° + h) = sin 30° + h cos 30° − (h²/2) sin 30° + … gives 0.5 + 0.01745 × 0.8660 − 0.000076 ≈ **0.5150** — the book's value (ch-pp.78–81). Three terms, because the centre was chosen well.

## Say it to your companion
Explain where each piece of the template f(0) + xf′(0) + x²f″(0)/2! + … comes from, and why the factorials grow in the denominators. Then explain, with sin 31°, why a Taylor centre near the target beats the Maclaurin centre at 0. Your companion checks both explanations against the lesson.

## Do It Yourself
1. Write the Maclaurin series of eˣ and use four terms to estimate e² (x = 2); check against a calculator and say why more terms are needed at x = 2 than at x = 1.
2. Write the Maclaurin series of sin x and estimate sin(0.5) with two non-zero terms (Pakistan, Class 12, §2.17, ch-pp.74–78).
3. Expand 1/(1+x) to four terms and use it at x = 0.1; then say why the same series cannot be used at x = 2.
4. Write (1+x)^(1/2) to three terms from the binomial series.
5. Rebuild ln(1+x) about x = 2 to three terms, and use sin 31° ≈ 0.5150's method to estimate sin 46° about 45° (Pakistan, Class 12, §2.17, ch-pp.78–81).
