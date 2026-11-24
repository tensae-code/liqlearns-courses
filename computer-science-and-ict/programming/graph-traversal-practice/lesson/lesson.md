# Graph Traversal Practice — Depth and Breadth Together

## Do it first

graph traversal practice — running depth-first and breadth-first traversal over the same graph, comparing their orders, and choosing the traversal a problem needs (Vietnam Grade 12 specialist, CS)

## Sub lesson 1 — One graph, two walks — the orders differ

The specialist book closes its graph strand with a **synthesis practical**: take one graph and traverse it **both ways**. **Depth-first** dives along one path, so its order lists a deep chain first; **breadth-first** spreads ring by ring around the start, so its order lists the near vertices first. Same graph, same start — **two different visit orders**, both complete, both correct. The practical's first skill is mechanical honesty: run each walk with its own memory (stack for depth, queue for breadth) and never let the two orders blur.

In your mind's eye: one graph, two walks — the orders differ.

## Sub lesson 2 — Choosing the walk — what the problem asks decides

The comparison's point is choice. **Breadth-first** answers 'nearest' questions — its rings are distances, so the first time it reaches a vertex is by the **fewest edges**. **Depth-first** answers 'reachable and structured' questions — connectedness, cycles, orderings — and uses memory only along one path. The practical ends with mixed problems: for each, name the walk **before** running it, and give the reason in the problem's own words — the traversal is chosen by the question, never by habit.

In your mind's eye: choosing the walk — what the problem asks decides.

## Say it to your companion

Tell your companion, in your own words: The specialist book closes its graph strand with a **synthesis practical**: take one graph and traverse it **both ways**. **Depth-first** dives along one path, so its order lists a deep chain first; **breadth-first** spreads ring by ring around the start, so its order lists the near vertices first. Same graph, same start — **two different visit orders**, both complete, both correct. The practical's first skill is mechanical honesty: run each walk with its own memory (stack for depth, queue for breadth) and never let the two orders blur. The comparison's point is choice. **Breadth-first** answers 'nearest' questions — its rings are distances, so the first time it reaches a vertex is by the **fewest edges**. **Depth-first** answers 'reachable and structured' questions — connectedness, cycles, orderings — and uses memory only along one path. The practical ends with mixed problems: for each, name the walk **before** running it, and give the reason in the problem's own words — the traversal is chosen by the question, never by habit. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Both traversals — depth-first and breadth-first Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A deep chain first — one path followed to its end Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Ring by ring — the near vertices first Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A stack for depth-first; a queue for breadth-first Do this with a real example of your own and write or say how you know it is right.
