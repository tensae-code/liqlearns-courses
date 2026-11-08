# Graph theory — ordering

Sub-lesson markers (2026-11-08 restructure): every item's marker names the sub lesson it belongs to. The files' old depth groups map onto the sub lessons as: (Level 1) -> Sub lesson 1 — Graphs, Vertices, Edges and Degrees · (Level 2) -> Sub lesson 2 — Paths, Euler Paths, Hamilton Paths and Shortest Paths · (Level 3) -> Sub lesson 3 — Algorithms, Bin Packing and Dominating Sets.

Put the steps in the right order.

**1. (Sub lesson 2)** Order the steps for deciding whether an Euler trail exists: (a) count the odd-degree vertices, (b) draw the graph, (c) if the count is 0 or 2 and the graph is connected, answer yes.
**Answer:** (b), (a), (c) — draw, count odd degrees, then apply the test (Vietnam, Bài 9, p.41).

**2. (Sub lesson 3)** Order first-fit decreasing: (a) place each item in the first bin with room, (b) sort the items biggest first, (c) open bin 1.
**Answer:** (b), (c), (a) — sort first, then first-fit (Jordan, p.68).

**3. (Sub lesson 3)** Order the hunt for γ(G): (a) compute the bound ⌈n/(Δ+1)⌉, (b) try to build a dominating set of that size, (c) if you build one, it is minimum — stop.
**Answer:** (a), (b), (c) — bound first, then construction (Iran, pp.49–51).
