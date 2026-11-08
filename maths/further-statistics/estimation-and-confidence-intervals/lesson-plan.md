<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Estimation and Confidence Intervals

**Course:** Maths · **Unit:** Unit 16 — Further Statistics and Probability · **Lesson:** Estimation and Confidence Intervals
**Place in the curriculum:** Level 120 of 136, Stage 16 — Further Statistics and Probability (maths/CURRICULUM.md).
**The one thing this lesson teaches:** estimation — point against interval estimation, unbiasedness, and confidence intervals for means, proportions and differences — closing with the German tank problem.
**This lesson's own level:** it stands on Sampling and Sampling Distributions (Level 119, same stage) — the learner can already build a sampling distribution and name its standard error. It needs nothing else.

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

1. **Point Estimation and Unbiasedness** — separate estimator, estimate, point and interval estimation; judge unbiasedness by E(T) = θ; and keep the point estimation error apart from the standard error. (Was depth Level 1.)
2. **Confidence Intervals for a Mean** — build a z interval with σ known and a t interval with σ unknown and small n, and say correctly what the confidence level means. (Was depth Level 2.)
3. **Proportions, Differences and the German Tank Problem** — build intervals for a proportion and for differences of means and proportions, describe Iran's machinery-free estimation, and run the German tank estimate. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Sampling and Sampling Distributions (Level 119, same stage) — a confidence interval is a sampling distribution turned into a range. Recommended, never forced.
- Recommended first: Random Variables and Distributions (Level 118, same stage) — the z and t values come from those distributions. Recommended, never forced.

## What the learner can do when it ends
1. Say what an estimator, an estimate, a point estimate and an interval estimate are, the way Pakistan's Class 12 Statistics book opens its estimation chapter (Ch. 12, p.73).
2. Judge unbiasedness by E(T) = θ, and say why Ŝ² with denominator n − 1 is unbiased where S² with denominator n is not, proved by enumeration in Pakistan's book (Ch. 12, pp.74–76).
3. Keep the two errors of a point estimate apart: |x̄ − μ| is the point estimation ERROR, while the standard error of x̄ is σ/√n — the corrected reading of Kuwait's Grade 12 book (4-1, p.171, error corrected).
4. Build a confidence interval for a mean with σ known, x̄ ± z·σ/√n, as Kuwait works its pulse-rate study: n = 40, σ = 12.5, x̄ = 76.3 → (72.4262, 80.1738) (4-1, pp.168–176).
5. Build a t interval when σ is unknown and n is small, with ν = n − 1, as Kuwait works n = 25, S = 10, x̄ = 15 → (10.872, 19.128) at 95% (4-1, pp.168–176) and Pakistan teaches (Ch. 12, pp.82–90).
6. Build confidence intervals for a proportion and for differences of two means and two proportions, as Pakistan teaches them (Ch. 12, pp.92–107).
7. Say what Iran's way adds and leaves out: point and interval estimation taught conceptually, WITHOUT z-machinery (Grade 11 Statistics and Probability, Ch. 4, pp.97–121) — and never cite Iran for hypothesis testing, which that book does not teach.
8. Estimate a hidden total the German-tank way, N ≈ x_max·(n + 1)/n, from China's A-edition reading (Ch. 9, reading, pp.208–209).

## What you need
Paper and a pencil. A calculator. The standard normal (z) table and the t table. A set of numbered slips for the tank problem.

## The run of the lesson (in order)
1. **Do it first** — the learner guesses a jar's sweet count with one number, then with a range they would bet on, and says which answer is more honest (lesson/lesson.md).
2. **The explanation** — point against interval; unbiasedness; the point estimation error against the standard error (corrected); z intervals; t intervals; intervals for proportions and differences; Iran's machinery-free way; the German tank problem (lesson/lesson.md).
   - ADD GIF at the confidence idea part: a picture of twenty sample intervals drawn under one bell, nineteen catching the true mean line and one missing it — the student counts the misses and says what 95% means.
   - ADD IMAGE at the unbiasedness part: a picture of two target diagrams — darts centred on the bull but scattered, and darts tight but off to one side → the student names which fault is bias and which is variance.
   - ADD IMAGE at the German tank part: a picture of captured tank parts stamped with serial numbers, the largest number circled → the student applies N ≈ x_max·(n + 1)/n to the numbers shown.
3. **Say it to your companion** — explain why a 95% interval is not "a 95% chance the parameter is inside this one interval" (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — estimation in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — build four intervals the books' ways and estimate one hidden total (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of twenty 95% intervals under a bell, one missing the true mean → the student counts the misses and states the meaning of 95%.
- IMAGE — a picture of two dart targets, scattered-but-centred against tight-but-off-centre → the student separates bias from variance.
- IMAGE — a picture of stamped serial numbers with the largest circled → the student runs the German tank estimate.
- VIDEO — the video-script filmed (made later) → the student builds an interval along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Gives one number and stops → that is a point estimate; ask "how wrong could it be?" and the interval appears: estimate ± margin of error (Pakistan, Ch. 12, pp.81–82).
- Calls |x̄ − μ| the standard error → that is Kuwait's printed slip on p.171, taught corrected here: |x̄ − μ| is the point estimation ERROR — one realised difference; the standard error is σ/√n, a property of the method.
- Uses z when σ is unknown and n is small → switch to t with ν = n − 1 degrees of freedom (Kuwait, 4-1, pp.168–176; Pakistan, Ch. 12, pp.82–90).
- Reads 95% as a probability about this one interval → the 95% is about the METHOD: in the long run, 95% of intervals built this way catch the parameter (Pakistan, Ch. 12, pp.81–82).
- This lesson's next door: Hypothesis Testing (Level 121, same stage) — the interval becomes a decision.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Statistics Class 12; Jordan Grade 12 Business Mathematics Term 2; Kuwait Grade 12 Term 1; Egypt Statistics Grade 12; Libya Grade 12 Foundations of Statistics (Science); Laos Grade 12; Iran Grade 11 Statistics and Probability; China A-edition Compulsory Volume 2 reading). One printed error is taught corrected and never as fact: Kuwait's p.171 label — |x̄ − μ| is the point estimation error, and the standard error is σ/√n. Iran is cited for estimation only: its book teaches estimation without z-machinery and does NOT teach hypothesis testing, so Iran appears nowhere in Lesson 121. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
