# Lesson plan — Dijkstra's Algorithm — the Shortest Path

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Dijkstra's Algorithm — the Shortest Path
**Place in the curriculum:** ICT expansion — Germany (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Germany's *Informatik 5 (Bayern NTG)*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** Dijkstra's algorithm finds the cheapest route through a weighted graph: keep a tentative distance for every node, always settle the unsettled node with the smallest tentative distance, and relax its edges — a settled node's distance is final, and following the parents back gives the shortest path.
**This lesson's own level:** It stands on Graphs — Nodes and Edges and on Breadth-First Search in this strand: breadth-first search is Dijkstra with all weights equal to 1.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The greedy step — tentative distances and settling** — Every node starts with tentative distance infinity except the start (0). Settle the unsettled node with the smallest tentative distance; relax each edge from it — if going through it beats a neighbour's tentative distance, replace the distance and note the parent. A settled distance never changes again.
2. **Reading the answer — and why greedy is safe** — Final distances are the cheapest costs; parents chain back into the shortest path. Why it works: any other route to the settled node must leave the settled region through a node already at least as expensive, and weights are never negative — the one condition. Uses: routing and navigation.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Programming lessons Graphs — Nodes and Edges and Breadth-First Search in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Carry out Dijkstra's algorithm on a small weighted graph, keeping the distance table.
2. Read the shortest path and its total cost from the parents the algorithm leaves behind.
3. Say why the greedy step is safe, and name the one condition the weights must meet.

## What you need
Paper and a pencil, and a ruler for the distance table. Dijkstra is careful bookkeeping: one table, updated without erasing, so every step can be checked.

## The run of the lesson (in order)
1. **Do it first** — Two roads join your town to the next: a short road over a hill, and a longer flat road that may still be quicker. 'Shortest' now means cheapest, not fewest. This lesson works the famous algorithm that finds the cheapest route — and proves each answer as it goes. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the five-town graph with the settling order numbered and each node's final distance in a box beside it — the student says the settling order aloud and points to the step where one town's price fell.
   - ADD IMAGE: a picture of the shortest route to the target town highlighted edge by edge, with its cost added up underneath — the student adds the highlighted costs and checks the total against the distance table.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the five-town graph with the settling order numbered and each node's final distance in a box beside it → the student says the settling order aloud and points to the step where one town's price fell.
- IMAGE — a picture of the shortest route to the target town highlighted edge by edge, with its cost added up underneath → the student adds the highlighted costs and checks the total against the distance table.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Settles the nearest node instead of the cheapest tentative one → the table decides, not the drawing: always scan the tentative distances. Erases old tentative values → cross out and write the new one beside it; the falls (4 → 3) are the algorithm's story and its check.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. 
