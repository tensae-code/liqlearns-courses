# Lesson plan — Python Lists — Creating, Indexing and Methods

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Python Lists — Creating, Indexing and Methods
**Place in the curriculum:** ICT expansion — Kuwait (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Kuwait's student books (Ministry of Education, State of Kuwait), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Python's list — creating one, reaching its items by index, and its methods for changing it (Kuwait Grade 10 Term 2, Python data structures 1)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Creating a list and indexing it** — A **list** holds **many values in one variable, in order**, written in square brackets: `marks = [18, 15, 20]`. Each item has an **index** — its position counted **from 0** — and `marks[1]` reaches the second item. Indexing is the list's promise: any item can be reached directly by its number, changed by assignment to its index, and counted with `len()`. The course begins here because almost every real program's data arrives as a collection, not a lone value.
2. **List methods — changing the collection** — Lists are **mutable** — they can change after creation — and their **methods** are the changes with names: **append** adds an item at the end; **insert** places one at a chosen index; **remove** and **pop** take items out; **sort** orders them and **reverse** turns them around; **index** and **count** answer questions about what is inside. Read a method by its effect on the collection, and remember the course's warning in the same breath: the list changed is the same list — no copy is made unless the program asks for one.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kuwait's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Many values in one variable, in order, written in square brackets
2. From 0
3. The second item — 15
4. How many items the list holds

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Term 2's Python begins with holding many things at once. The list is Python's first data structure in Kuwait's course — a single variable that carries a whole collection, in order. This lesson is making one, reading it, and changing it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of creating a list and indexing it as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of list methods — changing the collection in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of creating a list and indexing it → the student studies the picture and names what each part shows
- GIF — a GIF of list methods — changing the collection in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
