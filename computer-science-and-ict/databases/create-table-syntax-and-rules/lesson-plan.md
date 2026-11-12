# Lesson plan — CREATE TABLE — building a table with SQL

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** CREATE TABLE — building a table with SQL
**Place in the curriculum:** Unit 3 — Database Management System (Ethiopia Grade 12 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** CREATE TABLE builds a table from a written statement: name the table, list each column with its data type in parentheses, mark the primary key, and reference other tables' keys where a column links.
**This lesson's own level:** it stands on SQL's families (this is DDL at work) and on choosing a data type for each field.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The general form** — the general form — table name, columns with types in parentheses, optional PRIMARY KEY and REFERENCES
2. **The rules that keep it valid** — the rules — name+type per column, commas, DBMS type differences, sized fields cutting silently, no spaces in field names, semicolon good practice
3. **Worked builds and broken SQL (teacher guide — evidence)** — (teacher guide — evidence) the worked Student/Teacher/Grade builds, type sizing from real values, and diagnosing three broken CREATE statements

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: SQL — DDL, DML and DQL; Choosing a data type for each field (inside Creating a table and entering records in Access). Recommended, never forced.

## What the learner can do when it ends
1. Write a valid CREATE TABLE with a primary key.
2. Apply the comma, naming and sizing rules.
3. Size a text field from the longest real value and say why account numbers are text.
4. Diagnose the three classic broken-CREATE faults.

## What you need
A computer with Microsoft Access (2013 or later), or paper for the written builds.

## The run of the lesson (in order)
1. **Do it first** — the learner designs a bookshop table on paper first; the lesson turns that plan into the written command (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30511]: a picture of a CREATE TABLE statement with table name, columns, types and primary key colour-coded — the student reads each colour's part aloud.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30511] — the colour-coded CREATE TABLE → the student names what each part does.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Access rejects the statement → check in order: the word TABLE present? a comma between every pair of columns? brackets closed? REFERENCES spelt right?
- A long name comes out cut → the field was sized too small; a sized field keeps only its first N characters.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 3 — Database Management System). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
