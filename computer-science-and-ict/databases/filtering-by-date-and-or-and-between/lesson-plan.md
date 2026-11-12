# Lesson plan — Filtering by date, AND, OR and BETWEEN

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Filtering by date, AND, OR and BETWEEN
**Place in the curriculum:** Unit 3 — Database Management System (Ethiopia Grade 12 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** WHERE grows up: dates compare chronologically (>= includes its start date), AND demands both criteria, OR accepts either, and BETWEEN … AND takes the whole inclusive range.
**This lesson's own level:** it stands on choosing columns and filtering with WHERE (the Grade 12 growth of Query criteria): single tests are known; this lesson combines and ranges them.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Dates compare in time order** — dates compare chronologically; >= includes the start date (sales on and after 15 March 2020)
2. **AND narrows, OR widens** — AND: after 1 May 2020 and over 12,000 — one match; OR: under 1,000 or over 15,000 — four matches
3. **BETWEEN — the inclusive range** — BETWEEN … AND: an inclusive range, both endpoints kept

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Query criteria — asking for exactly the records you want (grown with chosen columns and WHERE). Recommended, never forced.

## What the learner can do when it ends
1. Filter by date with the boundary stated correctly.
2. Combine criteria with AND and OR and predict the direction of the count.
3. Use BETWEEN … AND for inclusive ranges.
4. Express a BETWEEN as two AND-joined comparisons.

## What you need
A computer with Microsoft Access (2013 or later), or paper.

## The run of the lesson (in order)
1. **Do it first** — the learner hand-filters a ten-row sales list for four hunts before the new keywords are named (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30522]: a picture of a sales table shrinking step by step as each filter is applied — the student counts the surviving rows per filter.
   - ADD GIF [GIF 30533]: rows dimming as the OR filter applies — the student names the row that drops out and why.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30522] — the shrinking sales table → the student counts survivors per filter.
- GIF [GIF 30533] — rows dimming as filters apply → the student names the dropped row.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Loses the boundary day → >= keeps it, > drops it; say 'on and after' vs 'strictly after' before writing.
- Expects OR to narrow → OR accepts either side, so its catch is the *union* — always at least as wide as each side alone.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 3 — Database Management System). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
