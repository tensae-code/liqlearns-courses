# Lesson plan — Using the cmath Library

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Using the cmath Library
**Place in the curriculum:** ICT expansion — North Macedonia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from North Macedonia's *Informatics* (2026), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** The cmath library gives C++ programs ready-made mathematical functions — sqrt for square roots, pow for powers, the rounding and absolute-value functions and more — used by including the header and calling the function with its value in brackets, receiving the result as the call's value.
**This lesson's own level:** It stands on the earlier lessons of its title and on the North Macedonia book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Including and calling** — Library functions arrive through a **header**: `#include <cmath>` at the top makes them available. A call looks like any function call — **sqrt(81)** has the value **9** wherever it is written, so it can be stored, printed or built into a bigger expression. The functions work on decimal (double) values and return doubles.
2. **The working set** — The book's working set: **sqrt(x)** square root; **pow(x, y)** x raised to the power y; **abs / fabs** absolute value; **floor** and **ceil** rounding down and up; **round** to nearest; and the trigonometric family (sin, cos, tan — in **radians**). Using the library instead of hand-writing these is the modular habit applied: tested once by the library's makers, reused by everyone.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- North Macedonia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. #include <cmath> at the top.
2. Stored, printed, or inside a bigger expression.
3. x raised to the power y.
4. Rounds to the nearest whole value.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — You do not have to build a square-root machine before you may use one. This lesson opens the toolbox the language already built for you. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of including and calling as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the working set in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of including and calling → the student studies the picture and names what each part shows
- GIF — a GIF of the working set in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
