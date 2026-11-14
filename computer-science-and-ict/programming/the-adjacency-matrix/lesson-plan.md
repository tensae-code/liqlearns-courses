# Lesson plan — The Adjacency Matrix

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** The Adjacency Matrix
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** a graph can be stored as a table — the adjacency matrix — with one row and one column per node and a 1 where an edge joins two nodes (0 where it does not), so a computer can hold, check and compute with the graph.
**This lesson's own level:** It stands on the graphs lesson just before it in Germany's strand — nodes and edges — and on ordinary tables of rows and columns.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Building the matrix from a graph** — Rows and columns labelled by the nodes; entry 1 if an edge joins row-node to column-node, 0 if not; a loop puts a 1 (or 2) on the diagonal; a weighted graph stores the weight instead of 1.
2. **Reading the matrix — neighbours, degrees, symmetry** — A row lists a node's neighbours; a row's sum is the node's degree; an undirected graph's matrix mirrors across the diagonal; a directed graph's matrix need not; counting edges from the matrix (half the sum of all entries).

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Programming lesson Graphs — Nodes and Edges in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Build the adjacency matrix of a small undirected graph, and of a weighted graph.
2. Read a graph back out of its matrix — edges, degrees and neighbours.
3. Say why an undirected graph's matrix is symmetric, and what a directed graph changes.

## What you need
Paper with a squared grid (or a ruler to draw one) and a pencil. The matrix is a table you draw by hand first — the hand learns what the computer stores.

## The run of the lesson (in order)
1. **Do it first** — Take the friendship graph from the last lesson and try to write it as pure text a computer could store — no drawing allowed. It is harder than it looks. This lesson shows the table that does it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a small graph beside its adjacency matrix, with one edge and its two matching cells highlighted in the same colour — the student finds the two cells for one more edge, unaided.
   - ADD IMAGE: a picture of the adjacency matrix folded along its diagonal, the two halves matching cell for cell — the student checks three mirrored pairs and says whether the graph is undirected.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a small graph beside its adjacency matrix, with one edge and its two matching cells highlighted in the same colour → the student finds the two cells for one more edge, unaided.
- IMAGE — a picture of the adjacency matrix folded along its diagonal, the two halves matching cell for cell → the student checks three mirrored pairs and says whether the graph is undirected.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Writes 1s only above the diagonal → every undirected edge is stored twice, once from each end; the mirror half is not optional. Reads a column when asked for neighbours → neighbours live in the node's row.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
