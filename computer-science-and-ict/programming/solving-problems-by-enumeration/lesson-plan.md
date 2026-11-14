# Lesson plan — Solving Problems by Enumeration

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Solving Problems by Enumeration
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Enumeration solves a problem by listing every possible candidate in an orderly way and testing each against the problem's conditions, keeping those that satisfy them all — simple, certain not to miss a solution, and powerful exactly when the list of candidates stays small enough to finish.
**This lesson's own level:** It stands beside the analytic-algorithms lesson as its twin: same chapter, opposite strategy. It needs careful, orderly listing more than any mathematics.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What enumeration is** — **Enumeration** means listing all the candidates and testing them one by one. An enumeration algorithm has three parts: a way to **generate** every candidate without repeats or gaps (usually in a fixed order — counting order is the favourite); a **test** that checks each candidate against all the problem's conditions; and a **collection** step that keeps the candidates that pass. Because every candidate is tested, enumeration cannot miss a solution that exists inside the list — its certainty is its beauty. Its textbook home is problems with no known formula, or where finding one is harder than searching.
2. **Doing it well — order, and the size of the list** — Good enumeration is **orderly**: generate candidates in a system (all two-digit combinations from 00 upward, all triples in counting order) so none is repeated and none skipped — disorder is how solutions get missed. And good enumeration watches the **size of the list**: ten forgotten digits finish in minutes; a forgotten six-digit code is a million candidates, and a long password is more candidates than a lifetime holds. That explosion is enumeration's limit — the method is certain, but certainty costs time, so the craft is to shrink the list first with anything the problem tells you (a digit known here, a condition that halves the list there) before the testing begins.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Say what enumeration is, and name its three parts: generate, test, collect.
2. Explain why orderly generation matters (no repeats, no gaps, no missed solution).
3. Explain enumeration's limit: the candidate list can explode in size.
4. Shrink a candidate list using a condition from the problem before enumerating.

## What you need
Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — You have forgotten the last digit of a friend's phone number. There is no formula for a forgotten digit — but there are only ten possibilities, and you can try them in order: 0, 1, 2 … until the right voice answers. When the possibilities are few and each is easy to test, trying them all is not a weakness. It is a method, and it has a name. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a sieve over a bowl: a stream of numbered candidate cards pouring in the top, most falling away, two golden cards caught in the mesh — the student points at the mesh and says what it stands for (the conditions, testing every card).
   - ADD GIF: a GIF of a counter of candidates climbing — 10, then 1,000, then 1,000,000, then a number too long for the screen — the student watches once and says at which size they would stop enumerating and start thinking analytically.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a sieve over a bowl: a stream of numbered candidate cards pouring in the top, most falling away, two golden cards caught in the mesh → the student points at the mesh and says what it stands for (the conditions, testing every card)
- GIF — a GIF of a counter of candidates climbing — 10, then 1,000, then 1,000,000, then a number too long for the screen → the student watches once and says at which size they would stop enumerating and start thinking analytically
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Lists candidates in a jumble and loses track → impose counting order and tick candidates off in rows; the order is not decoration, it is the guarantee. Wants to enumerate a huge space → count the list first: candidates = choices multiplied together; if the number explodes, shrink with conditions or look for an analytic route.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
