# Lesson plan — Reading Input With scanf and Printing With printf

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Reading Input With scanf and Printing With printf
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** scanf and printf: C's input and output pair — printf prints values through format specifiers, scanf reads typed values into variables through their addresses — with escape sequences, and the Celsius-to-Fahrenheit program as the worked whole (Bangladesh HSC ICT, Chapter 5, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **printf — printing with format** — **printf** prints text and values together: the **format string** carries ordinary words, **format specifiers** (%d, %f, %c — the data-types lesson's promises) where values go, and **escape sequences** for what keyboards cannot type directly — **\n** for a new line, **\t** for a tab. The values follow the string in order, one per specifier: `printf("Marks: %d\n", marks);`. What the user sees — labels, spacing, new lines — is entirely the programmer's courtesy, designed here and nowhere else.
2. **scanf — reading into addresses; and the worked program** — **scanf** reads the user's typed values **into variables** — and its famous peculiarity is the **&**: `scanf("%d", &age);` passes the variable's **address**, because scanf must *put* the value somewhere, not merely look at it. Forgetting the & is the C beginner's rite of passage. The book's worked whole joins the pair: read a **Celsius** temperature with scanf, compute **Fahrenheit = (C × 9/5) + 32**, print the answer with printf — input, process, output in C dress, and the template of every HSC program that follows.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Words, format specifiers and escape sequences
2. Starts a new line
3. Moves to a tab stop
4. In order, one per specifier

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A program that only prints its author's greeting is a poster. Give it scanf and it becomes a conversation: it asks, the user answers, it computes, printf reports. This lesson teaches the pair together, because in C they are one craft with two directions. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of printf — printing with format as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of scanf — reading into addresses; and the worked program in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of printf — printing with format → the student studies the picture and names what each part shows
- GIF — a GIF of scanf — reading into addresses; and the worked program in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
