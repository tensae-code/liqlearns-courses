# Merge Sort

## Do it first

merge sort — sorting by divide and conquer: split the list in half until the pieces are single, then merge neighbouring pieces in order (Vietnam Grade 11 specialist, CS)

## Sub lesson 1 — Split to singles — the divide

**Merge sort** (sắp xếp trộn) sorts the divide-and-conquer way. **Split** the list into two halves, split each half again, and keep splitting until every piece holds **one item** — a one-item list is already sorted. The splitting does no comparing at all; it is pure division, halving the problem until the pieces are trivial. Vietnam's specialist book teaches merge sort as the technique's showpiece: the problem is conquered not by working harder on the whole, but by reaching pieces too small to be unsorted.

In your mind's eye: split to singles — the divide.

[Picture 47279 — split to singles — the divide]

## Sub lesson 2 — Merge in order — the conquer

The way back up is the **merge**: take two neighbouring sorted pieces and build one sorted list from them by repeatedly **taking the smaller of their two front items**. When one piece empties, the other's rest follows in order. Merging two pieces of total length n takes n takings — and because the halves were each sorted the same way, the joined list is sorted whole. The book's cost remark: merge sort does about **n log n** work — splitting gives log n levels, each level merges everything once.

In your mind's eye: merge in order — the conquer.

[Picture 47280 — merge in order — the conquer]

## Say it to your companion

Tell your companion, in your own words: **Merge sort** (sắp xếp trộn) sorts the divide-and-conquer way. **Split** the list into two halves, split each half again, and keep splitting until every piece holds **one item** — a one-item list is already sorted. The splitting does no comparing at all; it is pure division, halving the problem until the pieces are trivial. Vietnam's specialist book teaches merge sort as the technique's showpiece: the problem is conquered not by working harder on the whole, but by reaching pieces too small to be unsorted. The way back up is the **merge**: take two neighbouring sorted pieces and build one sorted list from them by repeatedly **taking the smaller of their two front items**. When one piece empties, the other's rest follows in order. Merging two pieces of total length n takes n takings — and because the halves were each sorted the same way, the joined list is sorted whole. The book's cost remark: merge sort does about **n log n** work — splitting gives log n levels, each level merges everything once. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Split the list down to single items, then merge the pieces back in order Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: When every piece holds one item Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A single item has nothing out of order Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: None — splitting is pure division Do this with a real example of your own and write or say how you know it is right.
