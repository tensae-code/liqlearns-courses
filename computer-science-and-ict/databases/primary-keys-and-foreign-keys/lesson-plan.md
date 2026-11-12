# Lesson plan — Primary keys and foreign keys

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Primary keys and foreign keys
**Place in the curriculum:** Unit 3 — Database Management (Ethiopia Grade 11 Information Technology), in the Databases title of the Computer Science and ICT course. The ladder is the recommended order, never a forced one.
**The one thing this lesson teaches:** every table has a primary key — a field whose value is unique for each record — and tables are joined through foreign keys: an attribute in one table that matches the primary key of a related table.
**This lesson's own level:** it stands on The relational data model: relations are on the table, and this lesson names the fields that identify each row and link the tables.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Primary keys — the field that never repeats** — a relational database is a set of logically related tables; every table has a primary key — a field whose value is unique for each record, such as a student ID no two students can share
2. **Foreign keys — the matching field in the other table** — a foreign key is an attribute in one table that matches the primary key of a related table; tables are navigated and joined through foreign keys
3. **The book-loan table — both keys at work** — the student ID and book ID inside the book-loan table link it to the student and book tables

4. **Grade 12 — Sid in a five-table school database, and the popular RDBMSs** — Grade 12: the five-table school database; Sid unique as Students' primary key, repeating as MarkList's foreign key; the popular RDBMS list — with the guide's MongoDB listing corrected (NoSQL, not an RDBMS)

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: The relational data model — tables of rows and columns. Recommended, never forced.

## What the learner can do when it ends
1. Say what a relational database is: a set of logically related tables, built with relational DBMS software (RDBMS).
2. Define a primary key and give the student ID example: a value unique for each record, that no two students can share.
3. Define a foreign key: an attribute in one table matching the primary key of a related table.
4. Follow the book-loan table: its student ID and book ID link it to the Student and Book tables.

## What you need
Paper and a pencil. Nothing else.

## The run of the lesson (in order)
1. **Do it first** — the learner writes three student rows with the same first name in two of them, then finds the one column that can still tell every row apart (lesson/lesson.md).
2. **The explanation** — the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 16910]: a picture of three tables — Student, Book, Book_Loan — with key fields marked and linking lines drawn — the student traces one loan row to its student and its book.
   - ADD GIF [GIF 16911]: a loan row lighting up its student row and its book row through the foreign keys — the student names each key as it lights.
   - ADD IMAGE [Picture 30503]: a picture of two tables joined by a highlighted shared key field, one side marked unique, the other many — the student says where Sid is unique and where it repeats.
3. **Say it to your companion** — explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the lesson retold in the super-simple voice (made later, when videos are made).
   - ADD AUDIO: a voice reading the lesson's key words and steps aloud — the student listens and says, or does, each one after the voice.
4. **Questions** — from questions/: multiple-choice, true-or-false, short-answer, fill-in-the-blank — served at the learner's level (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 16910] — Student, Book and Book_Loan with keys marked and links drawn → the student traces a loan through both keys.
- GIF [GIF 16911] — a loan row lighting up its student row and book row → the student names the foreign keys as they light.
- AUDIO — a voice reading the lesson's key words and steps aloud → the student listens and repeats, or does each step.
- VIDEO — the video-script filmed (made later) → the student watches and follows along.

- IMAGE [Picture 30503] — Sid on both sides of the link → the student names the key kind per side.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Picks name as the key → names repeat; a primary key's value must be unique for each record.
- Thinks a foreign key must be unique too → a foreign key repeats freely (one student, many loans); it must only *match* the other table's primary key.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 11 Information Technology, Unit 3 — Database Management). Doing-lessons in this course are marked by watching the doing, as the teacher guide directs, not by a written key alone. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
