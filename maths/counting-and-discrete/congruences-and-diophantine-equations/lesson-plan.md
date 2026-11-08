<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Congruences and Diophantine equations

**Course:** Maths · **Unit:** Unit 14 — Counting and Discrete Mathematics · **Lesson:** Congruences and Diophantine equations
**Place in the curriculum:** Level 109 of 136, Unit 14 — Counting and Discrete Mathematics (maths/CURRICULUM.md).
**The one thing this lesson teaches:** modular arithmetic and congruences — working with remainders; Euclid's algorithm for the greatest common divisor; and solving linear Diophantine equations ax + by = c in whole numbers.
**This lesson's own level:** it stands on the division-with-remainder work of the numbers lessons — the learner can already divide and name a remainder. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the
exact places marked below, the lesson page carries an add-on — an
image, a GIF, a video, an audio. Every slot is written as **"a picture
of …" in words, plus one little line saying what the student does
with it**. The words carry the picture while the course is built and
while the AI learns from the books; on the website the real add-on is
dropped into that slot and the little explanation stays as the
student's guide. Images follow the picture rule (a real photograph,
or real art, with its source). GIFs come first where a thing must be
shown changing.

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **Remainders and a Modulus** — remainders, the modulus, simplest form, and adding, subtracting and multiplying inside a modulus. (Was depth Level 1.)
2. **Congruences, Tests and Euclid's Algorithm** — congruences and their rules (with the corrected cancellation rule), divisibility tests and the calendar, and Euclid's algorithm for the gcd. (Was depth Level 2.)
3. **Linear Congruences and Diophantine Equations** — solving linear congruences, and Diophantine equations ax + by = c: when solutions exist, the general solution, and the non-negative solutions. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: the factors-and-multiples work (gcd and lcm) in the numbers stage — this lesson's Euclid's algorithm is its fast engine. Recommended, never forced.
- Recommended first: Graph theory (Level 108, same stage) — the stage's other discrete topic. Recommended, never forced.

## What the learner can do when it ends
1. Reduce a number to its simplest form in a given modulus and do addition, subtraction and multiplication in a modulus, the way Sierra Leone's SSS 1 handbook teaches it (L22–L23, pp.62–67).
2. Use congruences a ≡ b (mod m) and their arithmetic rules — including the careful cancellation rule, dividing through by gcd(c, m) — the way Iran's Discrete Mathematics book states them (pp.18–25).
3. Use a congruence to test divisibility (the digit-sum rule mod 9) and to work out the day of the week, as Iran's book works them (pp.23–24).
4. Find a gcd by Euclid's algorithm, as Kazakhstan's Grade 8 book teaches it in its starred (optional) additional-materials chapter (§§6.1–6.5, pp.160–177; filed as optional).
5. Solve a linear congruence and a linear Diophantine equation ax + by = c, giving the general integer solution and picking out the non-negative solutions, the way Iran's book solves them through congruences (pp.25–29) and Greece's Grade 11 book teaches the linear Diophantine equation (Ch.4, pp.135–184).
6. Solve a whole-number problem by setting up a Diophantine equation, as Kazakhstan's Grade 6 book does with 30 matchsticks split into triangles and squares (§10.1, p.178).

## What you need
Paper and a pencil. A calendar page helps for the day-of-the-week work.

## The run of the lesson (in order)
1. **Do it first** — the learner works out what day of the week it is 100 days from today, using only remainders (lesson/lesson.md).
2. **The explanation** — remainders and moduli; congruences and their rules; divisibility tests and the calendar; Euclid's algorithm; linear congruences; Diophantine equations (lesson/lesson.md).
   - ADD GIF at the clock part: a picture of a clock hand sweeping past 12 again and again, the count resetting each round — the student says the hour shown after 25 sweeps of one hour each.
   - ADD IMAGE at the Euclid part: a picture of the division steps for gcd(680, 612) stacked as shrinking rows → the student follows each remainder down to the last non-zero one, 68.
   - ADD IMAGE at the Diophantine part: a picture of 30 matchsticks grouped into triangles and squares → the student counts why only two groupings use all 30.
3. **Say it to your companion** — explain why 7 ≡ 2 (mod 5) and why cancelling in a congruence needs care (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — congruences in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — five remainder, Euclid and Diophantine jobs in the books' own shapes (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of a clock hand sweeping and resetting → the student reads hours modulo 12.
- IMAGE — a picture of Euclid's division steps for 680 and 612 → the student follows the remainders to 68.
- IMAGE — a picture of 30 matchsticks in triangles and squares → the student finds the two whole-number groupings.
- VIDEO — the video-script filmed (made later) → the student reduces numbers along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Reduces a negative number wrong → Sierra Leone's way: add the modulus until the answer sits between 0 and the modulus (L22, p.62).
- Cancels a factor in a congruence freely → Iran's warning: plain cancellation can fail; divide through by gcd(c, m) as well as by c (p.22, stated without proof in the book, as filed).
- Diophantine equation "has no answer" → first check gcd(a, b) divides c; if it does not, there truly is no whole-number answer — that check IS the answer (Greece, Ch.4).
- Finds one solution but not all → step x by b/gcd and y by −a/gcd to walk through every solution (Iran, pp.26–29).
- This lesson's next door: Latin squares (Level 110, same stage).

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Iran, Discrete Mathematics, Grade 12; Greece, Mathematics Grade 11 orientation book, W7; Sierra Leone, SSS 1 Pupils' Handbook, Term 1; Kazakhstan, Grade 6 and Grade 8/9 books — the Grade 8 Euclid's-algorithm row is starred OPTIONAL in its book, as filed). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
