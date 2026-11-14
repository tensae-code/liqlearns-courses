# Lesson plan — Frequently Used Logical Functions

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Frequently Used Logical Functions
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The logical functions in constant use beyond and/or/not: NAND, NOR, XOR and XNOR — each defined by its truth table, each built from the basic three, and XOR as the adder's sum bit (Moldova Grade 11, Informatică, §4.3).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **NAND and NOR — the negated pair** — **NAND** is **NOT-AND**: it gives 0 only when both inputs are 1 — the exact negation of AND's table. **NOR** is **NOT-OR**: it gives 1 only when both inputs are 0. Each is **universal**: NAND alone (or NOR alone) can build NOT, AND and OR — whole circuits from one gate kind, which is why real chips are so often NAND chips. Their tables are written by the section's method: take the base function's table, and flip every output.
2. **XOR and XNOR — difference and sameness** — **XOR (exclusive or)** gives 1 when the inputs **differ** (0⊕1, 1⊕0) and 0 when they agree — the function of difference, which is why it is addition's heart: a sum bit is XOR of the addends, carry aside. **XNOR** is its negation — 1 when the inputs **agree** — the function of sameness, used wherever equality of bits is tested. With these four the chapter's kit is complete: every logical function a school circuit will need is basic, negated or comparative — all provable in four-row tables.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. NOT-AND — 0 only when both inputs are 1
2. NOT-OR — 1 only when both inputs are 0
3. Each alone can build NOT, AND and OR — whole circuits from one gate kind
4. Take AND's table and flip every output

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Three operations were enough in theory; practice keeps four more on the desk. Grade 11's Boolean chapter completes its function set with the combinations engineers named because they used them daily. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of nand and nor — the negated pair as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of xor and xnor — difference and sameness in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of nand and nor — the negated pair → the student studies the picture and names what each part shows
- GIF — a GIF of xor and xnor — difference and sameness in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
