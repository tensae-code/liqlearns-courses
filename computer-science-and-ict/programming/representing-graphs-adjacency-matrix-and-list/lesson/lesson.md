# Representing Graphs — Adjacency Matrix and List

## Do it first

representing graphs in a program — the adjacency matrix (a table of 1s and 0s) and the adjacency list (each vertex with its neighbours), and what each costs and buys (Vietnam Grade 12 specialist, CS)

## Sub lesson 1 — The matrix — the graph as a table

The **adjacency matrix** (ma trận kề) stores a graph of n vertices as an **n × n table**: the cell in row u, column v holds **1 if an edge joins u and v**, else 0. It answers 'are these two joined?' in one look, and a vertex's neighbours are its row's 1s. Its cost is fixed: **n² cells** whether the graph has many edges or few — a graph of a thousand vertices and a thousand edges still pays a million cells. Vietnam's specialist book sets this cost beside the list's, because representation is a choice with a price.

In your mind's eye: the matrix — the graph as a table.

[Picture 47582 — the matrix — the graph as a table]

## Sub lesson 2 — The list — each vertex with its neighbours

The **adjacency list** (danh sách kề) stores, for each vertex, a **list of its neighbours** — nothing more. Its cost follows the edges: memory about **n + 2E** entries for an undirected graph, so **sparse** graphs (few edges) are held cheaply, where the matrix would be mostly zeros. Its weakness is the matrix's strength: 'are u and v joined?' must **search u's list**, and listing all edges means walking every list. The practical's rule: many edges or edge-questions — matrix; few edges or neighbour-walks — list.

In your mind's eye: the list — each vertex with its neighbours.

[Picture 47583 — the list — each vertex with its neighbours]

## Say it to your companion

Tell your companion, in your own words: The **adjacency matrix** (ma trận kề) stores a graph of n vertices as an **n × n table**: the cell in row u, column v holds **1 if an edge joins u and v**, else 0. It answers 'are these two joined?' in one look, and a vertex's neighbours are its row's 1s. Its cost is fixed: **n² cells** whether the graph has many edges or few — a graph of a thousand vertices and a thousand edges still pays a million cells. Vietnam's specialist book sets this cost beside the list's, because representation is a choice with a price. The **adjacency list** (danh sách kề) stores, for each vertex, a **list of its neighbours** — nothing more. Its cost follows the edges: memory about **n + 2E** entries for an undirected graph, so **sparse** graphs (few edges) are held cheaply, where the matrix would be mostly zeros. Its weakness is the matrix's strength: 'are u and v joined?' must **search u's list**, and listing all edges means walking every list. The practical's rule: many edges or edge-questions — matrix; few edges or neighbour-walks — list. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: An n × n table — 1 where an edge joins the row and column vertices, else 0 Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: One look — a single cell Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: They are the 1s in its row Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: n² cells, however few edges the graph has Do this with a real example of your own and write or say how you know it is right.
