# Lesson plan — Python Sets

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Python Sets
**Place in the curriculum:** ICT expansion — Jordan (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Jordan's NCCD Digital Skills books (Jordan Grade 12 G12T1 Student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** sets in Python — unordered collections of unique values, and the set operations (Jordan Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What a set is** — A **set** is a collection of **unique** values in **no fixed order**, written in curly brackets: `{1, 2, 3}`. Adding a value already present changes nothing; there is no index, because there is no order to index by. The set's native question is **membership** — 'is this value in?' — asked with `in`, and answered fast however large the set grows. Sets are mutable (values can be added and removed), and their values must be of kinds that can be held fixed.
2. **Set operations — the mathematics built in** — Python builds set mathematics in as operations: **union** (in either — `|`), **intersection** (in both — `&`), **difference** (in the first, not the second — `−`), and **symmetric difference** (in exactly one — `^`). Jordan's Grade 12 data-structures lesson places sets after lists, tuples and dictionaries because the four together are the chooser's kit: order-and-change (list), order-fixed (tuple), named (dictionary), unique (set) — and real data declares which it is, if the programmer listens.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Jordan's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Unique values, no fixed order
2. Nothing — the set is unchanged
3. There is no order to index by
4. Membership — 'is this value in?'

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A list can hold the same pupil twice. A set cannot — and that refusal is its whole usefulness. This lesson learns Python's set: the collection that keeps each value once. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of what a set is as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of set operations — the mathematics built in in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of what a set is → the student studies the picture and names what each part shows
- GIF — a GIF of set operations — the mathematics built in in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
