# Modelling Networks with NetworkX

## Do it first

In the graph-measures lesson you measured a class network by hand: waves, eccentricities, centre, diameter. It took care and time for eighteen pupils. A real platform holds millions. Suppose you had a tireless assistant who understands exactly three orders: "add these people", "join these pairs", "measure it". Write down, in plain words, the orders you would give to rebuild the seven-pupil graph from the measures lesson and get its centre and diameter. Keep your list — the lesson introduces the Python library whose commands are almost exactly your orders.

## Sub lesson 1 — Building directed and undirected graphs in Python

**networkx** is Python’s graph library, and building with it follows your assistant orders closely. `import networkx as nx` brings it in. `G = nx.Graph()` creates an empty **undirected** graph — the friendship kind, where an edge joins two nodes symmetrically. Nodes and edges go in from lists: `G.add_nodes_from([...])`, `G.add_edges_from([("A","B"), ("A","C"), ...])`. For relations with a direction, the class is `nx.DiGraph()`: the edge ("A","B") then means A → B only — A **follows** B — and ("B","A") would be a separate fact. That single choice, Graph or DiGraph, is the modelling decision of the whole lesson: France’s SNT book builds both — a Twitter-type network of followings as directed, a Facebook-type network of friendships as undirected — because the relation decides the mathematics that follows.

In your mind's eye: the same five people drawn twice. Once with two-headed friendship edges, once with one-way follow arrows, the code class under each.

## Sub lesson 2 — Measuring the network with the machine

Once built, the graph answers the measures lesson’s questions in single calls: `nx.center(G)`, `nx.radius(G)`, `nx.diameter(G)` — the very numbers you sweated over by hand, returned instantly, and correct for graphs of thousands of nodes where hand waves would take weeks. The book’s discipline is the professional one: **verify on the small before trusting on the large**. Build the seven-pupil graph from the measures lesson, call the three functions, and check the answers against your hand work — centre, radius 3, diameter 5. Only then point the same calls at a network too big to check, and believe them. The library does not replace the earlier lesson; it is why the earlier lesson mattered — you cannot judge a machine’s answer about a concept you have never computed yourself.

In your mind's eye: a small graph and a vast graph side by side, the same three function calls written under both, the small one ticked "checked by hand".

## Say it to your companion

Tell your companion, in your own words: networkx builds a graph from nodes and edges in code; DiGraph for one-way relations like following, Graph for mutual ones like friendship; and nx.center, nx.radius and nx.diameter compute the measures of the earlier lesson at any scale — after you have verified them on a graph you measured by hand. Name the fork — Graph or DiGraph — for two relations as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: build an undirected graph in networkx from lists of nodes and edges. Do this with a real example of your own — in a real Python program with networkx, starting from the graph you measured by hand — and write or say how you know it is right.
2. Show it, don't just say it: build a directed graph for a following relation and explain how its edges differ. Do this with a real example of your own — in a real Python program with networkx, starting from the graph you measured by hand — and write or say how you know it is right.
3. Show it, don't just say it: compute centre, radius and diameter with networkx calls. Do this with a real example of your own — in a real Python program with networkx, starting from the graph you measured by hand — and write or say how you know it is right.
4. Show it, don't just say it: verify the machine’s measures against a hand-measured graph before trusting them on a large one. Do this with a real example of your own — in a real Python program with networkx, starting from the graph you measured by hand — and write or say how you know it is right.
