# Lesson plan — Handling Input Errors with Try and Except

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Handling Input Errors with Try and Except
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Checking input before the program trusts it.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Validate first — check before you trust** — **Validation** checks input **before** the program trusts it: is something there at all, is it the right **kind** (a number, where a number is needed), is it in the allowed **range**? Each failed check earns a **clear message** and another chance — 'Marks run from 0 to 100; you typed 140' teaches; a silent wrong answer corrupts. Egypt places this in the same lesson as error handling because the two are one discipline: most input errors should never become program errors at all, caught at the door by checks written from knowing exactly what the program needs.
2. **Try and except — when the error still comes** — Some errors survive validation — a conversion that fails, a file that is not there — and Python's answer is **try/except**: the risky lines go in the **try** block; if one raises an error, Python jumps to the **except** block instead of crashing, and the program responds — a message, a default, another attempt — and continues. The craft is aim: wrap the **few lines** that can fail, name the **specific** error where you can, and never let an except block swallow a fault silently, or real bugs will hide inside it. Egypt's Grade 9 book teaches this to pupils whose other error lesson is the IDLE debugger — the pair is complete: the debugger finds the program's faults; try/except survives the user's.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Checking input before the program trusts it.
2. Something is there, it is the right kind, and it is in the allowed range.
3. Respond — a message, a default, another attempt — and let the program continue.
4. The few lines that can fail — no more.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 9 input lesson is not about the debugger — it is about the user. People type letters where numbers belong, leave fields empty and paste the wrong thing, and a program that crashes on the first surprise is unfinished. This lesson teaches validation and Python's try/except: expecting the error, catching it, and answering it like a host instead of a trapdoor. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of validate first — check before you trust as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of try and except — when the error still comes in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of validate first — check before you trust → the student studies the picture and names what each part shows
- GIF — a GIF of try and except — when the error still comes in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
