# Video script — Representing Graphs — Adjacency Matrix and List

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **adjacency matrix** (ma trận kề) stores a graph of n vertices as an **n × n table**: the cell in row u, column v holds **1 if an edge joins u and v**, else 0. It answers 'are these two joined?' in one look, and a vertex's neighbours are its row's 1s. Its cost is fixed: **n² cells** whether the graph has many edges or few — a graph of a thousand vertices and a thousand edges still pays a million cells. Vietnam's specialist book sets this cost beside the list's, because representation is a choice with a price.
The **adjacency list** (danh sách kề) stores, for each vertex, a **list of its neighbours** — nothing more. Its cost follows the edges: memory about **n + 2E** entries for an undirected graph, so **sparse** graphs (few edges) are held cheaply, where the matrix would be mostly zeros. Its weakness is the matrix's strength: 'are u and v joined?' must **search u's list**, and listing all edges means walking every list. The practical's rule: many edges or edge-questions — matrix; few edges or neighbour-walks — list.
