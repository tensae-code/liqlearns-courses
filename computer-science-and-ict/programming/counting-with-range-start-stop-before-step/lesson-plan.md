# Lesson plan — Counting with range() — start, stop-before, step

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Counting with range() — start, stop-before, step
**Place in the curriculum:** Unit 6 — Fundamentals of Programming (CURRICULUM.md).
**The one thing this lesson teaches:** One, two or three parameters: range(5) gives 0–4; range(2, 5) gives 2–4; range(1, 10, 2) gives 1, 3, 5, 7, 9. The end is always excluded.
**This lesson's own level:** it stands on the Grade 11 Python lessons and the earlier Grade 12 Unit 6 lessons — the learner can already write, save and run a Python program in IDLE. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved (the gate: README, "Units, Lessons and Sub Lessons (ruled 2026-11-08)"):

1. **The three forms of range()** — One, two or three parameters: range(5) gives 0–4; range(2, 5) gives 2–4; range(1, 10, 2) gives 1, 3, 5, 7, 9. The end is always excluded.
2. **Keyboard input is text — cast with int() first** — Anything typed arrives as a string; int() converts it to a number range() can use. Counting ranges in practice: 51 to 70; steps of 10.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Loops — and the for loop over a sequence. Recommended, never forced.

## What the learner can do when it ends
1. Give the values of all three range() forms, end excluded.
2. Explain why keyboard input must pass through int() before range().
3. Write ranges for 51–70 and for tens to 100.

## What you need
A computer with Python and IDLE installed (or an online Python editor), paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — the learner runs or traces the lesson's opening program before any explanation (lesson/lesson.md).
2. **The explanation** — the sub lessons in order (lesson/lesson.md).
   - ADD - IMAGE [Picture 31708]: a picture of three number lines, one per range form, with the end number faded as not included — the student studies the picture and names what it shows before reading on.
   - ADD - GIF [GIF 31724]: a moving picture of a counter stepping along a number line, stopping before the last number — the student watches the motion and says what changed at each stage.
   - ADD - GIF [GIF 31731]: a moving picture of a counter adding 1 again and again inside a loop arrow until it reaches its target — the student watches the motion and says what changed at each stage.
   - ADD - AUDIO: a voice reading this lesson's key words and one worked run aloud — the student listens and repeats the key words.
   - ADD - VIDEO: the script in video-script.md, filmed (made later) — the student follows the doing along with it.
3. **Say it to your companion** — Explain stop-before to your companion with the GIF: the counter climbs and halts before the end number — then say why counting TO a typed number needs n + 1.
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- - IMAGE [Picture 31708]: a picture of three number lines, one per range form, with the end number faded as not included — the student studies the picture and names what it shows before reading on.
- - GIF [GIF 31724]: a moving picture of a counter stepping along a number line, stopping before the last number — the student watches the motion and says what changed at each stage.
- - GIF [GIF 31731]: a moving picture of a counter adding 1 again and again inside a loop arrow until it reaches its target — the student watches the motion and says what changed at each stage.
- - AUDIO: a voice reading this lesson's key words and one worked run aloud — the student listens and repeats the key words.
- - VIDEO: the script in video-script.md, filmed (made later) — the student follows the doing along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten. Audio and video are described slots in this build: no audio files are made, and filming is later.

## If the learner is stuck
- The program errors before it runs → check the syntax first: colon present, indentation even, brackets closed. Most faults in this unit live there.
- The program runs but the output is wrong → predict the output line by line with a trace table, then compare with the real run; the first line that differs is where the fault lives.
- This lesson's neighbours are the other Unit 6 Programming lessons, in the unit's order.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
