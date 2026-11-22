# Lesson plan — Tabular File Formats — CSV, JSON and XML

**Course:** Computer Science and ICT · **Title:** Databases · **Lesson:** Tabular File Formats — CSV, JSON and XML
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Databases on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The same table of data can live in many file shapes: spreadsheet files (XLSX, ODS) that carry presentation with the data, CSV — the table as plain text, one row per line, values separated by commas or semicolons — and the structured text formats JSON and XML, which name every value so programs can exchange data without a spreadsheet at all.
**This lesson's own level:** It stands on the structured-data lesson (collections as tables). No program knowledge is needed; the programming lessons on CSV, JSON and XML build on this one.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Spreadsheet files and CSV** — XLSX and ODS files store the table together with its presentation — column widths, colours, formulas — inside one program’s format. CSV strips all that away: plain text, the first line naming the descriptors, one line per row, values separated by a comma — or, in French locale, by a semicolon, because the comma is the decimal mark.
2. **JSON and XML — structured text formats** — JSON writes data as nested objects of name–value pairs and lists, in the syntax of JavaScript objects; XML writes it as a tree of tagged elements, each value wrapped in a named tag. Both name every value, so any program can read what any other program wrote.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Databases lesson on structured data — objects, descriptors and collections, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Données structurées et leur traitement", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Write a small table as a correct CSV file, header line included.
2. Say why French CSV files often use the semicolon instead of the comma.
3. Read a small JSON object and state the table it describes.
4. Read a small XML document and state the table it describes, and choose the right format for a given job.

## What you need
Paper and a pencil; a computer with a text editor and a spreadsheet for the hands-on work, if available.

## The run of the lesson (in order)
1. **Do it first** — Write one small table — three students, three descriptors — as pure text in three different ways, before the lesson names the standard formats. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one small table shown as a spreadsheet grid and as CSV text with the header line underlined — the student points at one cell of the grid and finds its value in the CSV text
   - ADD IMAGE: a picture of the same student written as a CSV line, a JSON object and an XML element tree, the values colour-matched — the student reads the year out of each of the three writings
   - ADD GIF: a GIF of a spreadsheet table being saved as CSV, its colours and borders falling away until only text remains — the student names what was lost and what was kept in the saving
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one small table shown as a spreadsheet grid and as CSV text with the header line underlined → the student points at one cell of the grid and finds its value in the CSV text
- IMAGE — a picture of the same student written as a CSV line, a JSON object and an XML element tree, the values colour-matched → the student reads the year out of each of the three writings
- GIF — a GIF of a spreadsheet table being saved as CSV, its colours and borders falling away until only text remains → the student names what was lost and what was kept in the saving
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Forgets the header line in CSV → without it, the values are numbers without names; the first line is the descriptors, always. Mixes separators → one file, one separator, used in every line including the header. Thinks JSON and XML are programs → they are text formats; any program can read or write them, which is their whole point.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches the formats inside its data Cours — XLSX, ODS, CSV, JSON, XML and even SQL named as table formats — and returns to JSON and XML syntax in the Prolongements; this lesson follows that map.
