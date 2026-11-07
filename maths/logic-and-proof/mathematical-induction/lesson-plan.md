# Lesson plan — Mathematical Induction

**Course:** Maths · **Stage:** Stage 13 — Logic and Proof · **Lesson:** Mathematical Induction
**Place in the curriculum:** Level 102 of 136, Stage 13 — Logic and Proof (maths/CURRICULUM.md).
**The one thing this lesson teaches:** proof by mathematical induction — the principle, its three steps (base case, induction hypothesis, induction step), and its use for series formulas, divisibility and inequalities, including extended induction — together with the warning that checking cases is not proving: Euler's polynomial n² − n + 41 gives primes for n = 1 to 40 and fails at n = 41.
**This lesson's own level:** it stands on Proof Methods (Level 101, same stage) and the sequences and series lessons — the learner can already prove a single statement and read Σ notation. It needs nothing else.

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

## Before this lesson
- Recommended first: Proof Methods (Level 101, same stage) — induction is one proof method among the ones taught there. Recommended, never forced.
- Recommended first: the sequences and series lessons — most first induction proofs are series formulas. Recommended, never forced.

## What the learner can do when it ends
1. State the principle of induction and carry out its three steps in order — check n = 1; assume the statement for n = k; prove it for n = k + 1 — as Laos's Grade 11 book teaches them (Ch.2 L7, p.28).
2. Prove 1 + 3 + 5 + … + (2n − 1) = n² by induction, the opening proof of Cambodia's Grade 11 Advanced book (Ch.1 L3, pp.24–34).
3. Prove the series formula 1 + 2 + … + n = n(n + 1)/2 by induction, as Kazakhstan's Grade 9 books prove it (Yelemessov, §3.1, p.80; Abylkasymova, §18, p.153).
4. Prove a divisibility statement by induction, such as 6²ⁿ − 1 divisible by 35, as Kazakhstan's Abylkasymova Algebra 9 sets it (§18, p.153).
5. Explain why checking n = 1 to 40 proves nothing by itself, using Pakistan's warning exhibit — Euler's n² − n + 41, prime for n = 1…40 and composite at n = 41 (Class 11, Unit 8, pp.140–150).
6. Say what extended induction adds — the hypothesis may be assumed from a later starting point or for several values at once — as Pakistan's Class 11 book teaches it (Unit 8, pp.140–150).
7. Spot a broken induction: a step that works only from some k onward, or a base case never checked — the "find the student's error" habit of Kazakhstan's Soltan Algebra 9 (§14, p.100).
8. Name where induction does the proving inside other results: Vietnam's Grade 10 study book proves Newton's binomial theorem by it (Bài 4, p.32), after teaching the method itself (Bài 3, p.25).

## What you need
Paper and a pencil. A row of dominoes — real or drawn — makes the principle visible.

## The run of the lesson (in order)
1. **Do it first** — the learner checks Euler's n² − n + 41 for n = 1, 2, 3, 4, finds primes every time, and is asked whether the claim "always prime" is now proved (lesson/lesson.md).
2. **The explanation** — the principle; the three steps; a series proof in full; a divisibility proof; inequalities and extended induction; broken inductions (lesson/lesson.md).
   - ADD GIF at the principle part: a picture of a row of dominoes, the first one pushed, each falling domino knocking the next — the student matches "first falls" to the base case and "each knocks the next" to the induction step.
   - ADD IMAGE at the series-proof part: a picture of the staircase 1 + 3 + 5 + … drawn as square layers building n² → the student points to the layer added when n grows by 1.
   - ADD IMAGE at the warning part: a picture of a tally chart, 40 boxes ticked "prime" and the 41st crossed in red → the student says in one sentence why 40 ticks are not a proof.
3. **Say it to your companion** — each partner talks the other through one full induction proof, naming the three steps out loud as they come (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — induction in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, matching, ordering — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — run three induction proofs of your own: one series, one divisibility, one inequality (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of falling dominoes, each knocking the next → the student matches the first fall to the base case and each knock to the induction step.
- IMAGE — a picture of square layers building n² from odd numbers → the student points to the layer added at each step.
- IMAGE — a picture of a 41-box tally chart with the last box crossed → the student says why 40 ticks are not a proof.
- VIDEO — the video-script filmed (made later) → the student follows the n² proof with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Proves the step by assuming the conclusion → in the step you may assume the statement for k only; the statement for k + 1 is what must be earned, by algebra, from it (Laos, Grade 11, Ch.2 L7, p.28).
- Skips the base case → without n = 1 the staircase has no first stair: the step alone can "prove" false statements, as Kazakhstan's Shynybekov book shows by dissecting a false proof (Algebra 9, §3.2*, p.72).
- Thinks induction means checking many cases → that is exactly the trap of Euler's polynomial: 40 true cases, false claim (Pakistan, Class 11, Unit 8, pp.140–150).
- Loses the algebra in the step → write the target for k + 1 first, then split off the k-sum and replace it by the hypothesis — the shape of Cambodia's n² proof (Grade 11 Advanced, pp.24–34).
- This lesson's next door: The Pigeonhole Principle (Level 103, same stage) — another small principle with outsized power.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Class 11; Armenia Grade 11, both streams; Vietnam Grade 10 study book; Greece Grade 11 orientation book; Cambodia Grade 11 Advanced; Kazakhstan Grade 9 Algebra books; Laos Grade 11; Iraq Grade 12 Scientific — filed "for information only" and worded as such wherever it appears). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
