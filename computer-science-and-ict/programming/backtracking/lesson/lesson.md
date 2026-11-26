# Backtracking

## Do it first

backtracking — building a solution step by step and, the moment a partial build fails, stepping back and trying the next choice, until a full solution stands or every road is proven closed (Vietnam Grade 11 specialist, CS)

## Sub lesson 1 — Build, test, step back — the technique

**Backtracking** (duyệt quay lui) improves exhaustive search with one idea: build the answer **step by step**, and test each **partial** build at once. The moment a partial build **cannot** lead to a solution, abandon it — **backtrack** to the last choice point and try the **next choice** — without building the whole doomed family beneath it. Where plain exhaustive search generates every candidate whole, backtracking prunes whole branches with one early failure, which is why hard placement problems (queens, routes, timetables) yield to it.

In your mind's eye: build, test, step back — the technique.

[Picture 46742 — build, test, step back — the technique]

## Sub lesson 2 — Designing with backtracking — choices, conditions, recursion

A backtracking program has a fixed shape: a **recursive** procedure that places the next piece, with the **choices** at each step listed, the problem's **conditions** checked after every placement, and the **return** from the call doing the stepping back. Vietnam's specialist book teaches the design, then drills it twice — a technique practical and a design practical — because the shape transfers: change the pieces, the choices and the conditions, and the same skeleton solves the next problem.

In your mind's eye: designing with backtracking — choices, conditions, recursion.

[Picture 46743 — designing with backtracking — choices, conditions, recursion]

## Say it to your companion

Tell your companion, in your own words: **Backtracking** (duyệt quay lui) improves exhaustive search with one idea: build the answer **step by step**, and test each **partial** build at once. The moment a partial build **cannot** lead to a solution, abandon it — **backtrack** to the last choice point and try the **next choice** — without building the whole doomed family beneath it. Where plain exhaustive search generates every candidate whole, backtracking prunes whole branches with one early failure, which is why hard placement problems (queens, routes, timetables) yield to it. A backtracking program has a fixed shape: a **recursive** procedure that places the next piece, with the **choices** at each step listed, the problem's **conditions** checked after every placement, and the **return** from the call doing the stepping back. Vietnam's specialist book teaches the design, then drills it twice — a technique practical and a design practical — because the shape transfers: change the pieces, the choices and the conditions, and the same skeleton solves the next problem. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Build step by step, test each partial build, and abandon a failing one at once Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Backtrack — return to the last choice point and try the next choice Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It prunes whole branches with one early failure instead of generating every candidate whole Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Hard placement problems — queens, routes, timetables Do this with a real example of your own and write or say how you know it is right.
