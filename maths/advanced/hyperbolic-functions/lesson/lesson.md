# Hyperbolic Functions — the lesson

Course: Maths · Stage: Stage 12 — Advanced Mathematics · Lesson: Hyperbolic Functions
Built from: Laos, Grade 12 student book — Pakistan, Mathematics Class 12

## Do it first
Take a calculator. Work out e¹ ≈ 2.718 and e⁻¹ ≈ 0.368. Add them and halve the answer: about 1.543. Subtract them and halve: about 1.175. Now square both numbers and subtract the squares: 1.543² − 1.175² ≈ 1. Two new functions are hiding inside eˣ, and they already obey a perfect identity. Laos's Grade 12 book gives them a whole chapter (Ch.7, p.207), and Pakistan's Class 12 book lists them among its types of functions (Ch.1, ch-pp.10–11). This lesson names them.

## Then the explanation
**The six functions, built from eˣ.** The **hyperbolic sine** is sinh x = (eˣ − e⁻ˣ)/2 and the **hyperbolic cosine** is cosh x = (eˣ + e⁻ˣ)/2. Their ratio is the **hyperbolic tangent**: tanh x = sinh x / cosh x = (eˣ − e⁻ˣ)/(eˣ + e⁻ˣ). The other three are reciprocals, named like the trigonometric ones: coth x = 1/tanh x, sech x = 1/cosh x, cosech x = 1/sinh x. Laos's book opens the chapter with the properties of these functions (Ch.7, L19, printed p.207), and Pakistan's book defines the hyperbolic and inverse hyperbolic functions by their log forms in its functions chapter (Ch.1, ch-pp.10–11). At x = 0: sinh 0 = 0, cosh 0 = 1, tanh 0 = 0 — because e⁰ = 1 makes the difference 0 and the sum 2.

**Graphs, domains and ranges.** Laos's book graphs the functions next (L20, printed p.210) and then states each domain and range (L21, printed p.217). Sinh is an odd function — sinh(−x) = −sinh x — passing through the origin and climbing both ways, domain all x, range all y. Cosh is even — cosh(−x) = cosh x — shaped like a hanging chain, with its lowest point (0, 1): domain all x, range y ≥ 1. Cosh can never fall below 1, because it is half the sum of two positive numbers whose product is 1. Tanh is odd, trapped between the horizontal lines y = −1 and y = 1, which it approaches but never reaches: domain all x, range −1 < y < 1. Sech shares cosh's ceiling: 0 < sech x ≤ 1. Cosech and coth are undefined at x = 0, where sinh x = 0.

**The identities.** The master identity is cosh²x − sinh²x = 1 — you met it in Do it first, and it falls straight out of the definitions: the squares subtract to (e²ˣ + 2 + e⁻²ˣ)/4 − (e²ˣ − 2 + e⁻²ˣ)/4 = 1. Divide it by cosh²x and you get 1 − tanh²x = sech²x; divide by sinh²x and you get coth²x − 1 = cosech²x. Laos's book collects the properties and the summary of the chapter in L19 and L22 (printed pp.207, 221), and its final page carries the hyperbolic and inverse-hyperbolic formulas in the book's integral tables (printed p.300). The addition shapes mirror the trigonometric ones with one sign change to watch: sinh(x + y) = sinh x cosh y + cosh x sinh y, but cosh(x + y) = cosh x cosh y + sinh x sinh y — a plus where cos has a minus.

**The derivatives.** Because the functions are built from eˣ, their derivatives are short: d/dx sinh x = cosh x and d/dx cosh x = sinh x — the pair swap, with no minus sign anywhere (unlike sin and cos). Then d/dx tanh x = sech²x and d/dx coth x = −cosech²x. The last two carry a minus, and here one printed error must be taught corrected, never as fact: Pakistan's Class 12 summary on Ch.2 ch-p.62 prints d/dx cosech x = coth x cosech x and d/dx sech x = tanh x sech x, dropping both minus signs; the correct rules, which the quotient rule gives at once, are **d/dx cosech x = −coth x cosech x** and **d/dx sech x = −sech x tanh x**. Pakistan's chapter teaches the hyperbolic and inverse hyperbolic derivatives across ch-pp.61–66.

Tip — from us, not from the books. Remember the pair this way: sinh and cosh swap under differentiation and never pick up a minus; the two reciprocal functions sech and cosech are the ones that carry the minus — if your derivative of sech x has no minus in it, you have copied the book's misprint, not the mathematics.

**The inverse hyperbolic functions.** Each hyperbolic function has an inverse, taken on the part where it is one-to-one. Laos's book teaches the inverses of the hyperbolic functions as their own lesson (Ch.8, L25, printed p.243), straight after the inverses of the trigonometric functions. Sinh is one-to-one everywhere, so sinh⁻¹ takes every real x. Cosh is one-to-one only for x ≥ 0, so cosh⁻¹ takes only x ≥ 1. Tanh is one-to-one with range −1 < y < 1, so tanh⁻¹ takes only −1 < x < 1. Because the functions come from eˣ, the inverses come out as logarithms — Pakistan's book files them by these log forms (Ch.1, ch-pp.10–11): sinh⁻¹x = ln(x + √(x² + 1)); cosh⁻¹x = ln(x + √(x² − 1)) for x ≥ 1; tanh⁻¹x = ½ ln((1 + x)/(1 − x)) for −1 < x < 1. Their derivatives close the lesson: d/dx sinh⁻¹x = 1/√(x² + 1); d/dx cosh⁻¹x = 1/√(x² − 1); d/dx tanh⁻¹x = 1/(1 − x²) (Pakistan, Class 12, Ch.2, ch-pp.61–66).

## Say it to your companion
Explain, using eˣ and e⁻ˣ, why cosh x can never be less than 1 and why sinh is odd but cosh is even. Then state all six derivative rules aloud — and say the two corrected ones, for sech and cosech, last and loudest, with their minus signs. Your companion checks you against the lesson.

## Do It Yourself
1. Evaluate sinh(ln 2) and cosh(ln 2) exactly, using e^(ln 2) = 2 and e^(−ln 2) = 1/2.
2. Prove cosh²x − sinh²x = 1 from the definitions, then derive 1 − tanh²x = sech²x by dividing by cosh²x.
3. Sketch y = cosh x and y = tanh x on one page and write each domain and range under its graph (Laos, Grade 12, L20–L21, pp.210, 217).
4. Differentiate: sinh(3x), cosh²x, tanh x + sech x, cosech x — using the corrected rule for the last two.
5. Write sinh⁻¹3 in log form and evaluate it approximately; then differentiate tanh⁻¹x and sinh⁻¹x.
