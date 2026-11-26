# Binary Search

## Do it first

Search a sorted list of a thousand names by checking the middle one first, and the hunt collapses: each check throws half the list away. Malaysia's second search is binary search. In this lesson you work it — and respect its one demand: the list must be in order.

## Sub lesson 1 — Halving the field

**Binary search** works only on an **ordered list**. Check the **middle** item: if it is the target, the hunt ends. If the target is **smaller**, it can only live in the **left half** — the right half is discarded whole. If **larger**, the left half is discarded. The surviving half is searched the same way — new middle, new halving — until the target is found or the field shrinks to **nothing**, which answers 'not found'. Each check halves the field: 1,000 items need at most about 10 checks, against linear search's 1,000.

In your mind's eye: halving the field.

[Picture 46766 — halving the field]

## Sub lesson 2 — Binary search in pseudocode and flowchart

The pseudocode tracks **low** and **high** — the ends of the surviving field — and repeats while low ≤ high: middle = (low + high) ÷ 2 (whole number); if the middle item is the target, report it and stop; if the target is smaller, set high = middle − 1; else set low = middle + 1. The flowchart's shape is a loop with a **three-way decision** at its heart. Malaysia's warning is drawn with it: run binary search on an **unordered** list and it will throw away the half that holds the target — the method's speed is bought entirely by the order it demands.

In your mind's eye: binary search in pseudocode and flowchart.

[Picture 46767 — binary search in pseudocode and flowchart]

## Say it to your companion

Tell your companion, in your own words: **Binary search** works only on an **ordered list**. Check the **middle** item: if it is the target, the hunt ends. If the target is **smaller**, it can only live in the **left half** — the right half is discarded whole. If **larger**, the left half is discarded. The surviving half is searched the same way — new middle, new halving — until the target is found or the field shrinks to **nothing**, which answers 'not found'. Each check halves the field: 1,000 items need at most about 10 checks, against linear search's 1,000. The pseudocode tracks **low** and **high** — the ends of the surviving field — and repeats while low ≤ high: middle = (low + high) ÷ 2 (whole number); if the middle item is the target, report it and stop; if the target is smaller, set high = middle − 1; else set low = middle + 1. The flowchart's shape is a loop with a **three-way decision** at its heart. Malaysia's warning is drawn with it: run binary search on an **unordered** list and it will throw away the half that holds the target — the method's speed is bought entirely by the order it demands. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: It must already be in order. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The middle item. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The right half — whole. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: low and high — the ends of the surviving field. Do this with a real example of your own and write or say how you know it is right.
