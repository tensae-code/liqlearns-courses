# Dijkstra's Algorithm — the Shortest Path — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) At the start of Dijkstra's algorithm, the tentative distance of every node except the start is —**
a) 0  b) 1  c) Infinity — nothing known yet  d) Its degree
**Answer: c) Infinity — nothing known yet** — Unknown means infinity until a route to the node is found.

**2. (Sub lesson 1) The next node to settle is the unsettled node with —**
a) The most edges  b) The smallest tentative distance  c) The largest tentative distance  d) The first letter
**Answer: b) The smallest tentative distance** — Greedy and exact: cheapest tentative first, and that distance is then final.

**3. (Sub lesson 1) Relaxing an edge from a settled node means —**
a) Deleting the edge  b) Checking whether going through this node beats the neighbour's tentative distance, and lowering it if so  c) Doubling the weight  d) Settling the neighbour at once
**Answer: b) Checking whether going through this node beats the neighbour's tentative distance, and lowering it if so** — Relaxation is the compare-and-lower step; the parent is noted when the distance falls.

**4. (Sub lesson 2) In the lesson's example, the cheapest cost from S to T is —**
a) 10  b) 8  c) 7  d) 4
**Answer: c) 7** — S → B → A → C → T costs 1 + 2 + 1 + 3 = 7.

**5. (Sub lesson 2) The shortest path itself is recovered by —**
a) Re-running the algorithm  b) Following the parents backwards from the target  c) Reading the diagonal  d) Sorting the nodes
**Answer: b) Following the parents backwards from the target** — Each parent is one step back along a cheapest route.

**6. (Sub lesson 2) Dijkstra's algorithm is promised to work only when —**
a) The graph is undirected  b) No edge weight is negative  c) All weights are equal  d) The graph has no cycles
**Answer: b) No edge weight is negative** — A negative edge could refund cost later and beat a settled answer, breaking the proof.
