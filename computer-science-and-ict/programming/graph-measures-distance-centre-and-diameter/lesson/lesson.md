# Graph Measures — Distance, Centre and Diameter

## Do it first

Here is a friendship graph: seven pupils, an edge wherever two are friends. A is friends with B and C. B with A, C and D. C with A, B and E. D with B and F. E with C and F. F with D, E and G. G only with F. Someone says "B is in the middle of this network" and someone else says "F is". Without any definition, who do you believe — and what would "middle" even mean, in numbers? Write your guess and your reason. Keep them — the lesson builds the measuring tools, applies them to this very graph, and settles the argument.

## Sub lesson 1 — Distance and eccentricity

Measuring a graph starts with **distance**: between two nodes, count the edges on a **shortest path** joining them. To find all distances from one node, spread out in waves: the node itself is at distance 0; its neighbours at 1; their other neighbours at 2; and so on, each node labelled the first time the wave reaches it — the wave cannot arrive later by a shorter road, because it expands one edge at a time. On the Do it first graph, from B: A, C, D at 1; E and F at 2 (through C and D); G at 3. The largest of a node’s distances is its **eccentricity** — how far that node sits from the farthest corner of its world. B’s eccentricity is 3, set by distant G.

In your mind's eye: the seven-pupil graph with waves of colour spreading from B. Distance 0, then 1, then 2, then 3 at G.

## Sub lesson 2 — Centre, radius and diameter — and small worlds

Now measure the whole graph. Every node has an eccentricity; the smallest of them belongs to the **centre** — the node that minimises the worst journey, the true "middle" the argument in Do it first needed. That smallest eccentricity has its own name: the **radius**. The largest distance between any two nodes is the **diameter** — the graph’s longest shortest journey, its real width. On our graph: eccentricities run from 3 (B, C, D, F) up to 4 (A, E) and 5 (G, out on its stalk). The radius is 3, the centre is shared by B, C, D and F — and the diameter is 5, the A-to-G and E-to-G journeys. Both arguers were partly right; the numbers say precisely how.

Then the astonishment the SNT book ends with: real social graphs are vast yet their diameters are tiny. Milgram’s 1960s letter experiment suggested about **six degrees of separation** between strangers; measured on Facebook’s whole graph, the average distance came out at **4.74**. Hubs — the few nodes with enormous numbers of edges — shrink the world: almost everyone is a few handshakes from almost everyone else.

In your mind's eye: a huge crowd of dots joined by edges, with one short highlighted path of five edges joining two distant strangers.

## Say it to your companion

Tell your companion, in your own words: distance is the shortest path’s length; eccentricity is a node’s greatest distance; the centre has the smallest eccentricity, which is the radius; the diameter is the greatest distance of all — and real social networks, though vast, have tiny diameters, about six degrees or fewer. Measure one node’s eccentricity on the class graph aloud as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: compute all distances from one node of a small graph by spreading out in waves. Do this with a real example of your own — on a graph you draw yourself — your own friendship circle, anonymised — and write or say how you know it is right.
2. Show it, don't just say it: state a node’s eccentricity and say what sets it. Do this with a real example of your own — on a graph you draw yourself — your own friendship circle, anonymised — and write or say how you know it is right.
3. Show it, don't just say it: find a small graph’s centre, radius and diameter and defend each answer. Do this with a real example of your own — on a graph you draw yourself — your own friendship circle, anonymised — and write or say how you know it is right.
4. Show it, don't just say it: explain the claim of six degrees of separation and the measured Facebook figure. Do this with a real example of your own — on a graph you draw yourself — your own friendship circle, anonymised — and write or say how you know it is right.
