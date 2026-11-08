# Graph theory — the lesson

Course: Maths · Unit: Unit 14 — Counting and Discrete Mathematics · Lesson: Graph theory
Built from: Iran, Discrete Mathematics, Grade 12 (Mathematical Sciences branch) — Vietnam, Grade 11 study book (Chuyên đề học tập Toán 11) — Jordan, Business Mathematics, Grade 12, Term 1 student book — China, Grade 6, second volume (the Königsberg box, enrichment as filed)

## Do it first
A river runs through a town. There are four pieces of land and seven bridges. Draw four dots for the land and a line for every bridge. Now try — without lifting your pencil and without tracing a line twice — to cross every bridge exactly once. You will get stuck. Iran's Discrete Mathematics book opens its graph chapter with exactly this Königsberg bridges problem, retelling Euler's 18th-century argument for why it cannot be done (pp.32–33), and China's Grade 6 book carries the same seven-bridges story as an enrichment box in its general review (pp.100–104). By the end of this lesson you will know the reason before you even start walking.

## Then the explanation

## Sub lesson 1 — Graphs, Vertices, Edges and Degrees

**Graphs, vertices and edges.** A graph is dots and lines: the dots are **vertices**, the lines are **edges**. The number of vertices is the graph's **order**; the number of edges is its **size**. An edge that starts and ends at the same vertex is a **loop**; two vertices may be joined by more than one edge. Iran's book builds this vocabulary step by step (pp.34–37), together with Sheikh Baha'i's three-houses-and-three-wells puzzle as history (pp.32–33): can each house be joined to each well without the pipes crossing?

**Degree.** The **degree** of a vertex is the number of edges at it, with a loop counted twice. The biggest degree in the graph is written Δ(G) and the smallest δ(G). Iran's book also builds the **complement graph** — same vertices, edges exactly where the original has none — and the **complete graph** K_p, where every pair of vertices is joined; its exercises include working backwards from "K_p has 36 edges" to p = 9 (pp.34–42).

Tip — from us, not from the books. When you draw a graph, write each degree in pencil beside its vertex as you go. Half of all graph mistakes are degree mistakes, and the pencil numbers catch them early.

**The handshaking lemma.** Add up all the degrees. Every edge has two ends, so it is counted exactly twice: **the sum of the degrees = 2 × (number of edges)**. Iran's book proves this (p.40) and proves its corollary from it: **the number of vertices of odd degree is always even**. A graph with exactly one odd vertex cannot exist — a quick lie-detector for degree lists.

## Sub lesson 2 — Paths, Euler Paths, Hamilton Paths and Shortest Paths

**Paths and cycles.** A **path** walks along edges without repeating a vertex; a **cycle** is a path that comes home. A graph is **connected** if you can walk from any vertex to any other, and disconnected if it falls into separate pieces (Iran, pp.38–39).

**Euler paths.** An **Euler path** uses every EDGE exactly once. Vietnam's Grade 11 study book teaches Euler paths in Bài 9 (p.41): a connected graph has an Euler trail exactly when it has zero or two vertices of odd degree — zero, and the trail comes home; two, and it starts at one odd vertex and ends at the other. Now Königsberg explains itself: all four land masses have odd degree, so no Euler trail exists. Jordan's Business Mathematics book teaches the same ground as "Euler graphs" (Grade 12 Term 1, Unit 2, Lesson 5, p.107), after building graphs and their special types (Lessons 3–4, pp.83–106).

**Hamilton paths.** A **Hamilton path** visits every VERTEX exactly once — the edges it does not use simply do not matter. Vietnam teaches Hamilton paths beside Euler paths (Bài 9, p.41). Keep the two apart the Vietnamese way: Euler counts edges, Hamilton counts vertices. There is no neat degree test for Hamilton paths; you search, carefully and systematically.

**Shortest paths.** Give each edge a length — a road's kilometres, a journey's minutes. The **shortest path** between two vertices is the route whose lengths add to the least total. Vietnam's Bài 10 (p.46) works the problem of finding the optimal (shortest) path in simple cases: build the total route by route, or grow the known-shortest distances step by step, and never trust a route just because its first step looks short.

## Sub lesson 3 — Algorithms, Bin Packing and Dominating Sets

**Algorithms and bin packing.** An **algorithm** is a list of steps that always works the same way. Jordan's book teaches algorithms first (Unit 2, Lesson 1, p.58), then **bin-packing algorithms** (Lesson 2, p.68): items of different sizes must go into bins of one fixed size, using as few bins as possible. In **first-fit**, each item goes into the first bin that has room for it. In **first-fit decreasing**, you sort the items biggest first, then first-fit them — big items are placed while the bins are still empty, and fewer bins are usually wasted.

**Dominating sets.** Iran's second graph lesson develops one idea deeply (pp.43–54): placing things — ATMs, radio stations, guards — so that every vertex is covered. A **dominating set** is a set of vertices D such that every vertex of the graph is in D or joined to a vertex in D. A dominating set is **minimal** if removing any vertex breaks it, and **minimum** if no dominating set is smaller. The size of a minimum dominating set is the **domination number**, γ(G). Iran motivates it with ATMs, radio stations and guards (pp.43–48) and gives a bound to aim at: since each chosen vertex covers itself and at most Δ neighbours, γ(G) ≥ ⌈n/(Δ+1)⌉ (p.49). Its worked graphs find γ = 2 for one pictured graph (p.49) and γ = 4 for a 14-vertex graph, where the bound alone gives only ⌈14/6⌉ = 3 and case analysis lifts it to 4 (p.51). Exercises ask when γ(G) = 1 (exactly when some vertex is joined to every other) and for the domination numbers of paths and cycles (pp.52–54).

## Say it to your companion
Explain, in your own words: "An Euler path cares about edges; a Hamilton path cares about vertices." Give your companion the Königsberg graph and ask: "Euler trail — yes or no, and why?" Then swap: they explain what a dominating set is, using guards on a drawing, and you check them.

## Do It Yourself
1. Draw the graph of your own street or school route: 6–8 vertices, edges for the paths between them. Write every degree, and check the degrees add to twice the number of edges (Iran, pp.34–40).
2. Count the odd-degree vertices of your graph. Say whether an Euler trail exists, and if it does, trace one (Vietnam, Bài 9, p.41).
3. Put lengths on your edges and find the shortest route from home to school two different ways; compare the totals (Vietnam, Bài 10, p.46).
4. Pack these items into bins of size 10 by first-fit, then by first-fit decreasing: 6, 5, 4, 7, 3, 2, 8. Count the bins each method uses (Jordan, pp.68–82).
5. For your street graph, find a smallest dominating set and compare its size with ⌈n/(Δ+1)⌉ (Iran, pp.43–49).
