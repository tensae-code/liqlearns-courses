# Project — Navigation Systems with Graphs

## Do it first

Ask a phone for the way from home to school and a line appears in under a second — with a time, and often a warning about traffic. That speed hides a clean piece of machinery you have already met piece by piece in this strand. This project (the book's Vertiefung — its deepening chapter) assembles it: model the roads as a graph, then let the shortest-path search do the routing.

## Step 1 — Model the map

A navigation graph is not the whole map. Its **nodes** are the crossings and the places a route can start, turn or end — junctions, in short. Its **edges** are the road pieces between junctions. Everything else on the map — the park, the river, the pretty shading — is thrown away, exactly as the first lesson of this strand threw away everything except connections.

Then each edge gets its **weight**, and here the modelling choice matters: weight by **length** and the system finds the shortest route; weight by **driving time** and it finds the fastest — and the two answers genuinely differ. One-way streets become **directed edges**. Turn bans and closed roads delete or forbid edges. A real system re-weights its edges with live traffic, which is why your route home changes at rush hour while the map stays the same.

[Picture — navigation-graph-model: a small street map on the left dissolving into its graph on the right — junctions as nodes, road pieces as edges with minute-weights]

## Step 2 — Answer the request by hand

Take your neighbourhood graph — eight to twelve nodes is a good size — and run Dijkstra's algorithm from a start node, exactly as the last lesson taught: tentative distances, settle the cheapest, relax, note parents. Then answer three route requests from the parents the run leaves behind. Check each route against your own knowledge of the streets: does the machine's 'best' match the way a local would actually walk or drive? Where it does not, the fault is in the model — a missing path, a wrong weight — not in the algorithm. That chase, model → run → check → fix the model, is the real project skill.

## Step 3 — What the real system adds

A production navigation system adds jobs the hand project only points at: it must find the graph nodes nearest to a typed address (geocoding); it must speak or draw the path as turn-by-turn instructions ('in 200 metres, turn left'), which are the path's edges translated back into street names; it must re-run the search when you leave the route or when traffic re-weights the edges; and it must do all of this on a graph of millions of edges in well under a second, which is why real systems prepare shortcuts in the graph long before you ask. None of that changes the heart: **roads as a weighted graph, routes as shortest paths**.

## Say it to your companion

Tell your companion, in your own words: a navigation system models roads as a weighted graph — junctions are nodes, road pieces are edges weighted by length or time — and answers requests with a shortest-path search; the extra jobs are finding the start, turning the path into instructions, and re-routing when things change. Trace one route on your own project graph as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: turn a small road map into a weighted graph, choosing nodes, edges and weights sensibly. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: answer a route request on that graph with Dijkstra's algorithm and present the route. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: name the extra jobs a real navigation system does beyond the shortest path. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
