# Bubble Sort

## Do it first

Watch a list being sorted by neighbours alone: compare two side by side, swap them if they are in the wrong order, step on. Malaysia's first sort is bubble sort. In this lesson you bubble a list into order, pass by pass.

## Sub lesson 1 — Neighbours compared, neighbours swapped

**Bubble sort** works in **passes** through the list. On each pass, every **neighbouring pair** is compared from the start; if the pair is **out of order** (the left bigger than the right, for ascending order), the two are **swapped**; if in order, they are left. One pass does not finish the sort — it guarantees one thing: the **biggest** of the unsorted values has been swapped step by step to the **end**, like a bubble rising — the movement that names the method.

In your mind's eye: neighbours compared, neighbours swapped.

## Sub lesson 2 — Pass after pass, until a clean pass

The passes repeat over the **still-unsorted front** of the list — the sorted tail at the end is left alone. Each pass parks one more biggest value, so the passes get shorter. The sort is finished when a **whole pass makes no swaps** — every neighbour already in order means the list is sorted. Malaysia's pseudocode nests the shape: an outer loop for passes, an inner loop for the neighbour comparisons, and a swapped flag to catch the clean pass. Bubble sort is simple and slow — its teaching worth is that every swap can be watched and counted.

In your mind's eye: pass after pass, until a clean pass.

## Say it to your companion

Tell your companion, in your own words: **Bubble sort** works in **passes** through the list. On each pass, every **neighbouring pair** is compared from the start; if the pair is **out of order** (the left bigger than the right, for ascending order), the two are **swapped**; if in order, they are left. One pass does not finish the sort — it guarantees one thing: the **biggest** of the unsorted values has been swapped step by step to the **end**, like a bubble rising — the movement that names the method. The passes repeat over the **still-unsorted front** of the list — the sorted tail at the end is left alone. Each pass parks one more biggest value, so the passes get shorter. The sort is finished when a **whole pass makes no swaps** — every neighbour already in order means the list is sorted. Malaysia's pseudocode nests the shape: an outer loop for passes, an inner loop for the neighbour comparisons, and a swapped flag to catch the clean pass. Bubble sort is simple and slow — its teaching worth is that every swap can be watched and counted. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Neighbouring pairs, from the start of the list. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: When they are out of order — the left bigger than the right, for ascending order. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The biggest unsorted value has reached the end. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Each pass parks one more biggest value at the end. Do this with a real example of your own and write or say how you know it is right.
