# Lesson plan — Adding a foreign key with ALTER

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Adding a foreign key with ALTER
**Place in the curriculum:** Unit 3 — Database Management System (Ethiopia Grade 12 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** a relationship can be added after both tables exist: ALTER TABLE … ADD FOREIGN KEY (column) REFERENCES other_table (key) ties the tables through the primary key.
**This lesson's own level:** it stands on ALTER TABLE and on the DEPARTMENT/COURSE pair: both tables exist, and this lesson links them late.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The statement, part by part** — the ALTER … ADD FOREIGN KEY … REFERENCES statement read part by part, with the matching-type rule
2. **When the late link is the right tool** — when a late link is right; (teacher guide — evidence) Grade linked to Student and Teacher by ALTER, combined and separate forms

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: ALTER TABLE — add, drop and change columns. Recommended, never forced.

## What the learner can do when it ends
1. Add a foreign key to an existing table with ALTER.
2. Read the statement's four named parts in order.
3. State that the matching-type rule still applies.

## What you need
A computer with Microsoft Access (2013 or later), or paper.

## The run of the lesson (in order)
1. **Do it first** — the learner lists the four things a late bridge statement must name before seeing the real statement (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30514]: a picture of one ALTER statement drawing a link line between two tables — the student traces the line from foreign key to primary key.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30514] — the ALTER link line → the student traces FK to PK.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Puts the primary key first → the statement alters the table that *holds* the foreign key; REFERENCES names the other table's key.
- The alter is refused → check the types match before blaming the syntax.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 3 — Database Management System). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
