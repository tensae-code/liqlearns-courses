# Lesson plan — Designing a Relational Database

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Designing a Relational Database
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How a relational database is designed — from the need, through entities, attributes and keys, to the tables of the design (Malaysia, Tingkatan 4)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **From the need to entities and attributes** — Design starts from the **need**: what the database must hold and what questions it must answer. From the need, the designer names the **entities** — the kinds of thing the database is about (Pupil, Book, Loan) — and each entity's **attributes**, the facts kept about it (Pupil: name, class, date of birth). An attribute belongs in the design only if the need asks for it: design is the need, written as structure — every table and column in the finished database should be traceable back to a question it must answer.
2. **Keys, relationships, and the tables** — Each entity is given a **primary key** — the attribute (or added ID) that picks out one record from all others — and the **relationships** between entities are stated with their cardinality (a pupil takes many loans; a loan is of one book). Only then are the **tables** drawn: one table per entity, attributes as columns, keys in place, and **foreign keys** carrying the relationships. Malaysia's order is the lesson: tables drawn before entities and keys are understood are not a design but a guess that the data will later pay for.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. From the need — what the database must hold and what questions it must answer
2. The kinds of thing the database is about — Pupil, Book, Loan
3. The facts kept about an entity — a pupil's name, class, date of birth
4. The attribute (or added ID) that picks out one record from all others

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Tables are not where a database starts. Malaysia's design lesson walks the road before them: need, entities, attributes, keys, relationships — then tables. In this lesson you design a small relational database on paper, in the book's order. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of from the need to entities and attributes as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of keys, relationships, and the tables in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of from the need to entities and attributes → the student studies the picture and names what each part shows
- GIF — a GIF of keys, relationships, and the tables in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
