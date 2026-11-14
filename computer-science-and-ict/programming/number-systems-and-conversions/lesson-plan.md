# Lesson plan — Number Systems and Conversions

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Number Systems and Conversions
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A number system is fixed by its base — how many different digits it uses — and every value is built from place values that are powers of that base: decimal counts in tens, binary in twos, hexadecimal in sixteens, and any value can be converted from one system to another without changing what it means.
**This lesson's own level:** It stands on ordinary counting and on place value from school mathematics — hundreds, tens and ones. Nothing electronic is needed before it; it is the first step of Montenegro's climb, the language everything else in the book is written in.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Decimal, binary and hexadecimal — bases and place values** — What a number system is: its base (radix) and its digits. Decimal (base 10, digits 0–9), binary (base 2, digits 0 and 1 — the bits a computer works with), hexadecimal (base 16, digits 0–9 and letters A–F). In every system the value of a written number is the sum of each digit times its place value, and the place values are powers of the base: in binary 1, 2, 4, 8, 16…; in hexadecimal 1, 16, 256…
2. **Converting between the systems** — Binary to decimal by adding place values; decimal to binary by repeated division by 2 (remainders read backwards) or by taking away the largest power of two; binary to hexadecimal by grouping the bits in fours from the right; hexadecimal to binary by writing four bits for each digit; decimal to hexadecimal by repeated division by 16.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the First Steps lessons on data and on digital computers (data as digits) in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Name the base and the digits of the decimal, binary and hexadecimal number systems.
2. Work out the decimal value of a binary or hexadecimal number from its place values.
3. Convert a decimal number into binary by repeated division by 2, and check by converting back.
4. Convert between binary and hexadecimal by grouping bits in fours.

## What you need
Paper and a pencil. A calculator that shows hexadecimal is a help but not a need — every conversion in this lesson is done by hand so the method is seen.

## The run of the lesson (in order)
1. **Do it first** — Write the number 2026. Now say what each digit is worth: the 2 on the left is worth two thousand, the last 6 only six. The digit is the same kind of mark — its place gives it its worth. Keep that thought: this lesson shows that base ten is only one way of giving places their worth. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the same value written in decimal, binary and hexadecimal, with the place values 1, 2, 4, 8 over the binary digits and 1, 16 over the hexadecimal digits — the student points at each place and says what that digit is worth in each system.
   - ADD GIF: a GIF of the repeated division of 22 by 2, the remainders appearing one by one and then flipping backwards into the binary answer 10110 — the student watches once, then does the same division for a new number on paper, flipping the remainders the same way.
   - ADD IMAGE: a picture of a long binary number being split into groups of four bits with string, each group turning into one hexadecimal digit — the student draws the groups of four on a binary number of their own and writes the hexadecimal digits under them.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the same value written in decimal, binary and hexadecimal, with the place values 1, 2, 4, 8 over the binary digits and 1, 16 over the hexadecimal digits → the student points at each place and says what that digit is worth in each system.
- GIF — a GIF of the repeated division of 22 by 2, the remainders appearing one by one and then flipping backwards into the binary answer 10110 → the student watches once, then does the same division for a new number on paper, flipping the remainders the same way.
- IMAGE — a picture of a long binary number being split into groups of four bits with string, each group turning into one hexadecimal digit → the student draws the groups of four on a binary number of their own and writes the hexadecimal digits under them.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Counts in binary as if the places were tens → write the place values 1, 2, 4, 8 over the digits first, every time, until the hand does it alone. Reads the division remainders forwards → the first remainder is the LAST bit; circle the remainders and read them in the arrow's direction. Mixes up the hexadecimal letters → A is ten, and the letters simply continue the counting where the digits ran out.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
