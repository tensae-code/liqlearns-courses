# Lesson plan — Creating a Database in MySQL

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Creating a Database in MySQL
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A database server — a program that holds data and answers other programs' requests.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **MySQL — a database server, not a file** — **MySQL** keeps a database on a **server**: a program that holds the data, answers requests from other programs, and guards who may do what. That is the step up from a desktop database file — the project's website and its database are different programs talking to each other, the PHP pages asking, MySQL answering. Creating begins with the **database itself** — a named container for this project's data — made with the server's tools (the book works through the local server stack's control panels), before any table exists: container first, furniture after.
2. **Tables for the dictionary — fields, types, the key** — Inside the new database, the project's **table** is created column by column: for the Illustrated Dictionary, the term, its meaning, and its illustration reference — each column given a **type** (text for the term and meaning, a number where a number belongs) and a length that fits real entries. One column is made the **primary key** — the identifier no two terms may share — so every entry can be found, edited and deleted exactly. Egypt teaches creation inside a live project for a reason: every choice (a too-short text field, a missing key) is paid for later by the Add_Term page that must write into this table, so the table is designed from the page's needs backwards.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A database server — a program that holds data and answers other programs' requests.
2. The website and the database are different programs talking to each other.
3. So every entry can be found, edited and deleted exactly.
4. From the Add_Term page's needs, backwards.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 11 website project needs somewhere real for its dictionary of computer terms to live. After the database idea itself, the book creates the project's database in MySQL — the database server that works beside PHP in the classic school stack — and this lesson teaches that creation as its own skill. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of mysql — a database server, not a file as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of tables for the dictionary — fields, types, the key in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of mysql — a database server, not a file → the student studies the picture and names what each part shows
- GIF — a GIF of tables for the dictionary — fields, types, the key in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
