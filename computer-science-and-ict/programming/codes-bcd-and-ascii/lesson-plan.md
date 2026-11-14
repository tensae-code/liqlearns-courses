# Lesson plan — Codes — BCD and ASCII

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Codes — BCD and ASCII
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** A code is an agreed way of writing something in bits: BCD writes each decimal digit separately in four bits, and ASCII gives every letter, digit and sign a fixed 7-bit number, so machines can store and exchange numbers and text the same way everywhere.
**This lesson's own level:** It stands on the number-systems lesson just before it in Montenegro's climb — bases, bits and conversions. A learner who lands here directly is told in the lesson itself how BCD and ASCII patterns are read, so it stands alone.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The BCD code — each decimal digit in four bits** — BCD (binary-coded decimal): instead of converting the whole number to binary, each decimal digit is written separately as a four-bit binary group. 47 becomes 0100 0111. Six four-bit patterns (1010 to 1111) are never used. Where BCD is used: displays, measuring instruments and money amounts, where each decimal digit matters on its own.
2. **The ASCII code — every character its own number** — ASCII (American Standard Code for Information Interchange): every letter, digit and sign is given a fixed 7-bit code — 128 characters in all. Capitals run from A = 65, small letters from a = 97, the digit characters from '0' = 48; the space is 32. Because the code is a standard, text written on one machine reads the same on another.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Number Systems and Conversions, the lesson before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. Say what a code is, and write a decimal number in BCD, four bits per digit.
2. Name the six four-bit patterns BCD never uses, and say where BCD is used and why.
3. Say what ASCII is, and find the ASCII code of a character from its runs (space 32, '0' = 48, A = 65, a = 97).
4. Read a short word given as ASCII numbers back into letters, and say why the character '5' is not the number 5.

## What you need
Paper and a pencil. An ASCII table copied from this lesson is the working tool for the hands-on part.

## The run of the lesson (in order)
1. **Do it first** — A shop till shows the price 47. A letter on your screen is the letter K. A computer cannot store '47' or 'K' as you see them — inside, there are only bits. So how does the machine know which bits mean a number, and which mean a letter? This lesson answers with two agreed codes. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the number 47 splitting into its two digits, each digit becoming its own four-bit BCD group, beside the plain binary of 47 written whole — the student writes the BCD of a price of their own choosing and reads it back digit by digit.
   - ADD IMAGE: a picture of a strip of the ASCII table — space, digit characters, capitals, small letters — with the word Cat picked out in colour — the student finds the codes for their own first name in the strip and writes the name as ASCII numbers.
   - ADD GIF: a GIF of the letters of a word lighting up one by one as their ASCII numbers appear under them, turning into bits — the student watches, then does the same for a two-letter word on paper before checking the table.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the number 47 splitting into its two digits, each digit becoming its own four-bit BCD group, beside the plain binary of 47 written whole → the student writes the BCD of a price of their own choosing and reads it back digit by digit.
- IMAGE — a picture of a strip of the ASCII table — space, digit characters, capitals, small letters — with the word Cat picked out in colour → the student finds the codes for their own first name in the strip and writes the name as ASCII numbers.
- GIF — a GIF of the letters of a word lighting up one by one as their ASCII numbers appear under them, turning into bits → the student watches, then does the same for a two-letter word on paper before checking the table.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Writes the whole number's binary and calls it BCD → BCD never converts the whole number: split into decimal digits first, then four bits for each digit, keeping the leading zeros inside each group. Reads the character '5' as the value 5 → a character is a picture with a code number; '5' is code 53, and only becomes the value 5 when the program decides to use it as one.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
