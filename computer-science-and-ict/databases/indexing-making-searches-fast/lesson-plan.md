# Lesson plan — Indexing — Making Searches Fast

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Indexing — Making Searches Fast
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** indexing: the database's index — a sorted lookup structure that lets the DBMS find records without reading the whole table — named among the DDL commands and practised in the exercises of Bangladesh's HSC database chapter (Chapter 6, printed pp. 198 and 211; no dedicated taught section — recorded as filed).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The index — a book's index inside the database** — An **index** is a separate, sorted structure the DBMS keeps beside a table: for an indexed field it holds each value in order, with a pointer to the record that carries it. Searching by that field then works like a book's index — look the value up in the sorted list, follow the pointer, done — instead of a **full table scan**, reading every record to find the few that match. The wider the table grows, the more the index earns: on ten records it is nothing; on ten million it is the difference between instant and unusable.
2. **The price of the index — and choosing fields** — An index is not free: it takes **storage**, and every INSERT, UPDATE and DELETE must update the index too, so writes grow slower as indexes multiply. The designer's craft is choosing: index the fields searches actually use — the key, the name looked up daily — and leave the rest unindexed. Bangladesh's exercises practise exactly this judgement on school-sized tables, where the principle can be seen whole before the tables grow beyond seeing.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A sorted lookup structure kept beside a table
2. A value in order, with a pointer to its record
3. A full table scan — reading every record
4. On very large tables

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Find one name in a thousand-page book with no index and you will read for an hour. With the index, ten seconds. A database with a million records has the same problem at machine speed — and the same answer, which this lesson teaches. Honesty first: Bangladesh's book names indexing inside its DDL command list and practises it in exercises rather than teaching it in its own section; the lesson is built from that naming and that practice. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the index — a book's index inside the database as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the price of the index — and choosing fields in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the index — a book's index inside the database → the student studies the picture and names what each part shows
- GIF — a GIF of the price of the index — and choosing fields in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
