# Lesson plan — Expressions and Arithmetic in Small Basic

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Expressions and Arithmetic in Small Basic
**Place in the curriculum:** ICT expansion — Mongolia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Mongolia's student books (Ministry of Education, Culture and Science(s) of Mongolia, Ulaanbaatar), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Working with expressions and numeric variables in Small Basic — reading a number in with ReadNumber, the arithmetic operators, and operator precedence, the order expressions are worked out in
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Expressions and ReadNumber — values in, values worked** — An **expression** is a written working-out: values and variables joined by operators, which the machine evaluates to a single result. Programs get their starting values from the user with **ReadNumber**, the TextWindow operation that pauses, takes a typed number, and hands it to a variable. Input, then expression, then assignment — `area = side * side` — is the rhythm of every numeric program in the book: read the quantities, work the expression, keep the result.
2. **Operators and precedence — the order of working out** — Small Basic's **arithmetic operators** are the school set: **+ − * /** and the remainder and powers met through the Math object. Joined in one expression they are **not** worked left to right by habit but by **operator precedence**: multiplication and division before addition and subtraction, and **parentheses** above all — the bracketed part is worked first, always. Precedence is the lesson's warning label: `2 + 3 * 4` is 14, not 20, and the programmer who needs 20 must write the brackets and say so.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Mongolia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A written working-out the machine evaluates to a single result
2. Pauses, takes a typed number from the user, and hands it to a variable
3. Read the quantities, work the expression, keep the result
4. +, −, * and /

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A variable that cannot be calculated with is a label, not a tool. Mongolia's next Small Basic section teaches the calculating: expressions, the operators that build them, and the order in which the machine works them out. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of expressions and readnumber — values in, values worked as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of operators and precedence — the order of working out in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of expressions and readnumber — values in, values worked → the student studies the picture and names what each part shows
- GIF — a GIF of operators and precedence — the order of working out in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
