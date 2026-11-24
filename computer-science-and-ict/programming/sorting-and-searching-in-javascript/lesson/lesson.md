# Sorting and Searching in JavaScript

## Do it first

Malaysia's final-year web chapter carries the school algorithms into JavaScript: the same bubble, selection and binary ideas, now as code that runs in a page. In this lesson you write the three in JavaScript — and see that the algorithm outlives the language.

## Sub lesson 1 — Sorting in JavaScript — bubble and selection

A JavaScript **sort** works on an **array** with nested loops. **Bubble sort** in code is the paper method written down: an outer loop for passes, an inner loop comparing array[j] with array[j+1], and a swap through a temporary variable (let t = a[j]; a[j] = a[j+1]; a[j+1] = t;). **Selection sort** searches each pass for the **smallest remaining** value and swaps it into place — the search-inside-sort weaving, in code. JavaScript also has a built-in sort method, but Malaysia codes the methods by hand first: the built-in is trusted only after its hand-written ancestors are understood.

In your mind's eye: sorting in JavaScript — bubble and selection.

## Sub lesson 2 — Searching in JavaScript — binary search coded

**Binary search** in JavaScript tracks low, high and mid over the array's indexes, looping while low <= high, comparing array[mid] with the target and halving the field exactly as the pseudocode did. The code returns the **index** where the target was found, or −1 for not found — the convention JavaScript programs use. The lesson's point closes the strand: pseudocode, flowchart and JavaScript are three writings of one algorithm; Malaysia moves between them to prove the algorithm is the thinking, and the language only its clothing.

In your mind's eye: searching in JavaScript — binary search coded.

## Say it to your companion

Tell your companion, in your own words: A JavaScript **sort** works on an **array** with nested loops. **Bubble sort** in code is the paper method written down: an outer loop for passes, an inner loop comparing array[j] with array[j+1], and a swap through a temporary variable (let t = a[j]; a[j] = a[j+1]; a[j+1] = t;). **Selection sort** searches each pass for the **smallest remaining** value and swaps it into place — the search-inside-sort weaving, in code. JavaScript also has a built-in sort method, but Malaysia codes the methods by hand first: the built-in is trusted only after its hand-written ancestors are understood. **Binary search** in JavaScript tracks low, high and mid over the array's indexes, looping while low <= high, comparing array[mid] with the target and halving the field exactly as the pseudocode did. The code returns the **index** where the target was found, or −1 for not found — the convention JavaScript programs use. The lesson's point closes the strand: pseudocode, flowchart and JavaScript are three writings of one algorithm; Malaysia moves between them to prove the algorithm is the thinking, and the language only its clothing. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: An array, with nested loops. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Through a temporary variable — let t = a[j]; a[j] = a[j+1]; a[j+1] = t;. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The smallest remaining value, to swap into place. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: low, high and mid over the array's indexes. Do this with a real example of your own and write or say how you know it is right.
