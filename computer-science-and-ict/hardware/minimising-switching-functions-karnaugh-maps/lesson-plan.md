# Lesson plan — Minimising Switching Functions — Karnaugh Maps

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Minimising Switching Functions — Karnaugh Maps
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A switching function can be built with fewer gates than its first written form: the algebraic method shortens it with the Boolean laws, and the Karnaugh map shortens it by eye — the truth table is drawn as a grid where neighbouring cells (in Gray-code order) differ in exactly one variable, so groups of 1s of size 1, 2, 4 or 8 read off directly as simpler terms.
**This lesson's own level:** It stands on the two Boolean lessons before it in Montenegro's climb — operations, truth tables and the laws including absorption and De Morgan. A learner who cannot yet simplify algebraically should do the Boolean laws lesson first; it is recommended, never forced.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Why minimise, and the algebraic method** — A switching function is a Boolean function that switches a circuit; minimising it means fewer gates, fewer inputs, lower cost and less power for the same truth table. The algebraic method works with the laws: factor out common parts (distribution), kill complement pairs (B + B̄ = 1), absorb swallowed terms, and combine pairs of terms that differ in exactly one variable (A·B + A·B̄ = A). Worked example: Ā·B·C + A·B·C + Ā·B·C̄ + A·B·C̄ = B.
2. **Karnaugh maps — minimising by eye** — The Karnaugh map redraws the truth table as a grid: rows and columns are labelled in Gray-code order (00, 01, 11, 10) so that physically neighbouring cells — including across the edges, which wrap around — differ in exactly one variable. Copy the 1s from the truth table, group them in rectangles of 1, 2, 4 or 8 that are as large as possible, and read one term per group: the variables that stay the same inside the group, plain if always 1, barred if always 0; a variable that changes inside the group disappears. Maps for two, three and four variables.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Boolean Laws and De Morgan's Theorems, the lesson before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what a switching function is and why minimising it saves real hardware.
2. Merge pairs of terms that differ in exactly one variable, using distribution and the complement law.
3. Draw a Karnaugh map for two, three or four variables with Gray-code order 00, 01, 11, 10, including the wrap-around edges.
4. Group the 1s in rectangles of 1, 2, 4 or 8 and read the minimised expression off the groups.

## What you need
Paper, a pencil and a ruler for drawing grids. Squared paper makes the Karnaugh maps much easier.

## The run of the lesson (in order)
1. **Do it first** — A function is written as four long terms, each with three letters and bars. Built as written, it needs a pile of gates. But drawn on the right grid, three of its four terms turn out to be neighbours — and neighbours merge. The pile shrinks to one small term. This lesson teaches the two ways to shrink a switching function: by algebra, and by map. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a four-term expression shrinking in three merging steps, each pair bracketed with the law named under the step — the student follows the brackets with a finger and says which variable disappears at each merge.
   - ADD IMAGE: a picture of a four-variable Karnaugh map in Gray-code order with two large rectangles drawn over its 1s, one wrapping around the edges — the student traces the wrapping rectangle and explains why the two edge cells count as neighbours.
   - ADD GIF: a GIF of 1s appearing on a Karnaugh map one by one, then rectangles growing over them — doubling 1, 2, 4 — until every 1 is covered — the student predicts the largest rectangle for each new group of 1s before the GIF draws it.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a four-term expression shrinking in three merging steps, each pair bracketed with the law named under the step → the student follows the brackets with a finger and says which variable disappears at each merge.
- IMAGE — a picture of a four-variable Karnaugh map in Gray-code order with two large rectangles drawn over its 1s, one wrapping around the edges → the student traces the wrapping rectangle and explains why the two edge cells count as neighbours.
- GIF — a GIF of 1s appearing on a Karnaugh map one by one, then rectangles growing over them — doubling 1, 2, 4 — until every 1 is covered → the student predicts the largest rectangle for each new group of 1s before the GIF draws it.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Labels the map 00, 01, 10, 11 → that order breaks the whole idea; neighbours must differ in one variable, so the order is 00, 01, 11, 10 — write the labels before any 1s. Draws a group of 3 or 6 → groups double: 1, 2, 4, 8; reshape the rectangles until every size is a power of two. Forgets the wrap-around → the edges are neighbours too; some of the best groups live half on the left edge and half on the right.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
