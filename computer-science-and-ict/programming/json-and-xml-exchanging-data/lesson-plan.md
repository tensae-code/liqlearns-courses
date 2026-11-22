# Lesson plan — JSON and XML — Exchanging Data

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** JSON and XML — Exchanging Data
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Programming on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Programs exchange data as structured text: JSON writes objects as name–value pairs that Python turns directly into dictionaries and lists, and XML writes a tree of tagged elements that a parser walks — and with a few lines a program can fetch live JSON from a web service and use it, or read an XML file element by element.
**This lesson's own level:** It stands on the formats lesson (what JSON and XML look like) and on Python dictionaries. A learner who knows dictionaries can start here directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **JSON — data as dictionaries** — Fetching a web service’s answer with urllib, turning the JSON text into Python objects with the json module — objects become dictionaries, arrays become lists — and reading values out by their names; the book’s example is the live crew of the ISS from api.open-notify.org.
2. **XML — data as a tree of elements** — Parsing an XML file with ElementTree: the root element, its children and their children, each element’s tag, text and attributes; finding all elements of one kind and reading them in a loop — the book’s example is a file of films.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Databases lesson on tabular file formats and the Programming lesson on Python dictionaries, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Données structurées et leur traitement", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Fetch a web service’s JSON answer with urllib and parse it with the json module.
2. Read values out of the parsed JSON by name, and loop over a list inside it.
3. Parse an XML file with ElementTree and describe its tree of elements.
4. Loop over all elements of one kind in an XML file and print a chosen field from each.

## What you need
A computer with Python; an internet connection for the live web-service part (the XML part works fully offline).

## The run of the lesson (in order)
1. **Do it first** — A web service answers a program’s question with a page of JSON text about astronauts in space — read it by eye and list what it knows, before the lesson shows the program that reads it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a satellite beaming JSON text to a laptop, the text unfolding into a dictionary and a list — the student matches two values in the text to their places in the dictionary
   - ADD GIF: a GIF of an XML file folding itself into a tree of element boxes, one branch unfolding at a time — the student names the root and the children of the unfolded branch
   - ADD IMAGE: a picture of a films.xml tree with one film branch highlighted from root to year — the student writes the loop that would visit every film on the tree
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a satellite beaming JSON text to a laptop, the text unfolding into a dictionary and a list → the student matches two values in the text to their places in the dictionary
- GIF — a GIF of an XML file folding itself into a tree of element boxes, one branch unfolding at a time → the student names the root and the children of the unfolded branch
- IMAGE — a picture of a films.xml tree with one film branch highlighted from root to year → the student writes the loop that would visit every film on the tree
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
JSON arrives but will not parse → the fetch returned the page, not the data (wrong address, or an error page); print the raw text before parsing and look at it. Dictionary key not found → names must match the JSON exactly, capitals included; print the dictionary’s keys. XML loop finds nothing → the search starts at the root; check the tags’ spelling and whether the elements are children or deeper descendants.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches JSON through the live ISS service (api.open-notify.org) and XML through a films file, both in the En codant strand of its data theme, with the two syntaxes set out in the Prolongements; this lesson follows that pairing.
