# Lesson plan — Characteristics of a Relational Database — Codd's Rules

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Characteristics of a Relational Database — Codd's Rules
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** the characteristics of a relational database: Codd's rules — the tests a system must pass to deserve the name RDBMS — and the standard RDBMS systems the book lists (Bangladesh HSC ICT, Chapter 6, §6.4.2).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Codd's rules — the character tests** — **Codd's rules** state what a true RDBMS guarantees. Among their heads: all information is held as **values in tables** — nothing hides in pointers the user cannot see; every value is reachable by **table name, key and column name**; **nulls** are handled systematically (the companion lesson); the catalogue describing the database is itself stored as tables and queryable with the same language; and one **comprehensive language** (SQL) does everything — defining, querying, changing. A system failing the heads may be useful, but it is not fully relational.
2. **The standard systems — and why the rules matter** — The book closes with the **standard RDBMS list** — the systems the world's organisations actually run, from desktop-scale to the engines behind banks and governments, Bangladesh's own NID and passport databases among the companion lesson's examples. The rules matter beyond examinations because they are promises a buyer can test: data independent of the programs that use it, integrity the system itself enforces, and no back doors around the language. Choose a system by Codd's tests and the data will outlive every program written against it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Edgar Codd, the relational idea's inventor
2. As values in tables — nothing hidden in pointers
3. By table name, key and column name
4. Systematically — by rule, not by accident

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Many programs store data in tables; few deserve the title relational database management system. In 1985 Edgar Codd, who invented the relational idea, published the rules that separate the real thing from the imitation. This lesson holds systems up against his list. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of codd's rules — the character tests as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the standard systems — and why the rules matter in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of codd's rules — the character tests → the student studies the picture and names what each part shows
- GIF — a GIF of the standard systems — and why the rules matter in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
