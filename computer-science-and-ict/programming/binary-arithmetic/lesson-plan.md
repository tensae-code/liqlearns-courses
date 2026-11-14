# Lesson plan — Binary Arithmetic

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Binary Arithmetic
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** Binary numbers are added, subtracted, multiplied and divided by the same rules as decimal, with the smaller tables of base 2: addition carries when a column reaches 2, negative numbers are held as two's complement (invert and add 1) so subtraction becomes addition, multiplication is shift-and-add, and division is repeated compare-and-subtract.
**This lesson's own level:** It stands on the number-systems lesson at the start of Montenegro's climb — bases and place values — refreshed here column by column. It needs no hardware knowledge: this is the arithmetic the next lesson will then build as circuits.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Binary addition, complements and negative numbers** — Binary addition column by column with the four rules: 0+0 = 0, 0+1 = 1, 1+1 = 0 carry 1, 1+1+1 = 1 carry 1. Ones' complement: invert every bit. Two's complement: invert and add 1 — the standard way machines hold negative numbers, so that +5 and −5 in 4 bits are 0101 and 1011, and adding a number to its two's complement gives zero (overflow discarded).
2. **Subtraction, multiplication and division** — Subtraction by complement: A − B is computed as A + (two's complement of B), discarding any carry beyond the register length — the adder does subtraction for free. Multiplication: the school method — one partial product per 1-bit of the multiplier, each shifted one place left from the previous, then added (equivalently: copy-and-shift, then add). Division: the inverse — repeatedly compare, subtract and shift, building the quotient bit by bit, the binary mirror of long division.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Number Systems and Conversions, the first lesson of Montenegro's climb. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Add two binary numbers column by column, handling 1 + 1 = 0 carry 1 and 1 + 1 + 1 = 1 carry 1.
2. Form the ones' complement and the two's complement of a binary number for a stated bit length.
3. Subtract by adding the two's complement and discarding the carry beyond the register length.
4. Multiply by shift-and-add partial products, and divide by repeated compare-and-subtract, giving quotient and remainder.

## What you need
Paper and a pencil — every operation is worked in columns by hand, so the carries are seen, not hidden by a calculator.

## The run of the lesson (in order)
1. **Do it first** — In decimal, 7 + 5 makes a carry because the column overflows past 9. Binary columns overflow far sooner — a column of two 1s is already full. If you can add 1 + 1 and say what the carry is, you can do every operation in this lesson; the rest is patience and columns. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of −5 being made in four bits in three frames: 0101, flipped to 1010, then +1 to give 1011, the sign bit shaded — the student makes −3 in four bits by the same three frames before checking against the lesson.
   - ADD IMAGE: a picture of 101 × 11 worked in columns, the second partial product shifted one place left, the sum 1111 beneath — the student covers the sum and adds the partial products again on paper, then uncovers to check.
   - ADD GIF: a GIF of a binary addition column overflowing: two 1s meet, a 0 is written, and the carry visibly hops into the next column — the student calls the carry aloud each time a column fills, while adding a pair of their own numbers.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of −5 being made in four bits in three frames: 0101, flipped to 1010, then +1 to give 1011, the sign bit shaded → the student makes −3 in four bits by the same three frames before checking against the lesson.
- IMAGE — a picture of 101 × 11 worked in columns, the second partial product shifted one place left, the sum 1111 beneath → the student covers the sum and adds the partial products again on paper, then uncovers to check.
- GIF — a GIF of a binary addition column overflowing: two 1s meet, a 0 is written, and the carry visibly hops into the next column → the student calls the carry aloud each time a column fills, while adding a pair of their own numbers.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Writes 1 + 1 = 2 → 2 does not exist here; 1 + 1 is the column overflowing: write 0, carry 1 — the value 2 written in binary is exactly '10', a 0 here and a 1 in the next column. Forgets the +1 in two's complement → inverting alone is ones' complement, a different (older) system; the machine's negatives need invert *and* add 1, and the check is that number + its complement = 0 in the register length. Panics at the discarded carry in subtraction → the register is only n bits wide; the bit beyond it has nowhere to live, and two's complement is built so what remains is the true answer.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
