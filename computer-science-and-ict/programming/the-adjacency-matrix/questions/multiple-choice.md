# The Adjacency Matrix — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) In an adjacency matrix, the cell at row X, column Y holds 1 when —**
a) X and Y are the same node  b) An edge joins X and Y  c) X comes before Y  d) The graph is directed
**Answer: b) An edge joins X and Y** — 1 means edge, 0 means no edge — that is the whole rule.

**2. (Sub lesson 1) A weighted graph's matrix stores, instead of 1 —**
a) The node's name  b) The edge's weight  c) A letter  d) Nothing
**Answer: b) The edge's weight** — With weights, the cell carries the weight of the edge, e.g. a distance.

**3. (Sub lesson 2) The degree of a node can be read from its matrix as —**
a) The diagonal entry  b) The number of rows  c) The sum of its row  d) The sum of its column only
**Answer: c) The sum of its row** — Each 1 in the row is one edge at that node; the row sum is the degree.

**4. (Sub lesson 2) An undirected graph's adjacency matrix is always —**
a) Full of zeros  b) Symmetric across the diagonal  c) Triangular  d) Empty on the diagonal of every graph
**Answer: b) Symmetric across the diagonal** — Every undirected edge is stored from both ends, so the matrix mirrors.

**5. (Sub lesson 2) A matrix has a 1 at row A column B, but a 0 at row B column A. The graph is —**
a) Undirected  b) Weighted  c) Directed  d) Disconnected
**Answer: c) Directed** — The broken mirror is the arrow: the edge runs A to B only.

**6. (Sub lesson 2) Adding every entry of an undirected graph's matrix and dividing by 2 gives —**
a) The number of nodes  b) The number of edges  c) The highest degree  d) The number of paths
**Answer: b) The number of edges** — Each edge is written twice, once at each end, so half the total is the edge count.
