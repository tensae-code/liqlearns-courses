<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — The Binomial Theorem

**Course:** Maths · **Unit:** Unit 14 — Counting and Discrete Mathematics · **Lesson:** The Binomial Theorem
**Place in the curriculum:** Level 106 of 136, Unit 14 — Counting and Discrete Mathematics (maths/CURRICULUM.md).
**The one thing this lesson teaches:** expanding (a+b)ⁿ without multiplying it out — Pascal's triangle, the binomial theorem with combination coefficients, the general term, and, as the closing part, the binomial series for negative and fractional powers.
**This lesson's own level:** it stands on Counting Principles (Level 105) — the learner can already compute ⁿCᵣ. It needs nothing else.

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

1. **Pascal's Triangle** — building Pascal's triangle by addition, reading off the row for a given n, and how each entry is made from the two above it. (Was depth Level 1.)
2. **The Theorem and Full Expansions** — the binomial theorem and full expansions, the signs in (a−b)ⁿ, coefficients matched to combination values, and the same theorem in Iraq's and Kazakhstan's books. (Was depth Level 2.)
3. **The General Term and the Binomial Series** — the general term, for extracting a named term or coefficient without a full expansion, and the binomial series for negative and fractional powers, valid for |x| < 1. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Counting Principles (Level 105) — the coefficients of the expansion are the combination numbers ⁿCᵣ. Recommended, never forced.
- Recommended first: the indices (powers) work of the earlier stages — the expansion is built from powers of a and b. Recommended, never forced.

## What the learner can do when it ends
1. Build Pascal's triangle row by row, each entry the sum of the two above it, the way Indonesia's Grade 8 K13 book teaches the triangle as a number pattern (Bab 1, pp.1–40) and Indonesia's Grade 12 Revisi book prints it in the body of its binomial lesson (pp.113–118).
2. State and use the binomial theorem (a+b)ⁿ = Σ C(n,k) aⁿ⁻ᵏ bᵏ, the form Yemen's Grade 12 Science book prints (2-4, p.65).
3. Expand a binomial fully for small n and check the coefficients against Pascal's triangle, the way Vietnam's Grade 10 Volume 2 book teaches the expansion (Bài 25, p.72).
4. Find one named term of an expansion — the general term — without expanding everything, the way Pakistan's Class 11 book organises the theorem after proving it by induction (Unit 8, pp.151–168).
5. Use the middle-term and coefficient facts for (1+x)ⁿ, the case Cambodia's Grade 10 book works with (1+a)ⁿ.
6. Expand (1+x)ⁿ for a negative or fractional n as an infinite series, state that it holds for |x| < 1, and use its first terms as an approximation — the closing part, from Pakistan's Class 11 book (Unit 8, pp.158–159).
7. Find the term free of x (the constant term) in an expansion such as (x² − 1/x)¹⁵, and use a whole-power expansion to compute and estimate numbers — (101)³ = 1,030,301 exactly, (1.04)⁵ approximately — the way Iraq's Grade 12 Literary book works the free-of-x term (Ch.1, pp.26–29), Iraq's Grade 11 Scientific book checks (101)³ ([8-6], pp.211–215), and Kazakhstan's Soltan Grade 9 book estimates from the expansion (§11, p.82).

## What you need
Paper and a pencil. A calculator for the closing approximations.

## The run of the lesson (in order)
1. **Do it first** — the learner multiplies out (a+b)² and (a+b)³ by hand and writes the coefficients in a row, before any triangle is shown (lesson/lesson.md).
2. **The explanation** — Pascal's triangle; the theorem; the general term; special cases; the closing binomial series for negative/fractional indices (lesson/lesson.md).
   - ADD GIF at the Pascal part: a picture of Pascal's triangle growing row by row, each new entry lighting up as the sum of the two above it — the student says each entry before it appears.
   - ADD IMAGE at the theorem part: a picture of the expansion of (a+b)⁴ with arrows joining each coefficient to the matching C(4,k) value — the student follows one arrow and checks the pair agree.
   - ADD IMAGE at the closing part: a picture of a number line from −1 to 1 marked as the safe zone for the series — the student says why x = 2 is outside it.
3. **Say it to your companion** — recite the theorem in words and explain where the coefficients come from (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the binomial chant in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — expand, extract terms, and approximate with the series (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of Pascal's triangle growing row by row → the student predicts each entry.
- IMAGE — a picture of (a+b)⁴ with coefficient arrows to C(4,k) → the student checks one pair.
- IMAGE — a picture of the |x| < 1 zone on a number line → the student tests given x values against it.
- VIDEO — the video-script filmed (made later) → the student recites along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Loses the powers pattern → write the expansion as a table: a's power falls  n, n−1, …, 0 while b's power climbs 0, 1, …, n; the two powers always add to n.
- Cannot see where coefficients come from → go back to Indonesia's Grade 8 K13 pattern work (Bab 1, pp.1–40): build the triangle by addition alone, then read the row for the n in front of you.
- Mixes up (a−b)ⁿ → the signs alternate because the second term is (−b); write (a + (−b))ⁿ and expand that.
- Uses the infinite series at x = 2 → return to the number-line picture: the series is only promised for |x| < 1 (Pakistan, pp.158–159).
- This lesson's next door: Inclusion–Exclusion and Venn Counting (Level 107) — counting with overlaps, where the same care about what was counted twice returns.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Class 11 Unit 8; Indonesia Grade 12 Revisi and Grade 8 K13; Vietnam Grade 10 Volume 2 and study book; Yemen Grade 12 Science; Kuwait Grade 11 Term 2 and Grade 11 Statistics Term 2; Laos Grade 11; Cambodia Grade 10; Egypt Pure Grade 12; Ethiopia Grade 11; Armenia Grade 12 teacher's guide — teacher evidence only; Iraq Grade 11 Scientific and Grade 12 Literary; Kazakhstan Grade 9 algebra books). Hard rule honoured: Indonesia's Grade 12 Merdeka (2022) book does NOT contain Pascal's triangle and is cited nowhere for it — Pascal rests on the 2025 Revisi (pp.113–118) and Grade 8 K13. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
