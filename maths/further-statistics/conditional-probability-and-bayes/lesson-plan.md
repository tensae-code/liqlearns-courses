<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Conditional Probability and Bayes' Theorem

**Course:** Maths · **Unit:** Unit 16 — Further Statistics and Probability · **Lesson:** Conditional Probability and Bayes' Theorem
**Place in the curriculum:** Level 117 of 136, the first lesson of Stage 16 — Further Statistics and Probability (maths/CURRICULUM.md).
**The one thing this lesson teaches:** the chance of one event *given* that another has happened — P(A|B) — and how to turn a conditional probability around with Bayes' theorem.
**This lesson's own level:** it stands on Probability (Stage 11) — sample spaces, events, P(A) = favourable / total, the addition and multiplication laws. It needs nothing else.

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

1. **Reading "Given"** — read P(A|B) in words and work P(A|B) = P(A∩B) / P(B) from counts or from given probabilities. (Was depth Level 1.)
2. **Independence, Dependence and Trees** — test independence with P(A∩B) = P(A)·P(B), and draw and use a tree for two draws without replacement, with the second branches correctly changed; the multiplication rule turned around is the working form along a branch. (Was depth Level 2.)
3. **Total Probability and Bayes** — split a probability by cases with the total-probability formula and turn a conditional probability around with Bayes' theorem. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Probability (Stage 11) — sample spaces, events and the two laws. Recommended, never forced.
- Recommended first: the sets lesson (Stage 11) — A∩B and A∪B are set language. Recommended, never forced.
- Nothing here needs a distribution — that is the next lesson's home (Level 118).

## What the learner can do when it ends
1. Say what "given" means and read P(A|B) aloud in words (Nicaragua's Grade 11 book puts the formula in a box, p.142; Cambodia's Grade 11 Advanced book writes P(B|A), p.129).
2. Work a conditional probability from counts: P(A|B) = P(A∩B) / P(B) (Kazakhstan's Shynybekov Algebra 9 proves the multiplication form from counts, §5.1.5, p.187).
3. Tell independent events from dependent events, and test independence by P(A∩B) = P(A)·P(B) (Kuwait's Grade 10 book, lesson 10-5, pp.192–205; Egypt's Statistics book, lesson 3-3, p.77).
4. Draw a tree diagram for draws without replacement, with the second branches changed because the bag has changed (Sierra Leone's SSS 3 book, lessons L105–L106, printed pp.27, 30 — tree diagrams only there, with no P(A|B) notation, as filed).
5. Use the multiplication rule in its conditional form: P(A∩B) = P(A)·P(B|A) (Cambodia's Grade 11 Advanced book, p.129).
6. Split a probability by cases with the total-probability formula, then turn it around with Bayes' theorem (Cambodia's PRIVATE Probability booklet, Lesson 2, pp.85–94; Kuwait's Grade 11 book, lesson 11-3, pp.167–178).
7. Work a Bayes problem end to end — Kuwait's quality-test example, where a defective item that was not cancelled still has probability about 0.00041 of being defective (Kuwait Grade 10, problem-solving guide, pp.204–205).

## What you need
Paper and a pencil.
A bag or box with counters or balls of two colours (for example 5 red and 5 blue, then changed numbers as the activities ask).
Two dice.

## The run of the lesson (in order)
1. **Do it first** — the learner draws two counters from a bag without putting the first back, and says how the second chance changed before any formula is named (lesson/lesson.md).
2. **The explanation** — what "given" means; the formula P(A|B) = P(A∩B) / P(B); independent against dependent; tree diagrams; the multiplication rule turned around; total probability; Bayes' theorem (lesson/lesson.md).
   - ADD IMAGE at the "given" part: a picture of a sample space with the B part shaded and the rest greyed out — the student points at the shrunken world the "given" leaves.
   - ADD GIF at the tree-diagram part: a picture of a tree growing its second branches one at a time, the fractions on the second branches changing after a counter is taken out — the student reads each changed fraction aloud.
   - ADD IMAGE at the Bayes part: a picture of a factory quality-test flow — items made, tested, some cancelled, some passed — the student follows one defective item through the flow.
3. **Say it to your companion** — explain "given" in your own words, then swap a without-replacement draw and make your companion say the changed chance (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — conditional probability and Bayes in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — a two-draw tree, a dice conditional, and one Bayes calculation in full (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a sample space with the given event shaded and the rest greyed out → the student points at the shrunken world.
- GIF — a picture of a tree diagram growing, its second-branch fractions changing after a draw → the student reads each changed fraction aloud.
- IMAGE — a picture of a factory quality-test flow → the student follows one defective item through it.
- VIDEO — the video-script filmed (made later) → the student works the bag draw along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Writes P(A|B) but divides by P(A) → the letter after the bar is the new whole: you divide by the probability of the thing you are *given*. Nicaragua's book works it on two dice and a bus-timing problem (pp.141–142) — go back to counts there.
- Thinks the second draw has the same chance as the first → the bag has changed. Sierra Leone's tree lessons (L105–L106) exist for exactly this: draw the tree and make the second fractions different numbers.
- Mixes up P(A|B) and P(B|A) → they are different questions. Kuwait's Grade 10 book works a pair side by side: P(B|A) = 2/3 while P(A|B) = 1/3 (Ex (10), p.202). Bayes' theorem is the machine that swaps them — never swap them by hand.
- Adds where it should multiply along a branch → along one branch of a tree you multiply; across the ends that give the same final result you add. That one sentence is the whole of total probability.
- This lesson's next door: Random Variables and Distributions (Level 118, same stage) — a number tied to each outcome, and the named distributions.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Kuwait Grades 10 and 11; Egypt Statistics Grade 12; Cambodia Grade 11 Basic, Grade 11 Advanced and the PRIVATE Khem Putthi Probability booklet — PRIVATE, not MoEYS, labelled wherever cited; Greece Grade 12 EPAL; Kazakhstan Shynybekov Algebra 9; Nicaragua Grade 11; Iraq Grades 9 and 11 Scientific; Sierra Leone SSS 3 — tree diagrams only, no P(A|B) notation there, as filed). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
