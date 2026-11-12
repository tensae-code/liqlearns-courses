# Lesson plan — DELETE — removing records safely

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** DELETE — removing records safely
**Place in the curriculum:** Unit 3 — Database Management System (Ethiopia Grade 12 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** DELETE removes records but leaves the table's structure standing: choose rows by their primary key, and in a one-to-many relationship delete the many-side records before the one-side record they belong to.
**This lesson's own level:** it stands on UPDATE (DML changes) and on DROP TABLE: DELETE is the careful middle — rows go, the table stays.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **DELETE removes records — the table stands** — DELETE removes records and leaves the structure; targeted or all rows (with/without *); never part of a record
2. **Name the record by its primary key** — name the record by its primary key — repeating fields can cost the wrong record; (teacher guide — evidence) delete-by-ID and delete-all
3. **Delete the many side first** — one-to-many order: many-side records (Students, Teacher, Course) before the one-side department; child deletion does not harm the parent

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: UPDATE — change rows, and never forget WHERE; DROP TABLE — and why it cannot be undone. Recommended, never forced.

## What the learner can do when it ends
1. Delete chosen records while the table stands.
2. Target a record by its primary key.
3. Remove all rows deliberately, knowing the structure remains.
4. Delete many-side records before their one-side record.

## What you need
A computer with Microsoft Access (2013 or later), or paper.

## The run of the lesson (in order)
1. **Do it first** — the learner decides the safe removal order for a closing department before the rule is given (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 30519]: a picture of rows disappearing from a table whose empty structure remains — the student points at what is still standing.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 30519] — rows gone, structure standing → the student names what remains.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Reaches for DROP to remove records → DROP takes the table too; DELETE is the record-only tool.
- Targets by name → names repeat; the primary key is the only identifier that cannot point at two records.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 12 Information Technology, Unit 3 — Database Management System). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
