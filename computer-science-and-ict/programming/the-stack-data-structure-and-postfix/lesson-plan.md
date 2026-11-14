# Lesson plan — The Stack Data Structure — and Postfix

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The Stack Data Structure — and Postfix
**Place in the curriculum:** ICT expansion — Indonesia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Indonesia's Informatika books (Indonesia Grade 8 G8 Informatika student, Indonesia Grade 10 G10 Informatika student, Indonesia Grade 8 G8 Informatika teacher guide, Indonesia Grade 10 G10 Informatika teacher guide), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** the stack data structure — a pile where the last value in is the first out, with push and pop; evaluating postfix expressions with a stack; and choosing stack or queue (Indonesia Grades 8 and 10).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The stack — last in, first out** — A **stack** (tumpukan) is a data structure that keeps its values in a pile with one open end — the **top**. Two operations work it: **push** puts a value on top, **pop** takes the top value off. Its law is **LIFO** — the last value in is the first value out — like a pile of plates, or the undo history of an editor. Indonesia meets the stack twice: in Grade 8's computational thinking, and in Grade 10, where it is chosen (against the queue) as the structure a problem needs. A stack is not a list with manners; its restriction — only the top may be touched — is exactly its power.
2. **Postfix — the stack computes** — Grade 8's jewel is **postfix** evaluation (the book's 'cara Koko' — Koko's way): in postfix notation the operator follows its values — `3 4 +` instead of `3 + 4` — and a stack evaluates it mechanically: read left to right, **push numbers**, and when an **operator** arrives, **pop two values, apply it, push the result**. At the end, the stack holds the single answer. No brackets, no precedence rules — the stack's order does the whole grammar. The same chapter's Grade 10 twin completes the picture: the **queue** beside the stack, first-in-first-out, and simulations that teach choosing between them by the problem's shape.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Indonesia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A data structure keeping values in a pile with one open end — the top
2. Push puts a value on top; pop takes the top value off
3. Last in, first out — the stack's law
4. A pile of plates, and an editor's undo history

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The stack data structure — a pile where the last value in is the first out, with push and pop; evaluating postfix expressions with a stack; and choosing stack or queue (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the stack — last in, first out as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of postfix — the stack computes in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the stack — last in, first out → the student studies the picture and names what each part shows
- GIF — a GIF of postfix — the stack computes in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
