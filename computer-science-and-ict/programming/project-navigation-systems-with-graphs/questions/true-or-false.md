# Project — Navigation Systems with Graphs — true or false

Say whether each statement is true or false.

**1. A navigation graph keeps everything shown on the map.**
**Answer: False** — It keeps junctions and road pieces only; the rest is thrown away.

**2. The shortest route and the fastest route are always the same route.**
**Answer: False** — They differ whenever a longer road is quicker — different weights, different answers.

**3. A real navigation system re-runs its search when you leave the route.**
**Answer: True** — Re-routing is one of the production system's extra jobs.

**4. Dijkstra's algorithm is what answers the route request in this project.**
**Answer: True** — The heart of the system is a shortest-path search on the weighted road graph.
