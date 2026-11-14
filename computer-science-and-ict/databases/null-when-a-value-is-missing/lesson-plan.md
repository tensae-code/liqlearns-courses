# Lesson plan — Null — When a Value Is Missing

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Null — When a Value Is Missing
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Databases on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** null: the database's way of saying a value is missing — not zero, not empty text, but unknown or not applicable — and the rule that a primary key is never null (Bangladesh HSC ICT, Chapter 6, §6.2.1).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Null — missing, not zero** — **Null** means **no value is stored** — the value is unknown, or the field does not apply to this record. Null is not **zero** (zero is a real amount) and not an **empty string** (that is a real, if short, text): a salary of 0 says the person earns nothing; a salary of null says we do not know, or the question does not arise. Queries must respect the difference: counting records with a value skips the nulls, and a comparison with null never comes out true — unknown compared to anything is still unknown.
2. **The primary key is never null** — One field may never hold the blank: the **primary key**. The key's whole job is to identify the record — the National ID of the companion lesson — and a record whose identifier is missing cannot be found, joined or told apart from another blank. So the DBMS enforces **entity integrity**: every primary key value exists and is unique. When you design a table, you decide field by field which may be null — a phone may be missing; an identity may not — and that decision is part of the table's honesty about the world.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Databases on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. No value is stored — unknown, or not applicable
2. No — zero is a real amount
3. No — an empty string is a real text
4. We do not know, or the question does not arise

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A form has a blank: the student has no phone. The database must store that blank honestly. Type 0 and you have invented a phone number that rings nobody; type a space and you have invented a name of nothing. Databases keep a special marker for the honest blank — and this lesson is about it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of null — missing, not zero as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the primary key is never null in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of null — missing, not zero → the student studies the picture and names what each part shows
- GIF — a GIF of the primary key is never null in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
