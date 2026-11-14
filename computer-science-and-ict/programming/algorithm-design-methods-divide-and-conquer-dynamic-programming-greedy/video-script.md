# Video script — Algorithm Design Methods — Divide-and-Conquer, Dynamic Programming, Greedy

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Divide-and-conquer (διαίρει και βασίλευε)** splits a problem into **smaller copies of itself**, solves each — often by the same splitting, recursively — and **joins** the answers. Its worked example in the supplementary material is **binary search** and its variants: halve the ordered list, decide which half holds the target, halve again. The method pays when the splitting is cheap and the pieces are truly independent.
**Dynamic programming (δυναμικός προγραμματισμός)** attacks problems whose pieces **overlap**: solve each small piece **once**, store its answer in a table, and let bigger pieces read the stored answers instead of solving again — the method that turns hopeless repetition into one pass of remembering. The **greedy method (άπληστη μέθοδος)** builds its answer **one best step at a time**: at each step take the locally best choice and never revisit it — fast and simple, and correct only where the book's care is spent proving the local best truly serves the whole. The workbook reworks all three as graded activities.
