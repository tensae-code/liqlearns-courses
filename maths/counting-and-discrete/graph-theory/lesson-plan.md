<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Graph theory

**Course:** Maths · **Unit:** Unit 14 — Counting and Discrete Mathematics · **Lesson:** Graph theory
**Place in the curriculum:** Level 108 of 136, Unit 14 — Counting and Discrete Mathematics (maths/CURRICULUM.md).
**The one thing this lesson teaches:** graphs — vertices, edges and degrees; Euler and Hamilton paths; shortest paths; dominating sets and the domination number; and bin-packing algorithms.
**This lesson's own level:** it stands on the counting lessons of this unit — the learner can already count systematically. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the
exact places marked below, the lesson page carries an add-on — an
image, a GIF, a video, an audio. Every slot is written as **"a picture
of …" in words, plus one little line saying what the student does
with it**. The words carry the picture while the course is built and
while the AI learns from the books; on the website the real add-on is
dropped into that slot and the little explanation stays as the
student's guide. Images follow the picture rule (a real photograph,
or real art, with its source). GIFs come first where a thing must be
shown changing.

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **Graphs, Vertices, Edges and Degrees** — what a graph is — vertices, edges, loops, order and size — degree, the complement and complete graphs, and the handshaking lemma. (Was depth Level 1.)
2. **Paths, Euler Paths, Hamilton Paths and Shortest Paths** — paths and cycles and connected graphs, Euler paths, Hamilton paths, and shortest paths. (Was depth Level 2.)
3. **Algorithms, Bin Packing and Dominating Sets** — algorithms and bin packing (first-fit and first-fit decreasing), and dominating sets and the domination number. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Counting principles (Level 105, this unit) — a graph problem is a counting-and-choosing problem. Recommended, never forced.
- Recommended first: the pigeonhole principle (Level 103) for the domination bound's covering argument. Recommended, never forced.

## What the learner can do when it ends
1. Draw a graph from vertices and edges, and read off its order, size and each vertex's degree, the way Iran's Discrete Mathematics book builds the vocabulary (pp.34–37).
2. Use the handshaking lemma — the sum of the degrees is twice the number of edges — and its corollary that the number of odd-degree vertices is even, as Iran's book proves them (p.40).
3. Decide whether a route uses every edge exactly once (an Euler path) or every vertex exactly once (a Hamilton path), the way Vietnam's Grade 11 study book teaches them (Bài 9, p.41).
4. Find a shortest path in a small network in the simple cases Vietnam's book works (Bài 10, p.46).
5. Follow an algorithm step by step and use first-fit bin packing to pack items into bins, the way Jordan's Grade 12 Business Mathematics book teaches algorithms and bin-packing (Unit 2, pp.58–82).
6. Find a dominating set of a graph, tell minimal from minimum, and compute the domination number γ(G) for small graphs, the way Iran's book develops domination (pp.43–54), including the bound γ(G) ≥ ⌈n/(Δ+1)⌉ (p.49).

## What you need
Paper and a pencil. Dots and lines drawn by hand are the whole laboratory. A ruler helps; string or counters help for the bin-packing.

## The run of the lesson (in order)
1. **Do it first** — the learner draws the Königsberg bridges as dots and lines and tries to walk every bridge once (lesson/lesson.md).
2. **The explanation** — graph vocabulary and degrees; the handshaking lemma; Euler and Hamilton paths; shortest paths; algorithms and bin packing; dominating sets (lesson/lesson.md).
   - ADD GIF at the Königsberg part: a picture of a walker tracing bridges one by one and getting stuck — the student counts the odd-degree land masses before the walk starts.
   - ADD IMAGE at the vocabulary part: a picture of a small graph with its vertices labelled and each degree written beside its vertex → the student checks the degrees add to twice the edges.
   - ADD IMAGE at the bin-packing part: a picture of three bins filling up item by item under first-fit → the student says which bin each next item enters, and why.
   - ADD GIF at the domination part: a picture of guards placed on vertices, with every covered vertex lighting up — the student watches one well-placed guard cover its neighbours too.
3. **Say it to your companion** — explain the difference between an Euler path and a Hamilton path in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — graph theory in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — draw your own street graph, find its degrees, an Euler or Hamilton path if one exists, and a smallest dominating set (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of a walker tracing the Königsberg bridges and getting stuck → the student counts odd degrees first.
- IMAGE — a picture of a labelled graph with degrees written in → the student checks the handshaking count.
- IMAGE — a picture of bins filling under first-fit → the student predicts each item's bin.
- GIF — a picture of guards covering a graph vertex by vertex → the student counts how few guards cover all.
- VIDEO — the video-script filmed (made later) → the student follows the two path kinds along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Mixes up Euler and Hamilton → Vietnam's way: Euler is about the EDGES (every bridge once), Hamilton is about the VERTICES (every town once). Say "E for edges".
- Counts a loop's degree wrong → Iran's book counts a loop twice in the degree, because it joins the vertex to itself at both ends (pp.34–37).
- Thinks a dominating set must cover only the other vertices → a chosen vertex covers ITSELF and its neighbours; that is the whole point of Iran's ATM-and-guards pictures (pp.43–48).
- Finds a dominating set but not the smallest → try the bound first: γ(G) ≥ ⌈n/(Δ+1)⌉ (Iran, p.49); if your set meets the bound, it is minimum and you can stop.
- This lesson's next door: Congruences and Diophantine equations (Level 109, same unit).

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Iran, Discrete Mathematics, Grade 12; Vietnam, Grade 11 study book; Jordan, Business Mathematics Grade 12 Term 1; China, Grade 6 second volume — the Königsberg box, enrichment as filed). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
