# Counting Elements in an Array

## Do it first

How many of these pass? How many are negative, even, above average? One walk answers all such questions — this lesson is that walk on its own.

## Sub lesson 1 — Test every element, count the passes

The shape: **count = 0;** then for each element, **if (test) count++;**. Nothing is stored and the array is untouched — the product of the walk is the single number. The **test** is the whole art: negative (a[i] < 0), even (a[i] % 2 == 0), in a range (both bounds with &&) — write the test to match the question's exact words, edges included.

[Picture — test every element, count the passes]

## Sub lesson 2 — Edges and two-pass questions

Boundary words decide counts: 'above 10' excludes 10 itself, 'at least 10' includes it — an off-by-one in the **condition**, not the loop. Some questions need **two passes**: the count of elements **above the average** cannot start until the average exists, so the program totals first, then walks again to count. Recognising a two-pass question is the section's real skill.

[Picture — edges and two-pass questions]

## Say it to your companion

Tell your companion, in your own words: Counting elements that satisfy a condition is a walk with a conditional step: a counter starts at zero, every element is tested, and the counter rises by one exactly when the test passes — the condition defines what is being counted, and the answer is finished only when the last element has been tested. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Zero. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Nothing — its product is the single count. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — 'at least 10' includes it. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The average must exist before elements can be compared with it. Do this with a real example of your own and write or say how you know it is right.
