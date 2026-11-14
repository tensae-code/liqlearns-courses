# Video script — Designing Recursive Algorithms

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A recursive algorithm is **designed**, not stumbled into, and the design names two parts. The **base case**: the smallest version of the problem, answered **directly**, with no further call — the floor the descent stands on. The **recurrence**: how the problem is restated as **one (or more) smaller copies of itself**, plus the small work of joining their answers. Vietnam's specialist book teaches the design before its applications: name these two, and the recursive function almost writes itself; miss the base case, and the calls never stop.
The recurrence carries one duty: every smaller copy must be **closer to the base case** — n−1 toward 0, a shorter list, a smaller tower. The design practicals drill the pattern on the book's examples (sequences like Fibonacci, where **two** smaller copies join; sums and factorials, where one does). The designer's checklist closes the lesson: state the problem with its size named, write the base case first, write the recurrence, then **argue the shrinking** — if you cannot say why the copies approach the floor, the design is not finished.
