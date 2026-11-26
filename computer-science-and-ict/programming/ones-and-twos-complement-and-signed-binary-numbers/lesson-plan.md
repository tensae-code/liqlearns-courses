# Lesson plan — Ones and Twos Complement and Signed Binary Numbers

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Ones and Twos Complement and Signed Binary Numbers
**Place in the curriculum:** Phantom repair — Kenya (2026-11-25) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Kenya's *Log On Computer Studies Form 3* (student book), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A computer stores negative numbers in binary by complementing: the ones complement flips every bit, and the twos complement flips every bit and adds 1 — with the leftmost bit acting as the sign, twos complement lets the machine subtract by adding, using the same adder circuit it already has.
**This lesson's own level:** It stands on the lessons named under "Before this lesson"; it stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Signed numbers and the ones complement** — Pure binary cannot show a minus sign, so one bit is given the job: the leftmost (most significant) bit is the sign bit — 0 for positive, 1 for negative. In ones complement, a negative number is written by flipping every bit of its positive form. Ones complement has two zeros (+0 and −0), one of its weaknesses.
2. **Twos complement — and subtracting by adding** — Twos complement: flip every bit, then add 1. It has a single zero and one more negative value than positive. Its real prize: subtraction becomes addition — to compute A − B, add the twos complement of B to A and throw away any carry beyond the register size; the answer is already in correct twos-complement form.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Programming lesson on binary arithmetic, and the First Steps lessons on bits, bytes and number systems, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kenya's own way is kept: the book teaches this inside its own unit/chapter order, in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Read the sign of a binary number from its leftmost bit and state the range of an 8-bit signed number.
2. Write the ones complement of any binary number by flipping its bits.
3. Write the twos complement by flipping the bits and adding 1.
4. Subtract two binary numbers by adding the twos complement of the number being taken away.

## What you need
Paper and a pencil. A row of eight boxes drawn on paper serves as the 8-bit register.

## The run of the lesson (in order)
1. **Do it first** — Write the number 5 in 8-bit binary: 00000101. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of two rows of eight bit boxes: 00000101 labelled +5, and beneath it 11111010 with curved arrows showing every bit flipped — the student flips one more number on paper before checking
   - ADD GIF: a GIF of a row of bits flipping one by one, 0s turning to 1s and 1s to 0s, until the whole row is inverted — the student says what operation just happened
   - ADD IMAGE: a picture of the addition 00001001 + 11111011 lined up in columns, with the ninth carry bit circled and crossed out, leaving 00000100 — the student works the same sum on paper and circles the carry to discard
   - ADD GIF: a GIF of bits flipping, then a +1 ripple running along the row from the right, turning the ones complement into the twos complement — the student calls out where the ripple stops
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of two rows of eight bit boxes: 00000101 labelled +5, and beneath it 11111010 with curved arrows showing every bit flipped — the student flips one more number on paper before checking
- GIF — a GIF of a row of bits flipping one by one, 0s turning to 1s and 1s to 0s, until the whole row is inverted — the student says what operation just happened
- IMAGE — a picture of the addition 00001001 + 11111011 lined up in columns, with the ninth carry bit circled and crossed out, leaving 00000100 — the student works the same sum on paper and circles the carry to discard
- GIF — a GIF of bits flipping, then a +1 ripple running along the row from the right, turning the ones complement into the twos complement — the student calls out where the ripple stops
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
