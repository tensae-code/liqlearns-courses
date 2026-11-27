# The Tower of Hanoi

## Do it first

the Tower of Hanoi — moving a tower of disks peg by peg, never a larger disk on a smaller, and its recursive solution: move the smaller tower, move the biggest disk, move the smaller tower again (Vietnam Grade 11 specialist, CS)

## Sub lesson 1 — The problem — three pegs and one rule

The **Tower of Hanoi** (Tháp Hà Nội) is a puzzle of **three pegs** and a tower of **disks of decreasing size** stacked on the first peg. The task: move the **whole tower** to another peg, moving **one disk at a time**, with one rule — **never place a larger disk on a smaller one**. Vietnam's specialist book gives the puzzle its own lesson inside the recursion strand, because its solution is the cleanest first sight of a problem that contains itself.

In your mind's eye: the problem — three pegs and one rule.

[Picture 47893 — the problem — three pegs and one rule]

## Sub lesson 2 — The recursive solution — the tower inside the tower

To move a tower of **n** disks: move the tower of **n−1** disks out of the way, move the **biggest disk** once, then move the n−1 tower **on top of it**. That is the whole solution — the base case is n = 1 (move the single disk). The cost grows by the recurrence T(n) = 2T(n−1) + 1, giving **2ⁿ − 1 moves**: 3 disks take 7, and the legendary 64 would take longer than the age of the universe at one move a second — recursion's elegance and its price in one problem.

In your mind's eye: the recursive solution — the tower inside the tower.

[Picture 47894 — the recursive solution — the tower inside the tower]

## Say it to your companion

Tell your companion, in your own words: The **Tower of Hanoi** (Tháp Hà Nội) is a puzzle of **three pegs** and a tower of **disks of decreasing size** stacked on the first peg. The task: move the **whole tower** to another peg, moving **one disk at a time**, with one rule — **never place a larger disk on a smaller one**. Vietnam's specialist book gives the puzzle its own lesson inside the recursion strand, because its solution is the cleanest first sight of a problem that contains itself. To move a tower of **n** disks: move the tower of **n−1** disks out of the way, move the **biggest disk** once, then move the n−1 tower **on top of it**. That is the whole solution — the base case is n = 1 (move the single disk). The cost grows by the recurrence T(n) = 2T(n−1) + 1, giving **2ⁿ − 1 moves**: 3 disks take 7, and the legendary 64 would take longer than the age of the universe at one move a second — recursion's elegance and its price in one problem. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Three pegs, and a tower of disks of decreasing size Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Move the whole tower to another peg Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: One at a time Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Never place a larger disk on a smaller one Do this with a real example of your own and write or say how you know it is right.
