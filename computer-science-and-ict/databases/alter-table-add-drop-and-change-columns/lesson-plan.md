# Lesson plan — ALTER TABLE — add, drop and change columns

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** ALTER TABLE — add, drop and change columns
**Place in the curriculum:** Unit 3 — Database Management System (Ethiopia Grade 12 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** ALTER TABLE changes a table that already exists: add a column, drop a column, or change a column's definition — including fixing a type mismatch and adding a missed primary key.
**This lesson's own level:** it stands on CREATE TABLE: tables exist, and this lesson changes them without rebuilding them.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Add a column, drop a column** — add a column and drop a column on a standing table
2. **Change a column — fixing the type mismatch** — fix the CHAR(15)/CHAR(10) mismatch — direct ALTER COLUMN, or drop and re-add
3. **Add a missed primary key afterwards** — add a missed primary key afterwards: TEACHER's teacher_id

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Creating two linked tables — DEPARTMENT and COURSE. Recommended, never forced.

## What the learner can do when it ends
1. Add and drop a column with ALTER TABLE.
2. Fix a foreign-key type mismatch by altering the column.
3. Add a primary key to an existing table.
4. Say when drop-and-re-add loses data and the direct alter does not.

## What you need
A computer with Microsoft Access (2013 or later), or paper.

## The run of the lesson (in order)
1. **Do it first** — the learner meets the CHAR(15)/CHAR(10) mismatch first and guesses the repair command's name before it is given (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30513]: a picture of a table gaining, losing and resizing columns under three ALTER commands — the student matches each command to its effect.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30513] — add, drop, change under ALTER → the student matches command to effect.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Wants to rebuild the whole table → ALTER exists precisely so a standing table can change; rebuild only when the design itself is wrong.
- Drop-and-re-add chosen for a filled column → its values are dropped with it; use ALTER COLUMN to keep them.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 3 — Database Management System). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
