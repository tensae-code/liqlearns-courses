# Lesson plan — Boolean Algebra and Logic Operations

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Boolean Algebra and Logic Operations
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** Boolean algebra is the mathematics of two values only — 0 and 1, false and true — with three basic operations (negation NOT, logical addition OR, logical multiplication AND) plus exclusive OR (XOR), and a truth table is the complete list of what an operation or expression gives for every possible input.
**This lesson's own level:** It stands on the number-systems and codes lessons before it in Montenegro's climb — the learner already knows a bit is 0 or 1. No electronics is needed: the operations are ideas first, and the book itself teaches them before any circuit.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The two values and the three basic operations — NOT, OR, AND** — Boolean variables take only the values 0 and 1. Negation (NOT, written with a bar over the variable) flips the value. Logical addition (OR, written +) gives 1 when at least one input is 1. Logical multiplication (AND, written ·) gives 1 only when all inputs are 1. Each operation is defined completely by its truth table.
2. **Exclusive OR, and reading combined expressions** — Exclusive OR (XOR, written ⊕) gives 1 when the inputs are different — exactly one of them is 1: it is 'one or the other, but not both'. Combined expressions are worked bracket by bracket, NOT first, then AND, then OR, and a full truth table of a combined expression is built column by column, one operation at a time.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Number Systems and Conversions and Codes — BCD and ASCII, the two lessons before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what a Boolean variable is and write the truth tables of NOT, OR and AND from memory.
2. Write the truth table of XOR and say how it differs from OR in one row only.
3. Count the rows of any truth table as 2ⁿ for n inputs.
4. Build the truth table of a combined expression column by column, in the order: brackets, NOT, AND, OR.

## What you need
Paper and a pencil — truth tables are drawn by hand so every row is thought through, not copied.

## The run of the lesson (in order)
1. **Do it first** — A light in a hall is controlled by two switches. Sometimes the light is on only when both switches are on; in another hall, either switch alone turns it on; on the stairs, flipping either switch changes the light from on to off or off to on. Three different behaviours — this lesson gives each one a name and a symbol, and they are the whole beginning of how computers decide. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the truth tables of NOT, OR and AND as one chart, the OR output shaded on the three rows where at least one input is 1, the AND output shaded only on the all-ones row — the student covers the output columns and writes them from the sayings 'at least one' and 'all', then uncovers to check.
   - ADD GIF: a GIF of a staircase light flipping on and off as each of its two switches is flipped in turn — both flips shown, ending back where it started — the student says 'same or different?' for each pair of switch positions and predicts the light before each flip.
   - ADD IMAGE: a picture of a combined expression's truth table half-built, with one new working column per operation appearing in a lighter shade — the student builds the table of a given expression one column at a time and checks the row count is 2ⁿ before starting.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the truth tables of NOT, OR and AND as one chart, the OR output shaded on the three rows where at least one input is 1, the AND output shaded only on the all-ones row → the student covers the output columns and writes them from the sayings 'at least one' and 'all', then uncovers to check.
- GIF — a GIF of a staircase light flipping on and off as each of its two switches is flipped in turn — both flips shown, ending back where it started → the student says 'same or different?' for each pair of switch positions and predicts the light before each flip.
- IMAGE — a picture of a combined expression's truth table half-built, with one new working column per operation appearing in a lighter shade → the student builds the table of a given expression one column at a time and checks the row count is 2ⁿ before starting.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Swaps OR and AND → the sayings are the cure: OR is 'at least one is enough', AND is 'all or nothing'. Tries 1 + 1 = 2 → this algebra has no 2; 1 + 1 = 1, because at least one input is 1 and the answer can only be 0 or 1. Jumps straight to the final column of a combined table → one column per operation, always; the table is built, never guessed.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
