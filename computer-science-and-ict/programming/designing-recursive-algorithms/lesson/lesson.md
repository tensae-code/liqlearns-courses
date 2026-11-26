# Designing Recursive Algorithms

## Do it first

designing recursive algorithms — finding the base case and the recurrence: how a problem is restated as a smaller copy of itself (Vietnam Grade 11 specialist, CS)

## Sub lesson 1 — The two parts every recursive design must name

A recursive algorithm is **designed**, not stumbled into, and the design names two parts. The **base case**: the smallest version of the problem, answered **directly**, with no further call — the floor the descent stands on. The **recurrence**: how the problem is restated as **one (or more) smaller copies of itself**, plus the small work of joining their answers. Vietnam's specialist book teaches the design before its applications: name these two, and the recursive function almost writes itself; miss the base case, and the calls never stop.

In your mind's eye: the two parts every recursive design must name.

[Picture 47021 — the two parts every recursive design must name]

## Sub lesson 2 — Shrinking honestly — the step must approach the floor

The recurrence carries one duty: every smaller copy must be **closer to the base case** — n−1 toward 0, a shorter list, a smaller tower. The design practicals drill the pattern on the book's examples (sequences like Fibonacci, where **two** smaller copies join; sums and factorials, where one does). The designer's checklist closes the lesson: state the problem with its size named, write the base case first, write the recurrence, then **argue the shrinking** — if you cannot say why the copies approach the floor, the design is not finished.

In your mind's eye: shrinking honestly — the step must approach the floor.

[Picture 47022 — shrinking honestly — the step must approach the floor]

## Say it to your companion

Tell your companion, in your own words: A recursive algorithm is **designed**, not stumbled into, and the design names two parts. The **base case**: the smallest version of the problem, answered **directly**, with no further call — the floor the descent stands on. The **recurrence**: how the problem is restated as **one (or more) smaller copies of itself**, plus the small work of joining their answers. Vietnam's specialist book teaches the design before its applications: name these two, and the recursive function almost writes itself; miss the base case, and the calls never stop. The recurrence carries one duty: every smaller copy must be **closer to the base case** — n−1 toward 0, a shorter list, a smaller tower. The design practicals drill the pattern on the book's examples (sequences like Fibonacci, where **two** smaller copies join; sums and factorials, where one does). The designer's checklist closes the lesson: state the problem with its size named, write the base case first, write the recurrence, then **argue the shrinking** — if you cannot say why the copies approach the floor, the design is not finished. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The base case and the recurrence Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The smallest version of the problem, answered directly with no further call Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The restating of the problem as smaller copies of itself, plus the work of joining their answers Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The calls never stop — the descent has no floor Do this with a real example of your own and write or say how you know it is right.
