# Breadth-First Search

## Do it first

Stand at your front door and imagine exploring your streets fairly: first every crossing one street away, then every crossing two streets away, never running deep down one road while a nearer crossing waits unchecked. That fair, layer-by-layer search has a name and an exact method — breadth-first search — and this lesson works it by hand until the method is yours.

## Sub lesson 1 — Visiting layer by layer — the queue at work

**Breadth-first search** (Breitensuche) visits a graph the way ripples spread from a stone dropped in water: ring by ring. It needs one tool — a **queue**, a line where new nodes join at the back and the next node to work on leaves from the front, first in, first out.

Start with the graph A joined to B and C; B joined to D and E; C joined to F. Search from A. Put A in the queue and mark it visited. Take A from the front; its unvisited neighbours B and C join the back — queue: B, C. Take B; its unvisited neighbours D and E join — queue: C, D, E. Take C; F joins — queue: D, E, F. Then D, E, F come off one by one with nothing new to add. The visiting order is A, B, C, D, E, F — layer 0, then layer 1 (B, C), then layer 2 (D, E, F).

[Picture — breadth-first-search-layers: the graph drawn in three shaded layers around the start node, with the queue shown as a line of boxes underneath]

Two rules do all the work. A node is **marked the moment it enters the queue**, not when it leaves it — otherwise the same node could be queued twice by two neighbours in the same layer. And the queue's order is never broken: first in, first out is what keeps the layers fair.

## Sub lesson 2 — What breadth-first search gives you — distances and uses

Breadth-first search hands you more than an order. Because it moves layer by layer, **the layer in which a node is first reached is its shortest distance, counted in edges, from the start** — F is 2 edges from A, and no 1-edge route to F exists, or F would have been found in layer 1. If, when a node is queued, you also note **who queued it** (its parent), you can walk the parents backwards from any node to the start and read off a shortest path: F ← C ← A.

That guarantee is why this search is used wherever 'nearest' matters in an unweighted network: the fewest stops between two stations, the smallest number of handshakes joining two people, everyone reachable within three steps of a post, a web crawler taking pages link-layer by link-layer.

[Picture — breadth-first-search-parents: the same graph with a parent arrow on each node pointing one step closer to the start, and one shortest path traced back]

Its opposite habit is worth naming: a **depth-first** wander runs down one branch as far as it can before coming back. Depth-first has its own uses, but it gives no shortest-path promise — the first route it finds to a node may be a long way round. Breadth-first's queue is the price of the promise.

## Say it to your companion

Tell your companion, in your own words: breadth-first search visits layer by layer using a queue — first in, first out; a node is marked when it enters the queue; the layer a node is found in is its shortest distance in edges from the start. Act out one tiny search together as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: carry out breadth-first search on a small graph, in order, using a queue. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: give each node's distance (in edges) from the start, and a shortest path to it. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: name what breadth-first search is used for, and how it differs from wandering depth-first. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
