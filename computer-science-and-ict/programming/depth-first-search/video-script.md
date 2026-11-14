# Video script — Depth-First Search

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Depth-first search** (duyệt theo chiều sâu, DFS) explores a graph the way a determined walker explores a cave: from the start vertex, follow **one path as deep as it goes** — vertex to unvisited neighbour to the next — until no new vertex can be reached; then **backtrack** along the path to the last vertex with an untried edge, and plunge again. Every vertex is **marked visited** when first reached, so none is explored twice. Vietnam's specialist book pairs DFS with its breadth-first twin and drills both, because choosing between them is a working skill.
DFS's memory is a **stack** — the path's vertices are pushed as the search descends and popped as it retreats (recursion hides the same stack inside the calls). DFS is the right tool when the job is about **reachability and structure**: can this vertex be reached at all, is the graph connected, is there a cycle, can these tasks be ordered so each comes after its dependencies? Its weakness is the mirror of its strength: it may dive deep past a solution that lay near the start — that shallower hunt is breadth-first search's.
