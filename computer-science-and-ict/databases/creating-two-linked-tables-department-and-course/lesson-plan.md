# Lesson plan — Creating two linked tables — DEPARTMENT and COURSE

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Creating two linked tables — DEPARTMENT and COURSE
**Place in the curriculum:** Unit 3 — Database Management System (Ethiopia Grade 12 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** two tables are linked at creation time by giving the foreign-key column the same data type as the primary key it references, and writing REFERENCES after it.
**This lesson's own level:** it stands on CREATE TABLE — building a table with SQL: the same form, now across two tables.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **DEPARTMENT — the one side** — DEPARTMENT built with D_Number CHAR(10) as primary key
2. **COURSE — with the foreign key inside** — COURSE built with C_Department matching D_Number's type and REFERENCES DEPARTMENT(D_Number)
3. **Set the relationship before the data** — the warning: no data before the relationship is set up

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: CREATE TABLE — building a table with SQL. Recommended, never forced.

## What the learner can do when it ends
1. Create DEPARTMENT with D_Number as primary key.
2. Create COURSE with C_Department as a working foreign key.
3. Match a foreign key's type to the primary key it references.
4. State why data waits until relationships are set.

## What you need
A computer with Microsoft Access (2013 or later), or paper.

## The run of the lesson (in order)
1. **Do it first** — the learner lists department and course facts on paper and finds the bridging fact before any SQL is shown (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30512]: a picture of the two CREATE statements above the two empty tables they produce — the student points at the matching CHAR(10) types.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30512] — DEPARTMENT and COURSE statements → the student matches the two CHAR(10) columns.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- The reference is refused → compare the two types character by character; a foreign key and its primary key must share a data type.
- Tempted to type records in first → stop: the book's order is relationship first, data after.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 3 — Database Management System). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
