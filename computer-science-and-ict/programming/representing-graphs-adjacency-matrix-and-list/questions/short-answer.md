# Representing Graphs — Adjacency Matrix and List — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does the adjacency matrix store?**
**Answer: An n × n table — 1 where an edge joins the row and column vertices, else 0**

**2. (Sub lesson 1) How fast is 'are these two joined?'**
**Answer: One look — a single cell**

**3. (Sub lesson 1) How are a vertex's neighbours found in the matrix?**
**Answer: They are the 1s in its row**

**4. (Sub lesson 1) What does the matrix always cost?**
**Answer: n² cells, however few edges the graph has**

**5. (Sub lesson 1) For an undirected graph, what symmetry does the matrix show?**
**Answer: It mirrors across the diagonal — cell (u,v) equals cell (v,u)**

**6. (Sub lesson 2) What does the adjacency list store?**
**Answer: For each vertex, the list of its neighbours**

**7. (Sub lesson 2) What does the list cost?**
**Answer: About n + 2E entries — it follows the edges**

**8. (Sub lesson 2) Which graphs does the list suit?**
**Answer: Sparse graphs — few edges**

**9. (Sub lesson 2) What is the list's weakness?**
**Answer: Testing one pair's edge means searching a neighbour list**

**10. (Sub lesson 2) What is the practical's rule?**
**Answer: Many edges or edge-questions: matrix. Few edges or neighbour-walks: list**
