# Lesson plan — Control Structures in JavaScript

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Control Structures in JavaScript
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How JavaScript's control structures are used in client-side scripting — if…else for choices, for and while for repetition, deciding and repeating inside the page (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Selection — if, else if, else** — JavaScript chooses with **if (condition) { … } else if (condition) { … } else { … }**: the condition sits in **brackets** and is tested as true or false, the chosen branch's **braces** run, and the rest are skipped. Conditions are built with comparisons (==, !=, >, <, >=, <=) and joined with logical operators (&& for AND, || for OR, ! for NOT). Client-side, the choices are the page's judgements: which message a form answer earns, which menu a visitor's level opens.
2. **Repetition — for and while in the page** — JavaScript repeats with **for** — for (let i = 1; i <= 5; i++) { … } gathers start, test and step in one line, for a count known in advance — and **while** — while (condition) { … } repeats until its test fails, for a count known only by the running. The loop's **body must move the test toward ending** (i++ inside the for's line; the change written inside a while's body), or the page hangs in an endless loop — the browser's most public fault. Malaysia's scripts use the pair for the page's repetitive work: listing items, checking each field of a form, totalling a column of marks.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. if … else if … else — condition in brackets, branches in braces
2. ==, !=, >, <, >=, <=
3. && (AND), || (OR), ! (NOT)
4. for: a count known in advance; while: a count known only by the running

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A script that only runs top to bottom can greet, but cannot judge or repeat. Malaysia's JavaScript chapter gives the page its choices and loops. In this lesson you use if…else and the loops in client-side scripts — the structures of every earlier language, wearing JavaScript's dress. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of selection — if, else if, else as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of repetition — for and while in the page in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of selection — if, else if, else → the student studies the picture and names what each part shows
- GIF — a GIF of repetition — for and while in the page in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
