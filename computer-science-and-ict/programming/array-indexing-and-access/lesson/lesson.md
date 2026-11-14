# Array Indexing and Access

## Do it first

The first element is number zero, not one — the single most important counting habit in programming. This lesson makes that habit exact, and shows the cliff edge at the array's end.

## Sub lesson 1 — Counting from zero

**a[0]** is the **first** element, a[1] the second, and **a[n−1]** the **last** in an array of size n. The **index** (subscript) is written in square brackets and can be any integer expression — a literal, a variable, even a calculation — which is what makes loops over arrays possible: for (i = 0; i < n; i++) visits each element exactly once.

[Picture — counting from zero]

## Sub lesson 2 — The edge — out of bounds

**a[n]** does not exist: it names memory **past the array**, and C++ performs **no bounds checking** — reading it gives garbage, writing it damages whatever lives there, and the program may crash later somewhere unrelated. Keeping the loop condition **i < n** (never i <= n) is the standing guard. Off-by-one at the array's edge is the classic array bug.

[Picture — the edge — out of bounds]

## Say it to your companion

Tell your companion, in your own words: Array elements are numbered from zero — the index in square brackets picks the element, so an array of size n has indexes 0 to n−1 — and asking for an index outside that range is out-of-bounds access, which C++ does not stop and which quietly corrupts the program. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: 0. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Any integer expression — literal, variable or calculation. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — it is past the last element. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Damage whatever lives in that memory. Do this with a real example of your own and write or say how you know it is right.
