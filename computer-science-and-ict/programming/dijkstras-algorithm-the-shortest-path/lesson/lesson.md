# Dijkstra's Algorithm — the Shortest Path

## Do it first

When every edge has a price — minutes, kilometres, cost — 'shortest path' stops meaning 'fewest edges'. The direct road may climb a hill; the longer way round may be cheaper. Finding the truly cheapest route by trying every possibility explodes: too many routes even on a small map. This lesson works Dijkstra's algorithm, the book's method that finds the cheapest route to everywhere, one certain step at a time.

## Sub lesson 1 — The greedy step — tentative distances and settling

Give every node a **tentative distance**: the cheapest cost to reach it that you know *so far*. The start node begins at 0; every other node begins at infinity — nothing known yet. One node at a time is **settled**: among the unsettled nodes, pick the one with the smallest tentative distance and declare it final. Then **relax** its edges: for each neighbour, add this node's final distance to the edge's weight — if that sum beats the neighbour's tentative distance, the tentative distance falls to the sum, and you note this node as the neighbour's **parent**.

Work it on five towns. Edges: S–A 4, S–B 1, B–A 2, B–C 5, A–C 1, C–T 3, A–T 7. Start at S (tentative 0; all others ∞). Settle S: relax to A = 4, B = 1. Settle B (smallest, 1): A improves — 1 + 2 = 3 beats 4, so A = 3, parent B; C = 1 + 5 = 6. Settle A (3): C improves — 3 + 1 = 4 beats 6, parent A; T = 3 + 7 = 10. Settle C (4): T improves — 4 + 3 = 7 beats 10, parent C. Settle T (7). Done.

[Picture — dijkstra-settling: the five-town graph with the settling order numbered and each node's final distance in a box beside it]

Notice what the greedy step did: it never settled the merely *near* node — it settled the *cheapest so far*, and twice a node's price fell (A: 4 → 3, C: 6 → 4, T: 10 → 7) before it was settled. Tentative means exactly that: believed, not yet proven.

## Sub lesson 2 — Reading the answer — and why greedy is safe

The table at the end is the answer for every node at once: the cheapest cost from S is A 3, B 1, C 4, T 7. To get the **path** to T, follow the parents backwards: T ← C ← A ← B ← S, so the shortest route is S → B → A → C → T, costing 1 + 2 + 1 + 3 = 7 — not the 'obvious' direct-looking edges at all. Navigation systems run exactly this, on road graphs with millions of edges.

[Picture — dijkstra-shortest-path: the shortest route to T highlighted edge by edge, with its cost added up underneath]

Why may the settled node be declared final? Suppose a cheaper route to it existed that the algorithm had missed. That route must at some point step from the settled region into an unsettled node — and that unsettled node already has a tentative distance at least as large as the node being settled, while the step itself adds a weight that is **not negative**. So the 'cheaper' route cannot be cheaper. That argument is the whole proof, and it shows the one condition Dijkstra needs: **edge weights must never be negative**. With a negative edge, a later step could refund money, and a settled answer could be beaten — the algorithm is simply not promised there.

Breadth-first search, from the last lesson, is this same machine with every weight equal to 1: the queue was the settling order, and the layers were the distances.

## Say it to your companion

Tell your companion, in your own words: Dijkstra keeps a tentative distance for every node, settles the cheapest unsettled node, and relaxes its edges; a settled distance is final because no later route — through pricier nodes and never-negative edges — can beat it. Work one relaxation aloud together as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: carry out Dijkstra's algorithm on a small weighted graph, keeping the distance table. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: read the shortest path and its total cost from the parents the algorithm leaves behind. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: say why the greedy step is safe, and name the one condition the weights must meet. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
