# Video script — Merge Sort

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Merge sort** (sắp xếp trộn) sorts the divide-and-conquer way. **Split** the list into two halves, split each half again, and keep splitting until every piece holds **one item** — a one-item list is already sorted. The splitting does no comparing at all; it is pure division, halving the problem until the pieces are trivial. Vietnam's specialist book teaches merge sort as the technique's showpiece: the problem is conquered not by working harder on the whole, but by reaching pieces too small to be unsorted.
The way back up is the **merge**: take two neighbouring sorted pieces and build one sorted list from them by repeatedly **taking the smaller of their two front items**. When one piece empties, the other's rest follows in order. Merging two pieces of total length n takes n takings — and because the halves were each sorted the same way, the joined list is sorted whole. The book's cost remark: merge sort does about **n log n** work — splitting gives log n levels, each level merges everything once.
