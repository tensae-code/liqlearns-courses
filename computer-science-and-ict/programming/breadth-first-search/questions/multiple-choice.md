# Breadth-First Search — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) Breadth-first search visits nodes —**
a) In alphabetical order  b) Layer by layer, nearest first  c) Deep down one branch first  d) At random
**Answer: b) Layer by layer, nearest first** — Breadth-first search finishes each layer before starting the next.

**2. (Sub lesson 1) The data structure breadth-first search uses is —**
a) A stack  b) A queue — first in, first out  c) A matrix  d) A tree
**Answer: b) A queue — first in, first out** — The queue's first-in-first-out order is what keeps the layers fair.

**3. (Sub lesson 1) A node must be marked visited —**
a) When it leaves the queue  b) At the very end  c) The moment it enters the queue  d) Never
**Answer: c) The moment it enters the queue** — Marking on entry stops two neighbours queueing the same node twice.

**4. (Sub lesson 1) In the lesson's search from A, the visiting order is —**
a) A, D, E, B, C, F  b) A, B, C, D, E, F  c) A, B, D, E, C, F  d) A, C, F, B, D, E
**Answer: b) A, B, C, D, E, F** — Layer 0: A; layer 1: B, C; layer 2: D, E, F — in queue order.

**5. (Sub lesson 2) The layer in which a node is first reached tells you —**
a) Its degree  b) Its shortest distance in edges from the start  c) Its weight  d) Nothing
**Answer: b) Its shortest distance in edges from the start** — Layers are distances: layer k means k edges from the start, and no shorter route exists.

**6. (Sub lesson 2) To rebuild a shortest path to a node, you follow —**
a) The alphabet  b) The parent notes — who queued whom — backwards to the start  c) The diagonal  d) The weights
**Answer: b) The parent notes — who queued whom — backwards to the start** — Each node's parent is one step closer to the start, so parents chain into a shortest path.
