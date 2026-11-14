# Video script — Dijkstra's Algorithm — the Shortest Path

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Every road has a price. We want the cheapest route — not the one with fewest roads.

Each town gets a price tag: what it costs to reach it, so far. The start is 0. The rest: unknown.

Settle the cheapest unsettled town. Its price is final.

From it, try to beat its neighbours' price tags. If you can, the tag falls.

Again and again, cheapest first — that is Dijkstra's algorithm.

Follow the parents back, and the cheapest route stands there, edge by edge.
