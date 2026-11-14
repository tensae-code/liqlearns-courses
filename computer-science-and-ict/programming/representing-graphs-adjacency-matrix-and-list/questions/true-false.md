# Representing Graphs — Adjacency Matrix and List — true or false

Say true or false, and fix the false ones in your own words.

**1. (Sub lesson 1) True or false: An n × n table — 1 where an edge joins the row and column vertices, else 0**
**Answer: True**

**2. (Sub lesson 1) True or false: An n × n table — 1 where an edge joins the row and column vertices, else 0** — as the answer to: How fast is 'are these two joined?'
**Answer: False — One look — a single cell**

**3. (Sub lesson 1) True or false: They are the 1s in its row**
**Answer: True**

**4. (Sub lesson 1) True or false: They are the 1s in its row** — as the answer to: What does the matrix always cost?
**Answer: False — n² cells, however few edges the graph has**

**5. (Sub lesson 1) True or false: It mirrors across the diagonal — cell (u,v) equals cell (v,u)**
**Answer: True**

**6. (Sub lesson 2) True or false: It mirrors across the diagonal — cell (u,v) equals cell (v,u)** — as the answer to: What does the adjacency list store?
**Answer: False — For each vertex, the list of its neighbours**

**7. (Sub lesson 2) True or false: About n + 2E entries — it follows the edges**
**Answer: True**

**8. (Sub lesson 2) True or false: About n + 2E entries — it follows the edges** — as the answer to: Which graphs does the list suit?
**Answer: False — Sparse graphs — few edges**

**9. (Sub lesson 2) True or false: Testing one pair's edge means searching a neighbour list**
**Answer: True**

**10. (Sub lesson 2) True or false: Testing one pair's edge means searching a neighbour list** — as the answer to: What is the practical's rule?
**Answer: False — Many edges or edge-questions: matrix. Few edges or neighbour-walks: list**
