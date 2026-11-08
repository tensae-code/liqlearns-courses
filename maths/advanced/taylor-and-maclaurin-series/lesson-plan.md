<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Taylor and Maclaurin Series

**Course:** Maths · **Unit:** Unit 12 — Advanced Mathematics · **Lesson:** Taylor and Maclaurin Series
**Place in the curriculum:** Level 96 of 136, Unit 12 — Advanced Mathematics (maths/CURRICULUM.md).
**The one thing this lesson teaches:** Taylor and Maclaurin series — rebuilding a function as an endless polynomial around a point: the Maclaurin series of 1/(1+x), sin x, aˣ, eˣ and (1+x)ⁿ, Taylor series about a non-zero point, and using a few terms to compute numbers like sin 31°.
**This lesson's own level:** it stands on the derivatives lesson (the coefficients are derivatives) and the sequences-and-series lesson (the series must converge). It needs nothing else. This lesson has ONE full source — Pakistan's Class 12 book, §2.17 — and it is built honestly at that size.

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

1. **The Maclaurin Template and eˣ** — the Maclaurin template, and the series for eˣ. (One paragraph in this text builds eˣ and aˣ together and is kept whole here; aˣ is Sub lesson 2's ground in the questions.) (Was depth Level 1.)
2. **The Standard Maclaurin Series** — the standard Maclaurin series: sin x, aˣ, 1/(1+x) and (1+x)ⁿ, each with its range of x where the book requires one. (Was depth Level 2.)
3. **Taylor Series and Computing Numbers** — Taylor series about a centre that is not 0, and computing numbers with them: ln(1+x) about x = 2, and sin 31° the book's way. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: the derivatives lesson, including successive (higher-order) differentiation — every coefficient in the series is a derivative at one point. Recommended, never forced.
- Recommended first: the sequences-and-series lesson — a series only names a number when it converges. Recommended, never forced.

## What the learner can do when it ends
1. Write the Maclaurin template f(x) = f(0) + xf′(0) + x²f″(0)/2! + x³f‴(0)/3! + … and say where each coefficient comes from (Pakistan, Class 12, Ch.2 §2.17, ch-pp.74–81).
2. Produce the Maclaurin series of eˣ and of aˣ (Pakistan, Class 12, Ch.2 §2.17, ch-pp.74–78).
3. Produce the Maclaurin series of sin x and of 1/(1+x), with |x| < 1 for the second (Pakistan, Class 12, Ch.2 §2.17, ch-pp.74–78).
4. Produce the Maclaurin (binomial) series of (1+x)ⁿ for any n, with |x| < 1 when n is not a whole number (Pakistan, Class 12, Ch.2 §2.17, ch-pp.74–78).
5. Build a Taylor series about a point other than 0 — ln(1+x) about x = 2 (Pakistan, Class 12, Ch.2 §2.17, ch-pp.78–81).
6. Use a Taylor series to compute a number the calculator way the book does: sin 31° ≈ 0.5150 (Pakistan, Class 12, Ch.2 §2.17, ch-pp.78–81).

## What you need
Paper and a pencil. A calculator for checking the approximations.

## The run of the lesson (in order)
1. **Do it first** — the learner adds 1 + 1 + 1/2 + 1/6 + 1/24 + 1/120 on a calculator, watches the sum settle near 2.718, and meets e as a polynomial before the series is named (lesson/lesson.md).
2. **The explanation** — the Maclaurin template; eˣ and aˣ; sin x; 1/(1+x) and (1+x)ⁿ; Taylor about another point; computing sin 31° (lesson/lesson.md).
   - ADD GIF at the template part: a picture of the graph of eˣ with polynomial approximations of one, two, three and four terms hugging it closer and closer near 0 — the student says how far each approximation can be trusted.
   - ADD IMAGE at the sin x part: a picture of y = sin x with the curves y = x and y = x − x³/6 drawn over it → the student points to where the three-term curve leaves the sine curve.
   - ADD IMAGE at the Taylor part: a picture of the same function expanded at 0 and at x = 2, the second polynomial hugging the curve near 2 → the student says why the centre matters.
3. **Say it to your companion** — explain where the 2!, 3! in the denominators come from, and why sin 31° is computed around 30°, not around 0° (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — Taylor and Maclaurin series in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, matching, ordering — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — build three series and compute two numbers, the book's ways (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of eˣ with one-, two-, three- and four-term polynomials hugging it closer near 0 → the student says how far each can be trusted.
- IMAGE — a picture of sin x with y = x and y = x − x³/6 over it → the student points to where the approximation leaves the curve.
- IMAGE — a picture of one function expanded at 0 and at x = 2 → the student says why the centre matters.
- VIDEO — the video-script filmed (made later) → the student follows the term-by-term build with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Forgets the factorials → each term divides by the factorial of its power: the x³ term carries 3! = 6. Build the template once, slowly, from f(0) (Pakistan, Class 12, §2.17, ch-pp.74–81).
- Uses the Maclaurin series of 1/(1+x) at x = 2 → that series needs |x| < 1; outside its range it does not settle on the function at all (Pakistan, Class 12, §2.17, ch-pp.74–78).
- Expands sin 31° about 0° and needs endless terms → move the centre: Taylor about 30°, where sin and cos are known exactly, and the step is only 1° (Pakistan, Class 12, §2.17, ch-pp.78–81).
- Mixes degrees and radians → series work in radians: 1° = π/180 ≈ 0.01745 before any term is computed.
- This lesson's next door: Parametric Equations (Level 97, same stage) — curves given by a travelling parameter.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Class 12, Ch.2 §2.17 only — the sole full source for this lesson, as filed). The book prints the section heading as "TAILOR SERIES"; the lesson uses the mathematician's name, Taylor. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
