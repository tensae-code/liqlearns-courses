# The Four Means and Their Inequalities

## You do it first

Here are two numbers: 2 and 8. What is "the average" of them?

You probably said 5 — add and halve. Hold on to that answer, then compute three more: the square root of their product; the product doubled and divided by their sum; and the square root of the average of their squares. You get 4, 3.2 and about 5.83. Four different "averages" of the same two numbers — and they always, always come out in the same order. This lesson is that order, and why it never breaks.

## The four means

For positive numbers, North Macedonia's Grade 12 Algebra book (§3.4, "Средни величини" — Mean values) defines four means side by side. For two numbers a and b:

- **Arithmetic mean (AM):** (a + b)/2 — add and share equally.
- **Geometric mean (GM):** √(ab) — the side of a square with the same area as the a-by-b rectangle.
- **Harmonic mean (HM):** 2ab/(a + b) — flip both numbers to their reciprocals, take the arithmetic mean of the flips, and flip back.
- **Quadratic mean (QM):** √((a² + b²)/2) — the root-mean-square: square, average, take the root.

For n numbers the same ideas stretch: AM = (x₁ + … + xₙ)/n, GM = (x₁·…·xₙ)^(1/n), HM = n/(1/x₁ + … + 1/xₙ), QM = √((x₁² + … + xₙ²)/n). (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §3.4, printed p. 58.)

## One pair, four answers

For 2 and 8:

- AM = (2 + 8)/2 = **5**
- GM = √(2·8) = √16 = **4**
- HM = 2·2·8/(2 + 8) = **3.2**
- QM = √((2² + 8²)/2) = √34 ≈ **5.83**

Lined up: 3.2 ≤ 4 ≤ 5 ≤ 5.83, that is HM ≤ GM ≤ AM ≤ QM. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §3.4, printed p. 58.)

## The chain

That order is a theorem, not a coincidence of the numbers 2 and 8. For **every** set of positive numbers,

**QM ≥ AM ≥ GM ≥ HM,**

and North Macedonia's book proves the chain, proving **QM ≥ AM first**: fix the sum of the numbers; then the sum of their squares — the thing QM measures — is smallest when the numbers are all equal, and grows as they spread. So QM sits at the top of the chain whenever the numbers differ at all. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §3.4, printed p. 58.)

## The equality case

All four means agree in exactly one situation: **when all the numbers are equal.** For 3 and 3: AM = 3, GM = √9 = 3, HM = 3, QM = √9 = 3. The chain collapses to a point. Read backwards, this is a measuring instrument: the wider the chain opens, the more spread out the numbers are. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §3.4, printed p. 58.)

## Reading the chain as a tool

The middle link, AM ≥ GM, is the hardest-working inequality in the chain. It says: **for a fixed sum, the product is greatest when the numbers are equal.** Two numbers with sum 10 have product at most 25 — reached only by 5 and 5. Every other link turns one kind of bound into another: know a set's harmonic mean and you already know its geometric mean is no smaller, and so on up the chain. (North Macedonia, *АЛГЕБРА ЗА ТРЕТА ГОДИНА* (Grade 12, elective), §3.4, printed p. 58.)

## Do it yourself

1. Compute all four means of 1 and 9, and write them in chain order. (QM = √41 ≈ 6.40, AM = 5, GM = 3, HM = 1.8.)
2. A classmate claims that for the numbers 4 and 16 the geometric mean is bigger than the arithmetic mean. Settle it by computing both. (GM = 8, AM = 10 — the claim breaks the chain.)
3. For which pair (a, b) with a ≠ b do all four means coincide? Trick question — say why no such pair exists.
4. Two positive numbers have sum 20. What is the largest their product can be, and which link of the chain gives it? (100, by AM ≥ GM, at 10 and 10.)
5. Compute the four means of 1, 3, 9 and check the chain holds. (QM ≈ 5.51, AM ≈ 4.33, GM = 3, HM ≈ 2.08.)
