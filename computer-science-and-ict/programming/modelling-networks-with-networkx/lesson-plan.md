# Lesson plan — Modelling Networks with NetworkX

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Modelling Networks with NetworkX
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Programming on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Python’s networkx library builds a graph in code — nodes, then edges, directed for followings (Twitter-style) or undirected for friendships (Facebook-style) — and then computes the graph measures of the earlier lesson in single calls: the centre, the radius, the diameter of a network far too big to measure by hand.
**This lesson's own level:** It stands on the graph-measures lesson and on Python basics (imports, lists, loops). A learner who has measured a graph by hand is ready to let the machine do it.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Building directed and undirected graphs in Python** — Creating a graph with networkx; adding nodes and edges from lists; the fork that matters: a DiGraph for directed relations — A follows B does not imply B follows A, as on Twitter — and a Graph for mutual relations, as with Facebook friendships.
2. **Measuring the network with the machine** — The measures of the earlier lesson as library calls — nx.center, nx.radius, nx.diameter — run on graphs of any size; reading back the results and checking them against the hand-measured small graph before trusting them on a big one.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Programming lessons on graphs and on graph measures, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Les réseaux sociaux", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Build an undirected graph in networkx from lists of nodes and edges.
2. Build a directed graph for a following relation and explain how its edges differ.
3. Compute centre, radius and diameter with networkx calls.
4. Verify the machine’s measures against a hand-measured graph before trusting them on a large one.

## What you need
A computer with Python and the networkx library.

## The run of the lesson (in order)
1. **Do it first** — Take the friendship graph you measured by hand in the graph-measures lesson and list the instructions you would give a tireless assistant to rebuild and measure it — before the lesson shows the library that is that assistant. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the same five people drawn twice — friendship edges two-headed, follow arrows one-way — with the code class under each — the student chooses the right drawing and class for "A is subscribed to B’s channel"
   - ADD GIF: a GIF of edges appearing one by one on a graph as add_edges_from runs, the node count rising with each — the student calls out the next edge in the list before it appears
   - ADD IMAGE: a picture of a small graph and a vast graph with the same three function calls under both, the small one ticked "checked by hand" — the student explains why the tick must come before trusting the vast graph’s answers
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the same five people drawn twice — friendship edges two-headed, follow arrows one-way — with the code class under each → the student chooses the right drawing and class for "A is subscribed to B’s channel"
- GIF — a GIF of edges appearing one by one on a graph as add_edges_from runs, the node count rising with each → the student calls out the next edge in the list before it appears
- IMAGE — a picture of a small graph and a vast graph with the same three function calls under both, the small one ticked "checked by hand" → the student explains why the tick must come before trusting the vast graph’s answers
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Measures throw an error about the graph not being connected → centre, radius and diameter need every node reachable from every other; a stray unconnected node breaks them — find and join or remove it. Directed edges behave like friendships → DiGraph edges are one-way by design; if the relation is mutual, the model is Graph. Machine disagrees with hand work → trust neither blindly: recount the edge list against the drawing first; most disagreements live there.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book programs the social-network model in the En codant strand of its social-networks theme — dictionaries first, then networkx, directed and undirected — and this lesson follows that strand, standing on the hand measures of its Cours.
