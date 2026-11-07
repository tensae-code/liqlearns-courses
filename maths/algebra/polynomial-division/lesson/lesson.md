# Polynomial Division — the lesson

Course: Maths · Stage: Stage 6 — Algebra · Lesson: Polynomial Division
Built from: Ethiopia, Grade 10 student book (Unit 2) — Indonesia, Grade 11 Tingkat Lanjut Revisi (Bab 2) — Pakistan, Class 11 Mathematics (Unit 9) — Yemen, Grade 10 Part 1 (Unit 4) — Bangladesh, Class 9 (Ch. 4) — Laos, Grade 9 and Grade 11 — Nicaragua, Grade 8 and Grade 10 — Iran, Grade 9 — Cambodia, Grade 10 Part 1 — Egypt, Grade 7 — Greece, Grade 9 — Kuwait, Grade 11 Term 1 exercise workbook only (workbook evidence)

## Do it first
Divide 47 by 5. You get quotient 9, remainder 2, and the check 5 × 9 + 2 = 47. Hold that shape in your head: **dividend = divisor × quotient + remainder**. Now the question of this lesson: can a polynomial be divided the same way? Divide x³ + 2x² − 5x − 6 by (x + 1) any way you can before reading on — the answer is x² + x − 6 with remainder 0, and by the end of the lesson you will be able to produce it two different ways and check it the 47-way.

## Then the explanation
**The division identity.** For polynomials, exactly as for numbers: **p(x) = d(x)q(x) + R(x)**, where the remainder R(x) has smaller degree than the divisor. Bangladesh's Class 9 book states the division in this general form (§8.4, pp.96–99), Indonesia's Grade 11 Tingkat Lanjut Revisi book builds the whole topic on the division algorithm (Bab 2, pp.70–88), and Ethiopia's Grade 10 book states the polynomial division theorem inside its polynomial unit (Unit 2, pp.67–120).

**Long division.** Work exactly as with numbers, one power at a time: divide the leading terms, multiply the divisor by what you got, subtract, bring down the next term. Divide x³ + 2x² − 5x − 6 by (x + 1): x³ ÷ x = x²; multiply (x + 1)x² = x³ + x², subtract, leaving x² − 5x; x² ÷ x = x; multiply (x + 1)x = x² + x, subtract, leaving −6x − 6; −6x ÷ x = −6; multiply (x + 1)(−6) = −6x − 6, subtract, leaving 0. Quotient x² + x − 6, remainder 0. Cambodia's Grade 10 book teaches polynomial division as its own section (§2.1, pp.78–90), Egypt's Grade 7 book drills the long-division layout including missing powers (§2-5, printed pp.43–47), Greece's Grade 9 algebra chapter carries division of polynomials in its expressions chapter (Ch. 1, pp.12–84), and Nicaragua's Grade 8 book works up from monomial ÷ monomial and binomial ÷ monomial to trinomial ÷ binomial.

**Synthetic division — the short road for (x − a).** When the divisor is (x − a), the long layout compresses into a table of coefficients — Horner's method in Indonesia's book (Bab 2, pp.70–88), taught in Laos's Grade 9 book (Ch. 1, L3, p.10) and again in its Grade 11 book (Ch. 1, L3–L5, pp.10, 15, 19), in Pakistan's Class 11 book (Unit 9, pp.169–176), and used in Nicaragua's Grade 10 book to divide x² + 5x − 6 by (x + 6). Divide x³ − 4x² + x + 6 by (x − 2): write the coefficients 1, −4, 1, 6 and the number 2. Bring down 1; 1 × 2 = 2, add to −4 giving −2; −2 × 2 = −4, add to 1 giving −3; −3 × 2 = −6, add to 6 giving 0. The bottom row 1, −2, −3, 0 reads: quotient x² − 2x − 3, remainder 0. Mind the sign: the table takes a from (x − a), so dividing by (x + 2) uses −2. Iran's Grade 9 book meets the same division inside rational expressions (p.126).

**The remainder theorem.** Put x = a in the identity: p(a) = (a − a)q(a) + R, so **the remainder on dividing p(x) by (x − a) is exactly p(a)**. No division needed. Yemen's Grade 10 book works it on (x² − 5x + 9) ÷ (x − 3): quotient x − 2, remainder 3 — and p(3) = 9 − 15 + 9 = 3, the same 3 (§4-3, p.88). Bangladesh's book states and proves the theorem (§9, pp.99–101) and extends it: for the divisor (ax + b) the remainder is p(−b/a) — its worked example (3x³ − 2x + 1) ÷ (2x + 1) has remainder p(−1/2) = 13/8. Ethiopia's and Pakistan's books prove the theorem, not just state it (Ethiopia, Unit 2; Pakistan, Class 11, Unit 9, pp.169–176).

**The factor theorem.** If the remainder is 0, the divisor divides exactly — that is, **(x − a) is a factor of p(x) exactly when p(a) = 0**. Bangladesh states it in §10.1 (pp.101–107), Yemen uses the remainder and factor theorems together and passes to the zeros of the polynomial (§4-4, p.92). Use it to open a cubic: for p(x) = x³ − 2x² − x + 2, test easy values: p(1) = 1 − 2 − 1 + 2 = 0, so (x − 1) is a factor. Divide it out: quotient x² − x − 2 = (x − 2)(x + 1). So p(x) = (x − 1)(x − 2)(x + 1), completely factorised — the same complete-factorisation finish Pakistan's Class 11 book reaches by synthetic division (Unit 9). Kuwait's Grade 11 Term 1 exercise workbook practises this territory in its polynomials unit (Unit 3, pp.43–48) — workbook evidence only: exercises with no teaching text, since the Kuwaiti student book for that term is not in hand.

**Rational zeros — where to look.** Testing every number would never end, so the books narrow the search: any rational zero, written p/q in lowest terms, has p dividing the constant term and q dividing the leading coefficient. Indonesia's book names this the rational-zero theorem (Bab 2), and Ethiopia's book teaches the same p/q candidates inside Unit 2. For x³ − 2x² − x + 2 the candidates are ±1, ±2 — and indeed all three zeros, 1, 2 and −1, sit in that short list.

> Tip — from us, not from the books: always finish a division with the check — multiply divisor × quotient and add the remainder. It takes one minute and it catches nearly every slip the other methods let through.

## Say it to your companion
Say the two theorems whole: "The remainder when p(x) is divided by (x − a) is p(a)." " (x − a) is a factor of p(x) exactly when p(a) = 0." Then explain, in your own words, why the second follows from the first. Trade divisions: your companion gives a cubic and a value a; you give the remainder by p(a) alone, then prove it by synthetic division.

## Do It Yourself
1. Divide x³ + 3x² − 4 by (x + 2) by long division, and check with the identity.
2. Divide 2x³ − 5x² + 3x + 1 by (x − 1) by synthetic division.
3. Without dividing, find the remainder when x³ + 2x² − 5x − 6 is divided by (x − 2).
4. Show that (x + 3) is a factor of x³ + 4x² + x − 6... first by p(−3), then divide and factorise the polynomial completely.
5. List all possible rational zeros of 2x³ − 5x² − 4x + 3, and find which of them are actual zeros.
