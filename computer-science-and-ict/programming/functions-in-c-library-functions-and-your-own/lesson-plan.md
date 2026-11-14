# Lesson plan — Functions in C — Library Functions and Your Own

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Functions in C — Library Functions and Your Own
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** functions in C: the library's ready functions (sqrt, pow and their kin, called through headers) and the programmer's own — declared by a prototype, defined once, called from anywhere (Bangladesh HSC ICT, Chapter 5, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Library functions — the borrowed toolbox** — **Library functions** are ready-made functions the language provides: **sqrt** for square roots, **pow** for powers, the string functions of the companion lesson, printf and scanf themselves. They are reached through **headers** — `#include <math.h>` borrows the mathematics toolbox as `<stdio.h>` borrowed input-output. Calling is one pattern everywhere: the function's **name**, the **arguments** in brackets, and the **returned value** used where the call stands: `area = sqrt(x);` — the call is replaced by its answer.
2. **Your own functions — prototype, definition, call** — A **user-defined function** is written in three parts. The **prototype** — `int add(int, int);` — declares the function's name, what it takes and what it returns, so the compiler can check every call. The **definition** holds the body: the work, ending in **return**. The **call** uses it from main or anywhere, as often as needed — write once, use everywhere, fix in one place. Functions divide a program the way chapters divide a book: by their jobs — and the good-structure lesson's readability is mostly this division, done well.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. sqrt and pow (also printf, scanf)
2. <math.h>
3. The name, the arguments, and the returned value used
4. Its answer — the returned value

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — You have called functions since the first program — printf did your printing. This lesson turns the caller into an author: C's programs are built of functions, the library lends hundreds, and the rest you write. The chapter's programs stop being lists and become organisations here. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of library functions — the borrowed toolbox as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of your own functions — prototype, definition, call in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of library functions — the borrowed toolbox → the student studies the picture and names what each part shows
- GIF — a GIF of your own functions — prototype, definition, call in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
