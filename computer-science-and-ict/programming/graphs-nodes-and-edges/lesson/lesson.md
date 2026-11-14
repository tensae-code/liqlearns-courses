# Graphs — Nodes and Edges

## Do it first

Think of six friends and who knows whom. Try to draw all of it on paper at once: names everywhere, lines crossing lines, and soon you cannot tell who is connected to whom. Keep the tangle in front of you. This lesson shows the tidy drawing — the graph — that computers use for exactly this job, from friendship networks to road maps.

## Sub lesson 1 — From a tangle of relationships to a graph

A **graph** throws away everything about a web of relationships except the connections themselves. Each person, place or thing becomes a **node** — just a point, drawn as a small circle. Each relationship becomes an **edge** — a line joining two nodes. In the book's words, the chapter opens by showing relationship networks (Beziehungsgeflechte) clearly: the drawing is clear precisely because it keeps so little.

Take six friends — Ana, Ben, Cy, Di, Eli, Fay — where Ana knows Ben and Cy, Ben knows Cy and Di, Di knows Eli, and Eli knows Fay. The graph has six nodes and six edges: Ana–Ben, Ana–Cy, Ben–Cy, Ben–Di, Di–Eli and Eli–Fay. Draw it twice, once with the names in a circle and once in a straight line with the edges curving. The two drawings look different, but they are **the same graph**, because the same pairs are joined. In a graph, position means nothing; connection means everything.

[Picture — graphs-nodes-edges: the same friendship graph drawn two ways, in a circle and in a line, with the same edges in both]

Two special edges complete the picture. A **loop** is an edge that leaves a node and comes straight back to the same node. Two nodes can also be joined by **more than one edge** — think of two towns joined by both a road and a railway. Ordinary school graphs often leave loops and double edges out, but a real network may need them, so the names are worth having from the start.

## Sub lesson 2 — Reading a graph — direction, degree, paths

Some relationships run one way. If Ana follows Ben online, Ben may not follow Ana back. A graph for that needs **directed edges** — edges drawn as arrows that point the way the relationship runs — and the graph is a **directed graph**. Friendships and roads (usually) run both ways: their edges have no arrows, and the graph is **undirected**. Choosing between them is the first modelling question: does this connection work in both directions, or only one?

The **degree** of a node is how many edges meet at it. In the friendship graph, Ben has degree 3 (edges to Ana, Cy and Di), Fay has degree 1, and a node of degree 0 would be an island — connected to nobody. Degree is the fastest first fact about a node: a station with degree 6 is a hub; a person with degree 1 hangs on the edge of the network.

[Picture — graphs-degree-and-path: the friendship graph with Ben's three edges highlighted, and one path from Ana to Fay lit up step by step]

A **path** is a walk from node to node along edges, never lifting the pencil: Ana → Ben → Di → Eli → Fay is a path of length 4 (four edges). Two nodes are **connected** if a path joins them — in our graph every pair is connected, so the whole graph is one connected piece. A path that comes back to its start is a **cycle**: Ana → Ben → Cy → Ana is a cycle of length 3. Paths, connection and cycles are the questions every later lesson in this strand answers with machinery: the matrix stores the graph, breadth-first search walks it in order, and Dijkstra finds its cheapest path.

## Say it to your companion

Tell your companion, in your own words: a graph keeps only connections — nodes joined by edges; directed edges run one way, undirected edges both ways; the degree of a node counts its edges; a path walks along edges from node to node. Draw your companion a small graph of your own as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: draw a graph from a list of relationships, naming its nodes and edges. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: say whether a graph is directed or undirected, and give the degree of a node. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: follow a path through a graph, and say whether two nodes are connected and whether a route is a cycle. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
