<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->
# Lesson plan — The Four Means and Their Inequalities

**One thing:** there are four different "averages" of a set of positive numbers — the quadratic mean (root-mean-square), the arithmetic mean, the geometric mean and the harmonic mean — and they always line up in one order: quadratic ≥ arithmetic ≥ geometric ≥ harmonic, with equality only when all the numbers are equal.

**Unit:** Algebra (Unit 6). **Level 156** (North Macedonia merge, 2026-11-07).

**Why this lesson exists:** North Macedonia's Grade 12 Algebra elective (*АЛГЕБРА ЗА ТРЕТА ГОДИНА*, §3.4 "Средни величини" — Mean values, printed p. 58) defines the four means of positive numbers side by side and proves the inequalities between them, opening with the proof of QM ≥ AM. No other read book in the library does this: the averages in the statistics lessons are data averages (one mean, for data handling), and the inequalities lesson carries named single inequalities such as Cauchy–Schwarz but no means and no chain. So under the everything-goes-in ruling (2026-11-06) the four means get their own lesson. It stands alone: the inequalities lesson is a soft hint before it, never a gate.

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **The Four Means of a Pair** — the four definitions — arithmetic, geometric, harmonic, quadratic (root-mean-square) — computed for a pair of numbers; the n-number forms are stated here too. (Was depth Layer 1; the three-or-more-numbers work of old depth Layer 4 is stated here, in the n-number forms.)
2. **The Chain of the Four Means** — the order QM ≥ AM ≥ GM ≥ HM: placing a computed set of four means in it, and spotting a claimed order that breaks the chain. (Was depth Layer 2.)
3. **The Equality Case** — when the four means are all equal, verified on an equal set, and how the chain opens as a set spreads out. (Was depth Layer 3.)
4. **Reading the Chain as a Tool** — turning the chain into a bound: the greatest product for a fixed sum (AM ≥ GM), and quick estimates that replace a hard mean by an easier one on the correct side. (Was depth Layer 5.)

Old depth Layer 4 (three or more numbers) has no separate text section: the n-number forms are stated inside Sub lesson 1, so its questions are marked Sub lesson 1 and its pass mark is carried in Sub lesson 1's depth section.

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## The climb

1. **Four ways to average.** For positive numbers x₁, …, xₙ: the arithmetic mean (x₁ + … + xₙ)/n; the geometric mean (x₁·…·xₙ)^(1/n); the harmonic mean n/(1/x₁ + … + 1/xₙ); the quadratic mean √((x₁² + … + xₙ²)/n) — the root-mean-square. For two numbers a and b these are (a + b)/2, √(ab), 2ab/(a + b) and √((a² + b²)/2).
2. **One set, four answers.** For 2 and 8: QM = √34 ≈ 5.83, AM = 5, GM = 4, HM = 3.2. The four "averages" of the same two numbers spread out — and they spread in a fixed order.
3. **The chain.** For every set of positive numbers, QM ≥ AM ≥ GM ≥ HM. North Macedonia's book proves the chain, and proves QM ≥ AM first — with the sum fixed, the sum of squares is smallest when the numbers are equal, which is the statement wearing work clothes.
4. **Equality.** All four means agree exactly when all the numbers are equal: for 3, 3, 3 every mean is 3. The more the numbers spread, the wider the chain opens.
5. **Reading the chain both ways.** AM ≥ GM says a fixed sum caps the product (the product is greatest when the numbers are equal); GM ≥ HM and the rest of the chain turn one bound into another whenever a problem hands you the "wrong" mean.

## Add-on slots

- slot-means-0 (IMAGE): the numbers 2 and 8 on a number line with their four means marked in four colours — HM 3.2, GM 4, AM 5, QM ≈ 5.83 — in chain order. What the student does: reads the chain off the line and says which mean sits nearest to 8 and why it must be the quadratic one.
- slot-means-1 (GIF, 1–2 s): two numbers a and b sliding towards each other until they meet at their arithmetic mean, while the four mean-markers slide together and merge into one point. What the student does: watches GM, HM and QM all close in on AM and says what the picture proves about the equality case.
- slot-means-2 (IMAGE): a rectangle of fixed perimeter split two ways — long and thin, then square — with the areas marked. What the student does: connects the bigger area of the square to AM ≥ GM (fixed sum, greatest product at equality).
