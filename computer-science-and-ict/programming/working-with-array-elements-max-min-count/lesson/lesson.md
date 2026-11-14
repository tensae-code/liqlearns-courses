# Working with Array Elements — Operations, Largest, Smallest, Counting

## Do it first

Almost every array job is the same walk wearing different clothes. This lesson teaches the walk once, in its three classic outfits: total and operations, largest-and-smallest, and counting.

## Sub lesson 1 — Operations over the whole array

The pattern: an **accumulator** starts at its neutral value (0 for a sum), the loop visits **every** element, and each visit **folds** the element in — total += a[i]. The same walk with a different fold gives products, sums of squares, or a transformed second array (each element doubled, say). The array itself is only read, never changed, in this family of tasks.

[Picture — operations over the whole array]

## Sub lesson 2 — Largest, smallest and counting

For **largest**: set max = **a[0]** (never 0 — an all-negative array would break that), then each element that **beats** max replaces it. **Smallest** mirrors it. For **counting**: a counter rises by one **only when the element passes a test** (negative? even? above the average?) — same walk, conditional fold. The links-pass reading splits this material further: inserting elements, finding largest/smallest and counting each get their own stocked lessons beside this one.

[Picture — largest, smallest and counting]

## Say it to your companion

Tell your companion, in your own words: The basic array operations all share one walk: keep a running answer outside the loop (a total, the largest so far, a count), visit every element once, and update the answer by comparing or adding — largest starts from the first element, counting tests each element against a condition, and the walk itself never changes the array. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A running answer — the accumulator. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: total += a[i]. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The first element, a[0]. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The counter rises only when the element passes a test. Do this with a real example of your own and write or say how you know it is right.
