# Lesson plan — Project — Navigation Systems with Graphs

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Project — Navigation Systems with Graphs
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** a navigation system is the graph strand at work: the road network becomes a weighted graph (crossings as nodes, road pieces as edges weighted by time or length), and a shortest-path search answers every route request — this project lesson builds a small one by hand and meets the real system's extra jobs.
**This lesson's own level:** It stands on the whole graph strand before it — graphs, the adjacency matrix, breadth-first search and Dijkstra — and pulls them together into one working thing, as the book's own deepening project (Vertiefung) does.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Before this lesson
- Recommended first: the Programming lessons Graphs — Nodes and Edges, The Adjacency Matrix, Breadth-First Search and Dijkstra's Algorithm in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Turn a small road map into a weighted graph, choosing nodes, edges and weights sensibly.
2. Answer a route request on that graph with Dijkstra's algorithm and present the route.
3. Name the extra jobs a real navigation system does beyond the shortest path.

## What you need
A printed or hand-drawn map of a neighbourhood you know, paper, a pencil, and the distance tables from the Dijkstra lesson. A phone map app, if one is at hand, is the comparison at the end — not the tool that does the work.

## The run of the lesson (in order)
1. **Do it first** — Open any map in your mind and ask for the way from home to school. In under a second a line appears. This project lesson slows that second down until you can build it yourself, by hand, on a real map. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a small street map dissolving into its graph — junctions as nodes, road pieces as edges with minute-weights — the student names the node and weight for three road pieces, unaided.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a small street map dissolving into its graph — junctions as nodes, road pieces as edges with minute-weights → the student names the node and weight for three road pieces, unaided.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Models every house as a node → nodes are junctions and start/end places; houses hang off edges. Weights by length when the user asked for fastest → the weight must match the question: time weights answer 'fastest', length weights answer 'shortest'.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
