# Lesson plan — Comments in C — Single-Line and Multi-Line

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Comments in C — Single-Line and Multi-Line
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** comments in C: the notes a programmer leaves inside the code — // for one line, /* … */ for many — ignored by the compiler, written for the humans (Bangladesh HSC ICT, Chapter 5, §5.6).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Two shapes — // and /* */** — A **single-line comment** begins with **//** and runs to the line's end: `// read the marks` — the margin note, for one statement's reason. A **multi-line comment** opens with **/\*** and closes with **\*/** and may span many lines — the paragraph at a function's head, the licence, the explanation of a hard algorithm. Both are removed before compilation as surely as Python's # comments (the comments lessons of other languages agree on the purpose while differing in dress): the machine never sees them.
2. **Writing comments that earn their place** — A good comment says **why**, or what the code below must never break — never merely repeats the code in words ('add 1 to i' above `i = i + 1` is noise wearing a comment's coat). Comments also carry the working programmer's second tool: **commenting out** — wrapping a troublesome block in /* … */ to silence it while debugging, instead of deleting what may be innocent. And a rotten comment is worse than none: a note that lies about the code below it will be believed once, at the worst moment — so comments are maintained like code, changed when the code changes, or struck out with it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. //
2. To the end of the line
3. /* and */
4. No — they are removed before compilation

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The compiler ignores them completely. Your future self, reading the program in six months, will bless or curse you by them. Comments are the part of a C program written entirely for people — and C gives them two shapes, one for the margin note and one for the whole paragraph. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of two shapes — // and /* */ as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of writing comments that earn their place in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of two shapes — // and /* */ → the student studies the picture and names what each part shows
- GIF — a GIF of writing comments that earn their place in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
