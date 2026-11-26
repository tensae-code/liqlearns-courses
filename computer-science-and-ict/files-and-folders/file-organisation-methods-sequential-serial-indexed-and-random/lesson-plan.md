# Lesson plan — File Organisation Methods — Sequential, Serial, Indexed and Random

**Course:** Computer Science and ICT · **Title:** Files and Folders · **Lesson:** File Organisation Methods — Sequential, Serial, Indexed and Random
**Place in the curriculum:** Phantom repair — Kenya (2026-11-25) — in the title Files and Folders on the ICT course ladder (TITLES.md). Built new from Kenya's *Log On Computer Studies Form 3* (student book), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A file's organisation is the rule for where each record sits and how you reach it: serial files store records in arrival order, sequential files store them sorted by key and read them in order, indexed-sequential files add an index so you can jump near a record as well as read in order, and random (direct) files calculate each record's address from its key for instant access.
**This lesson's own level:** It stands on the lessons named under "Before this lesson"; it stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Serial and sequential organisation** — Serial: records are written one after another in the order they arrive, unsorted — cheap to add to, but finding one record means reading from the start. Sequential: records are stored sorted by their key field and processed in that order, one after the other — the natural fit for batch work like payroll, where every record is visited anyway.
2. **Indexed-sequential and random organisation** — Indexed-sequential (ISAM): the file stays sorted, and a separate index — like a book's index — maps key ranges to places in the file, so you can jump close to a record and then read a few, or still process the whole file in order. Random (direct): no order at all — an address is calculated from the key itself (hashing), so any record is reached in one jump; perfect for instant lookups, useless for reading in key order.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Databases lesson on records, files and file types, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Kenya's own way is kept: the book teaches this inside its own unit/chapter order, in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Describe serial, sequential, indexed-sequential and random file organisation in your own words.
2. Say which access each method allows: sequential only, or direct as well.
3. Match a real job (payroll run, bank account lookup) to the organisation that fits it.
4. Name one strength and one weakness of each method.

## What you need
Paper and a pencil. A pack of numbered cards serves as a model file.

## The run of the lesson (in order)
1. **Do it first** — Take ten pieces of paper and write a name and a number on each — shuffle them. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of two rows of record cards: the first row in jumbled number order labelled serial, the second in neat ascending order labelled sequential — the student points to where record 7 sits in each row
   - ADD GIF: a GIF of a finger scanning card after card from the left in a serial row, then the same finger walking a sorted row and stopping early once the numbers pass the target — the student says why the sorted row can stop early
   - ADD IMAGE: a picture of a sorted stack of records with a small index card beside it pointing ranges of keys to stack positions, and next to it a key being fed into a formula box that outputs an address — the student traces one lookup through each drawing
   - ADD GIF: a GIF of a key number entering a hashing formula and an arrow flying directly to one record in a scattered grid, skipping all the others — the student contrasts it with the scanning GIF from sub lesson 1
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of two rows of record cards: the first row in jumbled number order labelled serial, the second in neat ascending order labelled sequential — the student points to where record 7 sits in each row
- GIF — a GIF of a finger scanning card after card from the left in a serial row, then the same finger walking a sorted row and stopping early once the numbers pass the target — the student says why the sorted row can stop early
- IMAGE — a picture of a sorted stack of records with a small index card beside it pointing ranges of keys to stack positions, and next to it a key being fed into a formula box that outputs an address — the student traces one lookup through each drawing
- GIF — a GIF of a key number entering a hashing formula and an arrow flying directly to one record in a scattered grid, skipping all the others — the student contrasts it with the scanning GIF from sub lesson 1
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
