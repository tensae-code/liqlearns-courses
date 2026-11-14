# The Adjacency Matrix

## Do it first

Take any small graph you have drawn and try to write it down as pure text that a computer could store — no picture allowed. A list of edges works, but it is slow to answer simple questions with: who are Ben's neighbours? This lesson shows the book's table for the job — the adjacency matrix — one row and one column for every node.

## Sub lesson 1 — Building the matrix from a graph

The **adjacency matrix** (Adjazenzmatrix) is the graph written as a table. Give every node one row and one column, in the same order down the side and across the top. In the cell where row X meets column Y, write **1 if an edge joins X and Y, and 0 if it does not**. That is the whole rule — the table is the graph, in a form a computer can store and search.

For the friendship graph with nodes Ana (A), Ben (B), Cy (C), Di (D) — edges A–B, A–C, B–C, B–D — the matrix is:

|  | A | B | C | D |
|---|---|---|---|---|
| **A** | 0 | 1 | 1 | 0 |
| **B** | 1 | 0 | 1 | 1 |
| **C** | 1 | 1 | 0 | 0 |
| **D** | 0 | 1 | 0 | 0 |

Read row B: 1, 0, 1, 1 — Ben is joined to Ana, Cy and Di, and not to himself. Two details complete the rule. The diagonal (A–A, B–B, …) is 0 unless the graph has a **loop**, which writes a 1 on the diagonal. And in a **weighted graph** — roads with distances, say — the cell stores the **weight** instead of 1, and 0 (or 'no entry') where there is no edge.

[Picture — the-adjacency-matrix: a small graph beside its adjacency matrix, with one edge and its two matching cells highlighted in the same colour]

## Sub lesson 2 — Reading the matrix — neighbours, degrees, symmetry

The matrix pays you back the moment you read it. The neighbours of a node are exactly the 1s in its **row**. The **sum of a row is the node's degree**: row B above sums to 3, and Ben's degree is 3. The whole graph's edge count hides here too — add up every entry in an undirected graph's matrix and divide by 2, because every edge was written twice, once at each end.

Look at the table once more: the entry at row A, column B equals the entry at row B, column A — 1 = 1. That is no accident. In an **undirected** graph every edge runs both ways, so the matrix is **symmetric**: it mirrors exactly across the diagonal. A program can check a matrix for symmetry to check that a graph really is undirected.

[Picture — adjacency-matrix-symmetry: the matrix folded along its diagonal, the two halves matching cell for cell]

A **directed** graph breaks the mirror. If the only edge runs A → B, the matrix holds a 1 at row A, column B but a 0 at row B, column A — the arrow lives in that difference. So the same one table serves both kinds of graph, and its symmetry — or its absence — tells you which kind you hold.

## Say it to your companion

Tell your companion, in your own words: the adjacency matrix stores a graph as a table — one row and column per node, 1 for an edge, 0 for none; a row lists the neighbours and its sum is the degree; an undirected graph's matrix is symmetric. Build a tiny matrix together as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: build the adjacency matrix of a small undirected graph, and of a weighted graph. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: read a graph back out of its matrix — edges, degrees and neighbours. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: say why an undirected graph's matrix is symmetric, and what a directed graph changes. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
