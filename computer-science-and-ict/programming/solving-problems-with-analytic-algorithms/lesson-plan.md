# Lesson plan — Solving Problems with Analytic Algorithms

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Solving Problems with Analytic Algorithms
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** An analytic algorithm solves a problem by finding the relationship inside it — a formula connecting what is given to what is wanted — and then simply calculating: model the problem, derive the formula, compute with the given values, and check the answer against the problem.
**This lesson's own level:** It stands on the lessons about algorithms and Polya's four steps: this is problem-solving where the road from givens to answer is a formula. School mathematics (letters for unknowns, simple formulas) is the only ground it needs.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What an analytic algorithm is** — Some problems carry their answer inside a **relationship**: the wanted quantity depends on the given quantities in a fixed way that can be written as a **formula**. An **analytic algorithm** finds that formula first — it analyses the problem until the relationship stands clear — and then obtains every answer by substitution and calculation. The thinking happens once, up front: model the problem (name the quantities, say how they relate), derive the formula, and the rest is arithmetic. Contrast it with trying cases one by one: analysis replaces searching with knowing.
2. **The analytic way, worked** — The method runs in four moves. **Model**: read the problem, name what is given and what is wanted, and state in words how they relate. **Derive**: turn the relation into a formula with letters. **Compute**: put the given values in and calculate, keeping units honest. **Check**: test the formula on an easy case you can verify by hand — if it fails there, the model, not the arithmetic, is wrong. Worked on the taxi: model — fare grows by the per-kilometre price with distance, on top of a fixed start; derive — F = S + P × D; compute — S = 10, P = 2, D = 7 gives F = 24; check — D = 0 must give exactly the starting price, and it does.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Say what an analytic algorithm is: solving by deriving the formula that connects givens to the wanted answer.
2. Name the four moves: model, derive, compute, check.
3. Work the taxi-fare example through all four moves.
4. Say why the check uses an easy case, and what a failed check tells you.

## What you need
Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — A taxi charges a starting price plus a price per kilometre. Asked the fare for 3 km, then 7 km, then 20 km, you could simulate the meter click by click — or see the shape of the problem once: fare = start + price × distance, and every question becomes one calculation. Seeing that shape is this lesson. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the taxi meter problem drawn twice — on the left a long winding path of clicks and additions, on the right one straight arrow labelled with the fare formula — the student points at the straight arrow and says what was discovered to draw it.
   - ADD IMAGE: a picture of the four moves as four stepping stones across a stream — Model, Derive, Compute, Check — with the taxi formula written on the Derive stone — the student steps a finger across and says what happens on each stone.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the taxi meter problem drawn twice — on the left a long winding path of clicks and additions, on the right one straight arrow labelled with the fare formula → the student points at the straight arrow and says what was discovered to draw it
- IMAGE — a picture of the four moves as four stepping stones across a stream — Model, Derive, Compute, Check — with the taxi formula written on the Derive stone → the student steps a finger across and says what happens on each stone
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Jumps to calculating before modelling → the formula is the lesson; arithmetic without the relationship is guessing with numbers. Check fails and the learner redoes the arithmetic → a failed easy case almost always means the model is wrong (a quantity misread, a fixed part forgotten), so re-read the problem before re-adding.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
