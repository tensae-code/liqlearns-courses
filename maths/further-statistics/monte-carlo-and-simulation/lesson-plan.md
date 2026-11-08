<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Monte Carlo and Simulation

**Course:** Maths · **Unit:** Unit 16 — Further Statistics and Probability · **Lesson:** Monte Carlo and Simulation
**Place in the curriculum:** Level 130 of 136, the fourteenth lesson of Unit 16 — Further Statistics and Probability (maths/CURRICULUM.md).
**The one thing this lesson teaches:** manufacturing chance on purpose — random numbers (from a printed table and from the linear congruential generator), simulation of real experiments with them, and the Monte Carlo idea: estimate a probability by the frequency in a long simulated run — closing with Mendel's pea ratios read as a probability model tested against real counts.
**This lesson's own level:** it stands on Geometric and Experimental Probability (Level 129, same unit) — a simulation is an experimental probability with the trials manufactured instead of performed. It needs nothing else.

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

1. **Random Numbers and Digits** — say what random digits are for, read a short run off a table under a fixed rule, and turn digits into coin tosses without changing the rule mid-run. (Was depth Level 1.)
2. **The Congruential Generator and PPS Ranges** — run the linear congruential generator xₙ₊₁ = axₙ + b (mod m) from a seed and spot the cycle returning; Table 7.1 is worked here — its first half is Sub lesson 1's table-reading at work — and ranges are assigned in proportion to cumulative probabilities (PPS). (Was depth Level 2.)
3. **Monte Carlo and Testing a Model** — state the Monte Carlo method, judge how long a run must be before its frequency can be trusted, and test the Mendel model's 0.25/0.5/0.25 against counts in the closing part. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Geometric and Experimental Probability (Level 129, same unit) — simulation spends its whole life estimating probabilities by frequencies. Recommended, never forced.
- Recommended first: Probability (Unit 11) — a simulation must copy an experiment's true chances, or it answers a question nobody asked. Recommended, never forced.

## What the learner can do when it ends
1. Say what a random number and a random digit are for: standing in for the outcomes of a real experiment (Pakistan, Statistics Class 11, Ch. 7, pp.186–196).
2. Run the linear congruential generator xₙ₊₁ = axₙ + b (mod m), reproducing Pakistan's worked run — seed 5, a = 13, b = 0, m = 16 giving 1, 13, 9, 5 — and say why the sequence must eventually repeat (Pakistan, Ch. 7).
3. Read random digits off a printed table — Pakistan's Table 7.1 (p.189) — and use them to simulate one-coin, two-coin and three-coin experiments (Pakistan, Ch. 7).
4. Assign random-number ranges in proportion to size (PPS) from cumulative probabilities (Pakistan, Ch. 7).
5. State the Monte Carlo method in one sentence — estimate a probability by simulating the experiment many times and taking the frequency — as China's book teaches random simulation (China, A edition Compulsory Volume 2, §10.3.2, p.255).
6. Close with the model-testing idea, worded as the reading it is filed as: Mendel's pea ratios as a probability model — DD, Dd, dd with probabilities 0.25, 0.5, 0.25, the dominant form totalling 0.75, the famous ≈3:1 — against Mendel's real counts (China, Ch. 10 reading, pp.259–260, reading as filed).

## What you need
Paper and a pencil.
A coin — to check a small simulation against the real thing.
Squared paper for tallying long runs.

## The run of the lesson (in order)
1. **Do it first** — the learner needs 200 coin tosses for a question and refuses, quite rightly, to perform them; the lesson offers a cheaper factory (lesson/lesson.md).
2. **The explanation** — random numbers and digits; the congruential generator; Table 7.1 at work on coin experiments; PPS ranges; Monte Carlo in Pakistan's and China's forms; the Mendel reading as the closing part (lesson/lesson.md).
   - ADD GIF at the generator part: a picture of the congruential wheel turning — each number multiplied, added, and wrapped around the modulus back into range → the student predicts the next number before the wheel stops.
   - ADD IMAGE at the table part: a picture of a page of random digits with one row circled and its digits paired off as coin tosses → the student reads the next pair and calls the toss.
   - ADD IMAGE at the Mendel part: a picture of pea pods split between round and wrinkled in a rough three-to-one heap → the student counts the heaps and compares them with 0.75.
3. **Say it to your companion** — explain how a table of digits becomes a coin, and how a model is tested against counts (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — manufactured chance in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — a generator run, a table simulation and a model check, each written up in whole sentences (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of the congruential wheel turning and wrapping at the modulus → the student predicts the next value.
- IMAGE — a picture of Table 7.1-style digits with a row circled and paired → the student calls the next simulated toss.
- IMAGE — a picture of pea heaps in a rough 3:1 split → the student compares the count with the model's 0.75.
- VIDEO — the video-script filmed (made later) → the student runs the generator along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Thinks the generator's numbers are "really" random → they are pseudo-random: one seed and one rule rebuild the whole run, which is why Pakistan's worked run can be checked digit for digit — and why the run must repeat once it returns to its seed (5 comes back after 1, 13, 9).
- Reads the table in clumps that suit the answer → fix the reading rule before starting: direction, grouping, and what each digit means. A rule chosen after seeing the digits is not a simulation, it is a wish.
- Simulates once and trusts it → one short run is one frequency, with all the wobble of Lesson 129. Monte Carlo earns its name only in long runs.
- Treats the Mendel reading as a taught theorem → it is filed as a reading: a model (0.25, 0.5, 0.25) held up against real counts. Report it as a reading, exactly as filed.
- This lesson's next door: Odds (Level 131, same unit) — probability said the bookmaker's way.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Statistics Class 11, Ch. 7 — random numbers, the congruential generator, Table 7.1 and the PPS ranges; China A edition Compulsory Volume 2 — Monte Carlo at §10.3.2, p.255, and the Mendel reading at pp.259–260, worded as a reading as filed). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
