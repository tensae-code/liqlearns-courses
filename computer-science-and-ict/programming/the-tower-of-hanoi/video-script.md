# Video script — The Tower of Hanoi

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **Tower of Hanoi** (Tháp Hà Nội) is a puzzle of **three pegs** and a tower of **disks of decreasing size** stacked on the first peg. The task: move the **whole tower** to another peg, moving **one disk at a time**, with one rule — **never place a larger disk on a smaller one**. Vietnam's specialist book gives the puzzle its own lesson inside the recursion strand, because its solution is the cleanest first sight of a problem that contains itself.
To move a tower of **n** disks: move the tower of **n−1** disks out of the way, move the **biggest disk** once, then move the n−1 tower **on top of it**. That is the whole solution — the base case is n = 1 (move the single disk). The cost grows by the recurrence T(n) = 2T(n−1) + 1, giving **2ⁿ − 1 moves**: 3 disks take 7, and the legendary 64 would take longer than the age of the universe at one move a second — recursion's elegance and its price in one problem.
