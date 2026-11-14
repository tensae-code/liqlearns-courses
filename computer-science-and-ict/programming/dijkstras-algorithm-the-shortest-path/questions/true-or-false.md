# Dijkstra's Algorithm — the Shortest Path — true or false

Say whether each statement is true or false.

**1. (Sub lesson 2) Once a node is settled, its distance can still fall later.**
**Answer: False** — Settled means final — the greedy proof guarantees no later route beats it.

**2. (Sub lesson 1) A tentative distance can fall several times before its node is settled.**
**Answer: True** — In the example A fell 4 → 3, C fell 6 → 4 and T fell 10 → 7 before settling.

**3. (Sub lesson 2) Breadth-first search is Dijkstra's algorithm with every weight equal to 1.**
**Answer: True** — With unit weights, settling order is the layer order and distances count edges.

**4. (Sub lesson 1) Dijkstra's algorithm tries every possible route and picks the best.**
**Answer: False** — It never enumerates routes; it settles nodes one by one with the greedy step.
