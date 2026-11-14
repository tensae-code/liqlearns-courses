# Video script — Graph Traversal Practice — Depth and Breadth Together

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The specialist book closes its graph strand with a **synthesis practical**: take one graph and traverse it **both ways**. **Depth-first** dives along one path, so its order lists a deep chain first; **breadth-first** spreads ring by ring around the start, so its order lists the near vertices first. Same graph, same start — **two different visit orders**, both complete, both correct. The practical's first skill is mechanical honesty: run each walk with its own memory (stack for depth, queue for breadth) and never let the two orders blur.
The comparison's point is choice. **Breadth-first** answers 'nearest' questions — its rings are distances, so the first time it reaches a vertex is by the **fewest edges**. **Depth-first** answers 'reachable and structured' questions — connectedness, cycles, orderings — and uses memory only along one path. The practical ends with mixed problems: for each, name the walk **before** running it, and give the reason in the problem's own words — the traversal is chosen by the question, never by habit.
