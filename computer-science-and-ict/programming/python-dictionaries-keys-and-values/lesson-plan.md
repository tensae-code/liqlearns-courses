# Lesson plan — Python Dictionaries — Keys and Values

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Python Dictionaries — Keys and Values
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Python's dictionary — values kept under named keys, reached by name instead of by position (Kuwait Grade 10 Term 2)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Keys and values — reaching by name** — A **dictionary** keeps **pairs**: a **key** and its **value**, written in curly brackets — `student = {"name": "Hamad", "grade": 10}`. A value is reached by its key — `student["grade"]` — the way a person looks a word up by its spelling, not by its page position. Keys are the dictionary's index and its meaning in one: a record's fields are **named**, so the program reads like the record it holds.
2. **Working with dictionaries — add, change, remove, ask** — Dictionaries are **mutable** in the record-keeper's ways: assigning to a **new key adds** a pair; assigning to an **existing key changes** its value; **del** and **pop** remove pairs; and the dictionary answers questions — its **keys**, its **values**, whether a key is present at all. The warning travels with the power: asking for a key that is **absent raises an error**, so careful programs test before they ask — the dictionary's version of looking before leaping.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Pairs — a key and its value, in curly brackets
2. By its key — student["grade"]
3. By name, not by position
4. Assigning to a new key

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Lists and tuples reach their items by number. The dictionary reaches them by name. Kuwait's third data structure is the one real records are kept in. This lesson is the dictionary and its key-based world. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of keys and values — reaching by name as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of working with dictionaries — add, change, remove, ask in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of keys and values — reaching by name → the student studies the picture and names what each part shows
- GIF — a GIF of working with dictionaries — add, change, remove, ask in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
