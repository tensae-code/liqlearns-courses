# Lesson plan — Processing CSV Files with Python Pandas

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Processing CSV Files with Python Pandas
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Programming on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Python’s pandas library reads a whole CSV file into a table object — a DataFrame — in one line, and then the program can select rows with conditions (loc), pick columns, and compute on thousands of rows as easily as on ten: the spreadsheet’s questions, asked by code.
**This lesson's own level:** It stands on the CSV format lesson and on basic Python (variables, calling functions). A learner who has seen a CSV file can start here directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Reading a CSV table with pandas** — read_csv turns the file into a DataFrame: the header line becomes the column names, each line a row; the program can show the first rows, count them, and name the columns — the table from the formats lesson, alive in memory.
2. **Asking questions of the table — and a real flight log** — Selecting with loc and conditions — rows where a column passes a test — taking a single column, and computing maxima, means and counts; the SNT book’s second use is a drone’s flight CSV: times, positions and altitudes from a real flight, analysed and mapped the same way, with the drone’s speed computed from the rows.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Databases lesson on tabular file formats and the Programming lessons on Python basics, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Données structurées et leur traitement", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Load a CSV file into a pandas DataFrame and report its columns and row count.
2. Select the rows of a DataFrame that match a condition, using loc.
3. Compute a maximum, a mean and a count on a chosen column.
4. Explain how a drone’s speed is computed from the rows of its flight log.

## What you need
A computer with Python and the pandas library. The thinking can be followed on paper with the printed CSV.

## The run of the lesson (in order)
1. **Do it first** — Take a printed CSV of twenty rows and answer three questions about it by hand, timing yourself — before the lesson shows the one line that loads it and the one line per question. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a CSV file flowing through a read_csv arrow into a table grid whose header has become column names — the student points at the header line and at where it landed in the table
   - ADD GIF: a GIF of rows lighting up one by one as a loc condition is applied, the non-matching rows fading out — the student predicts which rows will stay lit before the condition runs
   - ADD IMAGE: a picture of a drone’s curved flight path with three log rows beneath and a speed worked out between two points — the student says which two numbers from the rows divide to give the speed
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a CSV file flowing through a read_csv arrow into a table grid whose header has become column names → the student points at the header line and at where it landed in the table
- GIF — a GIF of rows lighting up one by one as a loc condition is applied, the non-matching rows fading out → the student predicts which rows will stay lit before the condition runs
- IMAGE — a picture of a drone’s curved flight path with three log rows beneath and a speed worked out between two points → the student says which two numbers from the rows divide to give the speed
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
The file loads but the numbers behave as text → the values were not recognised as numbers (a stray separator or decimal mark — remember the French semicolon and decimal comma); fix the reading options, not the questions. loc returns nothing → the condition must match the data exactly (spelling, capitals, type); print a few rows and compare. Column name not found → names come from the header line, character for character; list the columns and copy.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches pandas in the En codant strand of its data theme (read_csv, loc) and returns to it for the drone flight log in the localisation theme; this lesson carries both placements in that order.
