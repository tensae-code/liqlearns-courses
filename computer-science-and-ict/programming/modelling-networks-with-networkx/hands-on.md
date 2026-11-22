# Hands-on — Modelling Networks with NetworkX

The lesson with your hands and your feet, not only your eyes.

## Build both kinds
In Python with networkx, build the seven-pupil friendship graph from the measures lesson as a Graph, from lists of nodes and edges. Then invent a following relation among the same seven (at least eight one-way arrows, not all returned) and build it as a DiGraph. Print each graph’s edges and confirm the directed one kept the arrows one-way.

## Verify, then trust
Call nx.center, nx.radius and nx.diameter on the friendship graph and compare with the hand results from the measures lesson (centre among B, C, D, F; radius 3; diameter 5). If they differ, find whether the error is in your code’s edge list or in your hand work — one of them is wrong, and the hunt is the lesson.
