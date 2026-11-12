# Lesson plan — Queries across multiple tables

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Queries across multiple tables
**Place in the curriculum:** Unit 3 — Database Management (Ethiopia Grade 11 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** a relational database's power is retrieving across tables: add each table with Show Table, join them by dragging the parent table's primary-key field onto the matching field of the child table, pick the display fields from each table, save the query with a name, and view the combined results.
**This lesson's own level:** it is a doing-lesson, in Access 2010 as the book teaches, and the last lesson of this title. It stands on Creating a query in Access, Query criteria, and Primary keys and foreign keys — the drag in this lesson draws the foreign-key link.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Add each table** — open Query Design; add each table with Show Table and the Add button
2. **Drag the key — establish the relationship** — establish the relationship by dragging the primary-key field of the parent table onto the matching field of the child table
3. **Pick fields from each table, save, view** — select the display fields from each table (student name from Student, subject and grade from Grade, teacher name from Teacher); save the query with a name; view the combined results; practice includes students scoring above 85 in all subjects

4. **Grade 12 — selecting from two tables in SQL, and the six-step database project** — Grade 12: SELECT across two linked tables; qualified table.column names; FROM lists both; WHERE equates PK to FK; COURSE+CourseOffering with the Semester='I' filter; (teacher guide — evidence) the six-step project, filed in hands-on

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Creating a query in Access; Query criteria; Primary keys and foreign keys. Recommended, never forced.

## What the learner can do when it ends
1. Add each needed table with Show Table and the Add button.
2. Establish the relationship by dragging the primary-key field of the parent table onto the matching field of the child table.
3. Select the display fields from each table — the example takes student name from Student, subject and grade from Grade, teacher name from Teacher.
4. Save the query with a name and view the combined results.
5. Name the practice: selecting across Student and Grade, including students scoring above 85 in all subjects.

## What you need
A computer with Microsoft Access (the book teaches Access 2010), with the school database and its Student, Teacher and Grade tables holding records.

## The run of the lesson (in order)
1. **Do it first** — the learner lists, for one combined answer — student name, subject, grade, teacher name — which table each field lives in, and sees that no single table can answer the question (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 16920]: a picture of three tables joined by drag-lines in the design window, with one combined result below — the student names the source table of every result column.
   - ADD GIF [GIF 16921]: the primary key being dragged across to make the join line — the student performs the same drag, parent key onto matching child field.
   - ADD IMAGE [Picture 30506]: a picture of two tables with a join line and a combined result table beneath — the student traces one result row back to both its tables.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer, ordering — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 16920] — three tables joined by drag-lines, one combined result below → the student names each column's source table.
- GIF [GIF 16921] — the primary key dragged across to make the join line → the student performs the same drag.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

- IMAGE [Picture 30506] — the join and combined result → the student traces a result row home.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Drags a field that is not the key → the drag starts from the parent table's primary-key field and lands on the matching field of the child.
- Fields missing from the pick list → their table was never added; every needed table must be added with Show Table and Add first.
- Combined rows look multiplied → a join line is missing between a pair of tables; check that every crossed pair is joined.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 11 Information Technology, Unit 3 — Database Management). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
