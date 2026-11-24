# Algorithm Design Methods — Divide-and-Conquer, Dynamic Programming, Greedy

## Do it first

Some problems are too big to attack whole. Greece's exam course teaches three standing ways to attack them anyway — split them, remember the pieces' answers, or take the best step now. This lesson is the three methods, side by side.

## Sub lesson 1 — Divide-and-conquer — split, solve, join

**Divide-and-conquer (διαίρει και βασίλευε)** splits a problem into **smaller copies of itself**, solves each — often by the same splitting, recursively — and **joins** the answers. Its worked example in the supplementary material is **binary search** and its variants: halve the ordered list, decide which half holds the target, halve again. The method pays when the splitting is cheap and the pieces are truly independent.

In your mind's eye: divide-and-conquer — split, solve, join.

## Sub lesson 2 — Dynamic programming and the greedy method — remembering, and taking the best now

**Dynamic programming (δυναμικός προγραμματισμός)** attacks problems whose pieces **overlap**: solve each small piece **once**, store its answer in a table, and let bigger pieces read the stored answers instead of solving again — the method that turns hopeless repetition into one pass of remembering. The **greedy method (άπληστη μέθοδος)** builds its answer **one best step at a time**: at each step take the locally best choice and never revisit it — fast and simple, and correct only where the book's care is spent proving the local best truly serves the whole. The workbook reworks all three as graded activities.

In your mind's eye: dynamic programming and the greedy method — remembering, and taking the best now.

## Say it to your companion

Tell your companion, in your own words: **Divide-and-conquer (διαίρει και βασίλευε)** splits a problem into **smaller copies of itself**, solves each — often by the same splitting, recursively — and **joins** the answers. Its worked example in the supplementary material is **binary search** and its variants: halve the ordered list, decide which half holds the target, halve again. The method pays when the splitting is cheap and the pieces are truly independent. **Dynamic programming (δυναμικός προγραμματισμός)** attacks problems whose pieces **overlap**: solve each small piece **once**, store its answer in a table, and let bigger pieces read the stored answers instead of solving again — the method that turns hopeless repetition into one pass of remembering. The **greedy method (άπληστη μέθοδος)** builds its answer **one best step at a time**: at each step take the locally best choice and never revisit it — fast and simple, and correct only where the book's care is spent proving the local best truly serves the whole. The workbook reworks all three as graded activities. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Split into smaller copies, solve each, join the answers. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Binary search and its variants. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Halve the ordered list and decide which half holds the target. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: When splitting is cheap and the pieces are truly independent. Do this with a real example of your own and write or say how you know it is right.
