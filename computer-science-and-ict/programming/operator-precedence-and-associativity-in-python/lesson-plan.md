# Lesson plan — Operator Precedence and Associativity in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Operator Precedence and Associativity in Python
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 11 G11T1 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** operator precedence and associativity in Python — the order in which an expression's parts are worked out (Jordan Grade 11).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Precedence — who goes first** — **Precedence** ranks the operators: brackets first, then powers, then multiplication and division, then addition and subtraction; comparisons and logic sit lower in their own ranks. An expression is worked out by precedence, not by reading order — `2 + 3 * 4` is 14 because the multiplication outranks the addition. Jordan's Python lesson teaches the ladder with the standing advice attached: when the order matters to a reader, **brackets** say it — precedence is for reading code, brackets are for writing it kindly.
2. **Associativity — ties broken by direction** — Operators of **equal precedence** are settled by **associativity**: most work **left to right** (`10 - 4 - 3` = (10−4)−3 = 3), but the power operator works **right to left** (`2 ** 3 ** 2` = 2^(3^2) = 512, not 64). Assignment, too, associates right to left. The pair of rules together — precedence for rank, associativity for ties — decide every expression Python will ever meet, which is why the book drills them before the conditionals that spend them.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The operators — who is worked out first
2. Brackets, then powers, then × and ÷, then + and −
3. Multiplication outranks addition
4. No — by precedence

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Python reads 2 + 3 * 4 as 14, and 10 - 4 - 3 as 3 — never 9. Two rules make those answers inevitable. This lesson learns both. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of precedence — who goes first as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of associativity — ties broken by direction in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of precedence — who goes first → the student studies the picture and names what each part shows
- GIF — a GIF of associativity — ties broken by direction in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
