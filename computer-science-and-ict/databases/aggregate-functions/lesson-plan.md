# Lesson plan — Aggregate Functions in SQL

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Aggregate Functions in SQL
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How SQL's aggregate functions work — COUNT, SUM, AVG, MAX and MIN summarise a whole column of records into one answer (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Five functions, one answer each** — An **aggregate function** takes a **whole column across many records** and returns **one value**. **COUNT** counts records (COUNT(*) counts records; COUNT(column) counts its non-empty values). **SUM** totals a numeric column; **AVG** averages it; **MAX** and **MIN** return its largest and smallest values. Written in a SELECT, the aggregate replaces the record list: SELECT COUNT(*) FROM Pupil; answers a single number — the size of the whole table — not a page of rows.
2. **Aggregates with conditions and groups** — Aggregates answer about **chosen records** when a WHERE clause selects them first (SELECT AVG(Mark) FROM Result WHERE Subject = 'Maths';), and about **each group separately** with **GROUP BY** (SELECT Class, AVG(Mark) FROM Result GROUP BY Class; gives one average per class). Malaysia's order of reading keeps the machine's order honest: the records are chosen, then grouped, then each group is summarised. The common fault is expecting both the summary and the records from one plain SELECT — an aggregate query returns summaries; the records stay in the table.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A whole column across many records — and one value back
2. Records
3. SUM totals a numeric column; AVG averages it
4. A WHERE clause selects the records first

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Most SQL questions ask for records. Some ask for one number about all the records: how many, how much in total, what average. Malaysia's advanced SQL chapter gives those questions their own functions. In this lesson you summarise with COUNT, SUM, AVG, MAX and MIN. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of five functions, one answer each as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of aggregates with conditions and groups in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of five functions, one answer each → the student studies the picture and names what each part shows
- GIF — a GIF of aggregates with conditions and groups in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
