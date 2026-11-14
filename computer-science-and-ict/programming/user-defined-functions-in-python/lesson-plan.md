# Lesson plan — User-Defined Functions in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** User-Defined Functions in Python
**Place in the curriculum:** ICT expansion — Nepal (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Nepal's *Computer Science, Class 10*, because no existing lesson teaches Python's user-defined functions as its own lesson.
**The one thing this lesson teaches:** a programmer can build their own function in Python — write a named block of code once with `def`, then call that name wherever the job is needed, giving values in through parameters and getting a result back through `return`.
**This lesson's own level:** It stands on being able to write and run a short Python script; the `def` block, the call, parameters and `return` are built inside the lesson from Unit 4 §4.2 of Nepal's book.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Writing your own function with `def`** — A function is a named block of code written once with the `def` line and an indented body; it does nothing until its name is called, and then it runs as many times as it is called.
2. **Values in, a result back — parameters and `return`** — Parameters are the named slots a value is handed in through at each call; `return` hands a result back to the place that called, where it can be stored and used.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Writing and Running a Python Script in Programming. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Nepal's own way is kept: in Nepal's book user-defined functions (§4.2) come straight after the revision of Python basics and before libraries — first the functions you write yourself, then the ready-made code other people wrote.

## What the learner can do when it ends
1. Say what a user-defined function is and how it differs from a built-in function like `print`.
2. Write a function with `def`, an indented body, and call it by name.
3. Write a function that takes parameters and call it with different values.
4. Use `return` to hand a result back and store it in a variable.

## What you need
A computer with Python (or paper for the first writing — the code is short enough to write and trace by hand before it is run).

## The run of the lesson (in order)
1. **Do it first** — In every program so far, the same few lines keep coming back: greet the user, check a number, work out a total. Imagine copying those lines in ten places — and then finding a mistake in them. This lesson teaches the way out: write the job once, give it a name, and call the name. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a Python function drawn as a labelled machine: the `def` line as its name plate, the indented body as the works inside, an arrow marked "call" going in and an arrow marked "return" coming out — the student points to each part and says its job.
   - ADD IMAGE: a picture of one function called three times with three different values going in, and three results coming back — the student traces one call from its values to its result and says what stayed the same (the body) and what changed (the values).
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a Python function drawn as a labelled machine, with "call" going in and "return" coming out → the student points to each part and says its job.
- IMAGE — a picture of one function called three times with different values and three results → the student traces one call and says what stayed the same and what changed.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Writes a function but nothing happens → defining is not calling: the `def` block only teaches Python the name; the function runs when its name is called. Forgets the indentation → the body must be indented under the `def` line; Python reads the indentation as 'inside the function'. Expects a printed value to be usable later → `print` shows a value and throws it away; `return` hands it back so it can be stored and used.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
