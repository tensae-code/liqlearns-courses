# Video script — Bubble Sort

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Bubble sort** works in **passes** through the list. On each pass, every **neighbouring pair** is compared from the start; if the pair is **out of order** (the left bigger than the right, for ascending order), the two are **swapped**; if in order, they are left. One pass does not finish the sort — it guarantees one thing: the **biggest** of the unsorted values has been swapped step by step to the **end**, like a bubble rising — the movement that names the method.
The passes repeat over the **still-unsorted front** of the list — the sorted tail at the end is left alone. Each pass parks one more biggest value, so the passes get shorter. The sort is finished when a **whole pass makes no swaps** — every neighbour already in order means the list is sorted. Malaysia's pseudocode nests the shape: an outer loop for passes, an inner loop for the neighbour comparisons, and a swapped flag to catch the clean pass. Bubble sort is simple and slow — its teaching worth is that every swap can be watched and counted.
