# Depth-First Search

## Do it first

depth-first search — traversing a graph by plunging down one path as far as it goes, then backtracking and plunging down the next (Vietnam Grade 12 specialist, CS)

## Sub lesson 1 — Down one path to the end — then back

**Depth-first search** (duyệt theo chiều sâu, DFS) explores a graph the way a determined walker explores a cave: from the start vertex, follow **one path as deep as it goes** — vertex to unvisited neighbour to the next — until no new vertex can be reached; then **backtrack** along the path to the last vertex with an untried edge, and plunge again. Every vertex is **marked visited** when first reached, so none is explored twice. Vietnam's specialist book pairs DFS with its breadth-first twin and drills both, because choosing between them is a working skill.

In your mind's eye: down one path to the end — then back.

## Sub lesson 2 — The stack underneath — and when DFS is the right tool

DFS's memory is a **stack** — the path's vertices are pushed as the search descends and popped as it retreats (recursion hides the same stack inside the calls). DFS is the right tool when the job is about **reachability and structure**: can this vertex be reached at all, is the graph connected, is there a cycle, can these tasks be ordered so each comes after its dependencies? Its weakness is the mirror of its strength: it may dive deep past a solution that lay near the start — that shallower hunt is breadth-first search's.

In your mind's eye: the stack underneath — and when DFS is the right tool.

## Say it to your companion

Tell your companion, in your own words: **Depth-first search** (duyệt theo chiều sâu, DFS) explores a graph the way a determined walker explores a cave: from the start vertex, follow **one path as deep as it goes** — vertex to unvisited neighbour to the next — until no new vertex can be reached; then **backtrack** along the path to the last vertex with an untried edge, and plunge again. Every vertex is **marked visited** when first reached, so none is explored twice. Vietnam's specialist book pairs DFS with its breadth-first twin and drills both, because choosing between them is a working skill. DFS's memory is a **stack** — the path's vertices are pushed as the search descends and popped as it retreats (recursion hides the same stack inside the calls). DFS is the right tool when the job is about **reachability and structure**: can this vertex be reached at all, is the graph connected, is there a cycle, can these tasks be ordered so each comes after its dependencies? Its weakness is the mirror of its strength: it may dive deep past a solution that lay near the start — that shallower hunt is breadth-first search's. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Follow one path as deep as it goes, then backtrack and plunge down the next Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: When the current path can reach no new vertex Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The last vertex with an untried edge Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: So no vertex is explored twice Do this with a real example of your own and write or say how you know it is right.
