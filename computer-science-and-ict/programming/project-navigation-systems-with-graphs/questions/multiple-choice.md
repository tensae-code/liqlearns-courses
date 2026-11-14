# Project — Navigation Systems with Graphs — multiple choice

Pick the one right answer.

**1. In a navigation graph, the nodes are —**
a) Every house  b) Junctions and start/end places  c) Every tree  d) The street names
**Answer: b) Junctions and start/end places** — Nodes are where routes can start, turn or end — the crossings.

**2. Weighting edges by driving time instead of length makes the system find —**
a) The prettiest route  b) The fastest route, which can differ from the shortest  c) The oldest route  d) No route
**Answer: b) The fastest route, which can differ from the shortest** — The weight must match the question asked.

**3. A one-way street is modelled as —**
a) A loop  b) A directed edge  c) Two edges  d) A node
**Answer: b) A directed edge** — One-way travel runs one direction only — an arrow.

**4. When your hand-run route disagrees with how locals actually travel, the fault is usually in —**
a) Dijkstra's algorithm  b) The model — a missing path or a wrong weight  c) The pencil  d) The map's colours
**Answer: b) The model — a missing path or a wrong weight** — The algorithm is exact on the graph it is given; modelling is where errors live.

**5. Live traffic changes a route by —**
a) Moving the roads  b) Re-weighting the edges, so the search prefers other roads  c) Adding nodes  d) Deleting the destination
**Answer: b) Re-weighting the edges, so the search prefers other roads** — Same graph heart; new weights, new cheapest path.

**6. Turn-by-turn instructions are —**
a) A new search  b) The found path translated back into street names and turns  c) A photograph  d) The adjacency matrix read aloud
**Answer: b) The found path translated back into street names and turns** — Instructions are presentation of the path, one edge at a time.
