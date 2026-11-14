# Lesson plan — Numbers in Pascal and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Numbers in Pascal and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How numbers are written in the two languages: integer and real constants, decimal and (in C++) other bases, exponent form — the exact writing rules a compiler accepts (Moldova Grade 10, Informatică, §1.5.3).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Integer constants — whole writings** — An **integer constant** is a whole number written with digits and an optional sign: 42, −7, +1000. No spaces or commas may interrupt it — 1 000 is two constants, not one. Pascal writes integers in **decimal** only. C++ adds writings by base: a leading **0** means octal (017 = 15), **0x** means hexadecimal (0x1F = 31) — the same value in other clothes, useful where bits matter. A constant's form announces its reading before its value is computed.
2. **Real constants — the point and the exponent** — A **real constant** carries a fractional part or an exponent: 3.14, 0.5, and the exponent forms 2.5E3, 1.2E−4 — the letter E reads 'times ten to the power'. The decimal separator is a **point**, never a comma, in both languages: 3,14 is a syntax error, not a number. A constant with a point or an E is **real-typed**; without, integer-typed — the writing decides the type before any operation touches it, the fact the type-of-expression lessons will spend.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Digits with an optional sign — 42, −7, +1000
2. Spaces may not interrupt a constant — it reads as two
3. Octal and hexadecimal — 017 = 15, 0x1F = 31
4. No — decimal only, in this course's writing

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A number on paper is forgiving; a number in a program is judged character by character. Grade 10's vocabulary chapter gives the writing of numeric constants its own section in both languages. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of integer constants — whole writings as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of real constants — the point and the exponent in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of integer constants — whole writings → the student studies the picture and names what each part shows
- GIF — a GIF of real constants — the point and the exponent in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
