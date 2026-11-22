# Lesson plan — Graph Measures — Distance, Centre and Diameter

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Graph Measures — Distance, Centre and Diameter
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Programming on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A graph can be measured: the distance between two nodes is the length of the shortest path joining them; a node’s eccentricity is its greatest distance to any other node; the centre is the node whose eccentricity is smallest, that smallest value is the radius, and the greatest distance in the whole graph is its diameter — the numbers that say how spread out a network is and who sits at its middle.
**This lesson's own level:** It stands on the graphs lesson (nodes and edges) and on counting path lengths. France’s book measures the class’s own social network; any small graph on paper serves the same way.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Distance and eccentricity** — Distance between two nodes: the number of edges on a shortest path between them (found by spreading out level by level). Eccentricity of a node: the largest of its distances to all the others — how far the node is from the far end of its world.
2. **Centre, radius and diameter — and small worlds** — The centre: the node of smallest eccentricity; the radius: that smallest eccentricity; the diameter: the largest distance anywhere in the graph. Then the famous smallness of real networks: Milgram’s six degrees, and Facebook’s measured 4.74 — big graphs, tiny diameters.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Programming lesson on graphs — nodes and edges, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Les réseaux sociaux", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Compute all distances from one node of a small graph by spreading out in waves.
2. State a node’s eccentricity and say what sets it.
3. Find a small graph’s centre, radius and diameter and defend each answer.
4. Explain the claim of six degrees of separation and the measured Facebook figure.

## What you need
Paper and a pencil. The graph from Do it first is the working example.

## The run of the lesson (in order)
1. **Do it first** — Take a small friendship graph of seven pupils and guess who is "in the middle" of it — before the lesson defines middle with numbers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the seven-pupil graph with waves of colour spreading from one node, distances labelled — the student continues the wave from a different starting node and labels its distances
   - ADD GIF: a GIF of the wave spreading edge by edge across a graph until every node carries a distance number — the student calls out the distance of the last node before the wave reaches it
   - ADD IMAGE: a picture of a huge crowd graph with one short highlighted path joining two distant strangers — the student counts the edges of the highlighted path and says what that number is an example of
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the seven-pupil graph with waves of colour spreading from one node, distances labelled → the student continues the wave from a different starting node and labels its distances
- GIF — a GIF of the wave spreading edge by edge across a graph until every node carries a distance number → the student calls out the distance of the last node before the wave reaches it
- IMAGE — a picture of a huge crowd graph with one short highlighted path joining two distant strangers → the student counts the edges of the highlighted path and says what that number is an example of
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Counts a long path instead of the shortest → distance is the SHORTEST path; the wave method guarantees it because nodes are labelled the first time the wave arrives. Confuses radius and diameter → radius is the smallest eccentricity (best worst journey); diameter is the largest distance (worst pair). Thinks the centre is the node with most edges → degree and centre are different measures; a stalk’s hub can have high degree yet sit far from one end.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book measures the graph of the class’s own eighteen pupils in its social-networks theme and closes with Milgram and the Facebook study — this lesson keeps that example shape and those figures.
