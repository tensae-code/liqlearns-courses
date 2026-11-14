# Lesson plan — Mapping an ERD to a Relational Schema

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Mapping an ERD to a Relational Schema
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How an entity-relationship diagram is mapped to a relational schema — entities become tables, attributes become columns, keys are chosen, and relationships become foreign keys or new tables (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Entities and attributes — the straight mapping** — The straight rules come first: every **entity** in the ERD becomes a **table**; every **attribute** of the entity becomes a **column** of that table; the entity's **key attribute** becomes the table's **primary key**. A **multivalued attribute** (a pupil's phone numbers) cannot be a column — it becomes a **table of its own**, holding the key and one value per record. After this step every box and oval of the diagram has a home in the schema, or a stated reason why not.
2. **Relationships — foreign keys and new tables** — Relationships map by their **cardinality**. A **one-to-many** relationship is carried by a **foreign key**: the key of the 'one' side is placed as a column in the 'many' side's table (ClassID inside the Pupil table). A **many-to-many** relationship cannot be a single column — it becomes a **new table** holding both sides' keys as its composite key, plus the relationship's own attributes (an Enrolment table: PupilID, SubjectID, mark). Malaysia's check closes the mapping: every relationship in the ERD must be traceable in the schema — as a foreign key or as a table — or the mapping is not finished.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A table
2. A column of its entity's table
3. The table's primary key
4. By a foreign key — the 'one' side's key placed in the 'many' side's table

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — An ERD is a picture; a schema is the buildable design. Malaysia's advanced database chapter teaches the mapping between them as a craft of its own. In this lesson you turn a diagram into tables — rule by rule. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of entities and attributes — the straight mapping as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of relationships — foreign keys and new tables in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of entities and attributes — the straight mapping → the student studies the picture and names what each part shows
- GIF — a GIF of relationships — foreign keys and new tables in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
