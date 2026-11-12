# Lesson plan — Query criteria — asking for exactly the records you want

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Query criteria — asking for exactly the records you want
**Place in the curriculum:** Unit 3 — Database Management (Ethiopia Grade 11 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** criteria narrow a query to records that match a condition: the condition is typed in the Criteria row under the right field — M under Sex shows only male students — and the criterion must match the stored data exactly.
**This lesson's own level:** it is a doing-lesson, in Access 2010 as the book teaches. It stands on Creating a query in Access — the query exists; this lesson narrows it.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The Criteria row — M under Sex** — open Query Design, add the table, select the display fields, then type the condition in the Criteria row under the right field — entering M under Sex shows only male students
2. **The exact-match warning — and the practice** — the criterion must match the stored data exactly: if sex is stored as a single character, typing the full word returns nothing; the practice includes the Female_Students query

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Creating a query in Access. Recommended, never forced.

## What the learner can do when it ends
1. Build a criteria query in the book's order: Query Design, add the table, select the display fields, type the condition in the Criteria row under the right field.
2. Work the book's example: M under Sex shows only male students.
3. State the exact-match warning: if sex is stored as a single character, typing the full word returns nothing.
4. Name the practice: the Female_Students query.

## What you need
A computer with Microsoft Access (the book teaches Access 2010), with the school database and a Student table holding records.

## The run of the lesson (in order)
1. **Do it first** — the learner writes the question “only the male students” as a condition on paper — field: Sex; value: M — and predicts which records of their own class list will survive it (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 16918]: a picture of a full class list narrowing to only the matching rows as a criterion is typed — the student predicts the surviving rows before checking.
   - ADD GIF [GIF 16919]: the result list shrinking as the criterion lands — the student names the record that disappears at each step.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 16918] — a full class list narrowing to the matching rows → the student predicts the survivors.
- GIF [GIF 16919] — the result list shrinking as the criterion lands → the student names each record that disappears.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Types the criterion in the Field row → conditions go in the Criteria row, under the field they test.
- Gets zero records and thinks the table is empty → check the stored form: single character stored, full word typed, nothing can match.
- Puts the criterion under the wrong field → the criterion tests the field directly above it.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 11 Information Technology, Unit 3 — Database Management). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
