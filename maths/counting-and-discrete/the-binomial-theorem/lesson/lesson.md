# The Binomial Theorem — the lesson

Course: Maths · Unit: Unit 14 — Counting and Discrete Mathematics · Lesson: The Binomial Theorem
Built from: Pakistan, Class 11 Mathematics (PECTAA) — Indonesia, Grade 12 Revisi; Grade 8 K13 — Vietnam, Grade 10 Volume 2; Grade 10 study book — Yemen, Grade 12 Science — Kuwait, Grade 11 Term 2; Grade 11 Statistics Term 2 — Laos, Grade 11 — Cambodia, Grade 10 — Egypt, Pure Mathematics Grade 12 — Ethiopia, Grade 11 — Armenia, Grade 12 teacher's guide (teacher evidence) — Iraq, Grade 11 Scientific; Grade 12 Literary — Kazakhstan, Grade 9 Algebra (four books)

## Do it first
Multiply out (a+b)² with your own hands: you get a² + 2ab + b².
Now multiply (a+b)³ = (a+b)(a² + 2ab + b²) the long way. You get
a³ + 3a²b + 3ab² + b³. Write down only the coefficients, in a row:

for power 2: 1, 2, 1
for power 3: 1, 3, 3, 1

Each row starts and ends in 1, and — look — every middle number is
the sum of the two numbers above it in the row before (3 = 1 + 2).
You have just found the pattern this whole lesson stands on.

## Then the explanation

## Sub lesson 1 — Pascal's Triangle

**Pascal's triangle.** Stack the coefficient rows, centred:

        1
      1   1
    1   2   1
  1   3   3   1
1   4   6   4   1

Every entry is the sum of the two entries above it. Indonesia's
Grade 8 K13 book teaches this triangle as a number pattern in its
opening chapter (Bab 1, pp.1–40) — you build it by addition alone,
no algebra needed. Indonesia's Grade 12 Revisi book then prints
the same triangle in the body of its binomial lesson
(pp.113–118), where it does its real work. One source is never
used for this triangle: Indonesia's Grade 12 Merdeka (2022) book
was checked and Pascal's triangle is NOT FOUND there, so it is
cited nowhere in this lesson — the triangle rests on the Revisi
and K13 books only.

## Sub lesson 2 — The Theorem and Full Expansions

**The binomial theorem.** Row n of the triangle gives the
coefficients of (a+b)ⁿ, because each coefficient is a combination
number: the coefficient of aⁿ⁻ᵏbᵏ is C(n,k) — the number of ways
of choosing which k of the n brackets give a b. In symbols, the
form Yemen's Grade 12 Science book prints (2-4, p.65):

(a+b)ⁿ = Σ C(n,k) aⁿ⁻ᵏ bᵏ,  k = 0, 1, …, n

Pakistan's Class 11 book proves this theorem by induction
(Unit 8, pp.151–168). Vietnam's Grade 10 Volume 2 book teaches the
same expansion (Bài 25, p.72), and its Grade 10 study book proves
Newton's binomial by induction (Bài 4, p.32). Kuwait's Grade 11
Term 2 book carries the expansion in its counting unit
(11-2, pp.162–166), as does its Grade 11 Statistics Term 2 book
(5-2, pp.63–67); Laos's Grade 11 book carries it in its counting
chapter (Ch.6 L28, p.180); Egypt's Pure Grade 12 book opens its
first unit with it; Ethiopia's Grade 11 book teaches it at §8.4.
Armenia's Grade 12 teacher's guide plans "Newton's binomial and
Pascal's triangle" as Chapter 2 §4 — teacher evidence only, since
Armenia's Grade 12 student book is not held.

Tip — from us, not from the books. In every term of the expansion the two powers add to n. If your term's powers add to anything else, the term is wrong before you even check its coefficient.

**Reading an expansion.** For (a+b)⁴ the triangle row is
1, 4, 6, 4, 1, a's power falls 4, 3, 2, 1, 0 and b's power climbs
0, 1, 2, 3, 4:

(a+b)⁴ = a⁴ + 4a³b + 6a²b² + 4ab³ + b⁴

For (a−b)ⁿ, write (a + (−b))ⁿ: the b-powers bring their minus
signs with them, so the signs alternate +, −, +, −, … Cambodia's
Grade 10 book works the cleanest special case, (1+a)ⁿ, where the
triangle row can be read off directly.

**The same theorem in Iraq and Kazakhstan.** Iraq teaches the
theorem twice. Its Grade 11 Scientific book closes its counting
chapter with it ([8-6], pp.211–215): (a+b)ⁿ = Σ C(n,r) aⁿ⁻ʳ bʳ,
n+1 terms, and the general term written as
P_r = C(n,r−1) · aⁿ⁻ʳ⁺¹ · bʳ⁻¹ — the r-th term, counted from
r = 1. Its favourite check is a number, not a letter:
(101)³ = (1 + 100)³ = 1,030,301. The Grade 12 Literary book
teaches it again from the expansions of (x+y)², (x+y)³ and
(x+y)⁴ (1-5, p.24): the 5th term of (x+y)⁸ carries the
coefficient C(8,4) = 70, (3a+b)⁴ expands to
81a⁴ + 108a³b + 54a²b² + 12ab³ + b⁴, and the term free of x in
(x² − 1/x)¹⁵ is the 11th term, with value 3003 (pp.26–29).
Kazakhstan's four Grade 9 algebra books each end their
combinatorics chapter with Newton's binomial: Pascal's triangle
built from the expansions of (a±b)⁰ to (a±b)³, with its history
through Omar Khayyam (Yelemessov, §2.3, pp.64–70); the Pascal
rule Cₙ₊₁ᵏ⁺¹ = Cₙᵏ + Cₙᵏ⁺¹ proved by counting lattice paths,
and Σ C(n,k) = 2ⁿ (Shynybekov, §2.6, p.54); seven listed
properties of an expansion, the general term Tₖ₊₁ among them
(Abylkasymova, §11, p.92); and a Pascal table carried to n = 9,
used for approximate computation — (1.04)⁵ and (0.98)⁵ estimated
from the expansion (Soltan, §11, p.82).

## Sub lesson 3 — The General Term and the Binomial Series

**The general term.** You often need one term, not all of them.
The (k+1)-th term of (a+b)ⁿ is C(n,k) aⁿ⁻ᵏ bᵏ. To find, say, the
term in x³ inside (2 + x)⁵, set the b-power to 3: the term is
C(5,3) · 2² · x³ = 10 · 4 · x³ = 40x³. Pakistan's Class 11 book
organises its binomial work around this general term, including
middle terms and equal coefficients (Unit 8, pp.151–168).

**Closing part: the binomial series for negative and fractional
powers.** The theorem above is for a whole-number power, and the
expansion stops after n+1 terms. Pakistan's Class 11 book closes
the topic by letting the power be any number — negative or
fractional (Unit 8, pp.158–159). Then (1+x)ⁿ does not stop; it
runs on as an infinite series:

(1+x)ⁿ = 1 + nx + n(n−1)/2! · x² + n(n−1)(n−2)/3! · x³ + …

and the series is valid only for |x| < 1. Two working forms:
(1+x)^(−1) = 1 − x + x² − x³ + … and
(1+x)^(1/2) = 1 + x/2 − x²/8 + x³/16 − …
The first few terms give an approximation — that is what the
series is for — and the smaller |x| is, the fewer terms you need.

## Say it to your companion
Say the theorem to your companion in plain words: "To expand
(a+b) to a whole power, the coefficients are the combination
numbers; a's power falls from n to 0 while b's power climbs from
0 to n." Then your companion names a power — 2, 3, 4 or 5 — and
you recite its triangle row from memory and write the first and
last terms of the expansion.

## Do It Yourself
1. Build Pascal's triangle to row 6 and circle row 5.
2. Expand (x + 2)³ fully, checking coefficients against the
   triangle.
3. Expand (a − b)⁴ and mark where each minus sign came from.
4. Find the coefficient of x² in (1 + 3x)⁵ using the general term.
5. Find the middle term of (a+b)⁶.
6. Use the series to write (1+x)^(−2) up to the x³ term, and
   state the values of x for which the series is valid.
7. Estimate √1.04 with (1+x)^(1/2) ≈ 1 + x/2 − x²/8, x = 0.04,
   and check by squaring your answer.
