# Lesson plan — Metadata — Data about Data

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Metadata — Data about Data
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Databases on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Metadata is the data that describes data: for a photo, a book or a dataset, it records what it is, who made it, when, in what format and where it belongs — and it is metadata, not the content itself, that lets machines file, find and sort millions of items.
**This lesson's own level:** It stands on the structured-data lesson (objects and descriptors). It is also the general idea behind the EXIF lesson in Multimedia: EXIF is a photo’s metadata.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What metadata is** — The definition and the kinds: descriptive metadata (title, author, subject), administrative metadata (date, format, size, rights), and structural hints (part of a series, page count) — written partly by people, partly automatically by machines, as the EXIF lesson showed for photos.
2. **Metadata at work — finding and sorting data** — How search, catalogues and file managers answer questions from metadata alone: filtering a collection by one descriptor, sorting by another — and what happens when metadata is missing or wrong: the item is still there, but no one can find it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Databases lesson on structured data — objects, descriptors and collections, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Données structurées et leur traitement", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Define metadata and give three examples for one real item.
2. Classify metadata items as descriptive or administrative, and say who or what wrote each.
3. Answer search questions about a small collection using only its metadata table.
4. Explain why an item with missing or wrong metadata is effectively lost.

## What you need
Paper and a pencil. Books or files nearby serve as examples.

## The run of the lesson (in order)
1. **Do it first** — Take one book and write down everything you could say about it without opening it — before the lesson gives that kind of data its name. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one book with two layers — the thick content and a card on top carrying title, author, date, format and size — the student reads the card and answers a question about the book without opening it
   - ADD GIF: a GIF of a million books going dark except the few whose cards glow under the filter words "French, 2020" — the student names the two descriptors the filter used
   - ADD IMAGE: a picture of a photo on a disk labelled IMG_0001 with no date, crossed by a big question mark — the student lists what metadata would have made the photo findable
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one book with two layers — the thick content and a card on top carrying title, author, date, format and size → the student reads the card and answers a question about the book without opening it
- GIF — a GIF of a million books going dark except the few whose cards glow under the filter words "French, 2020" → the student names the two descriptors the filter used
- IMAGE — a picture of a photo on a disk labelled IMG_0001 with no date, crossed by a big question mark → the student lists what metadata would have made the photo findable
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Calls the content itself metadata → metadata is ABOUT the item; the story inside the book is content, its title and year are metadata. Thinks all metadata is typed by people → machines write much of it automatically (EXIF, file size, creation date). Thinks a missing item must have been deleted → with wrong metadata it is present but unfindable; the failure is in the record, not the storage.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book gives metadata its own Cours inside the structured-data theme, between personal data and file formats — this lesson keeps that place.
