# Lesson plan — Structured Data — Objects, Descriptors and Collections

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Structured Data — Objects, Descriptors and Collections
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Databases on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Data becomes structured when the world is described in a fixed way: each thing is an object, each fact about it is a descriptor with a value, and objects described by the same descriptors form a collection — which is drawn as a table, one row per object, one column per descriptor.
**This lesson's own level:** It stands on nothing technical: only on the difference between a fact and a description of a fact. It is the first lesson of the databases ladder in France’s order.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Objects and their descriptors** — An object is one thing being described; a descriptor is one named aspect of it (colour, price, year); the value is what that descriptor holds for this object. Choosing descriptors is a decision: the same object can be described differently for different purposes.
2. **Collections — data in tables** — A collection gathers objects that share the same descriptors; drawn as a table, each row is one object and each column one descriptor — the shape every database, spreadsheet and CSV file in later lessons will take.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Computers in Society lesson on data as raw facts, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Données structurées et leur traitement", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Describe one object by at least four descriptors, each with its value.
2. Explain why the choice of descriptors depends on the purpose of the data.
3. Turn a small collection of objects into a table with the rows and columns in the right places.
4. Say what an empty cell in such a table means.

## What you need
Paper and a pencil. Objects in the room serve as the examples.

## The run of the lesson (in order)
1. **Do it first** — Describe one classmate — or one book — so exactly that someone could pick it out of a hundred, listing the facts you would need, before the lesson names descriptors. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one book with labelled lines running from it to its descriptors and their values — the student adds one more descriptor the bookshop would want and gives its value
   - ADD GIF: a GIF of three described books sliding into three rows of a table while their shared descriptors rise into the column headings — the student names what each row and each column stands for as it settles
   - ADD IMAGE: a picture of a table with one empty cell circled — the student explains what the empty cell says about that object
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one book with labelled lines running from it to its descriptors and their values → the student adds one more descriptor the bookshop would want and gives its value
- GIF — a GIF of three described books sliding into three rows of a table while their shared descriptors rise into the column headings → the student names what each row and each column stands for as it settles
- IMAGE — a picture of a table with one empty cell circled → the student explains what the empty cell says about that object
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Puts descriptors in the rows and objects in the columns → the table’s law is one row per object, one column per descriptor; the headings are the descriptors. Describes each object with different descriptors → a collection needs the SAME descriptors for every object, or the columns fall apart. Thinks more descriptors is always better → each descriptor must serve the purpose; unused descriptors are weight, not wealth.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book opens its structured-data theme with objects, descriptors and collections before any file format appears — this lesson keeps that order as the doorway to the databases ladder.
