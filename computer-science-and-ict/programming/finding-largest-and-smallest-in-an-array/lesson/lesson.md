# Finding the Largest and Smallest in an Array

## Do it first

This is the champion walk of the array theme, given its own lesson by the links-pass reading: keep the best so far, challenge it with every element, crown the survivor.

## Sub lesson 1 — Best-so-far — value

Set **max = a[0]**. For each remaining element, **if (a[i] > max) max = a[i];** — after the walk, max holds the **largest value**, because every element had its chance to beat it and only a bigger one could replace it. Starting from a[0] rather than 0 is what keeps all-negative arrays honest.

[Picture — best-so-far — value]

## Sub lesson 2 — Smallest, and where it sits

**min** mirrors max with **<**. Often the **position** matters as much as the value: keep **imax** beside max, updating both together, and the program can report 'largest is 9, at index 4'. Ties keep the **first** extreme position, because the strict comparison only replaces on a true beating — a detail the exercises test.

[Picture — smallest, and where it sits]

## Say it to your companion

Tell your companion, in your own words: The largest element is found by keeping the best-so-far: start with the first element, then let every element that beats it take its place — the smallest is the same walk with the comparison flipped — and remembering the position as well as the value answers where the extreme sits, not only what it is. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The best-so-far — the largest seen yet. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: When an element beats it — a[i] > max. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The comparison flips to <. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Largest is 9, at index 4. Do this with a real example of your own and write or say how you know it is right.
