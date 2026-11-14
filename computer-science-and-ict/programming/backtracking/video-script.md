# Video script — Backtracking

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Backtracking** (duyệt quay lui) improves exhaustive search with one idea: build the answer **step by step**, and test each **partial** build at once. The moment a partial build **cannot** lead to a solution, abandon it — **backtrack** to the last choice point and try the **next choice** — without building the whole doomed family beneath it. Where plain exhaustive search generates every candidate whole, backtracking prunes whole branches with one early failure, which is why hard placement problems (queens, routes, timetables) yield to it.
A backtracking program has a fixed shape: a **recursive** procedure that places the next piece, with the **choices** at each step listed, the problem's **conditions** checked after every placement, and the **return** from the call doing the stepping back. Vietnam's specialist book teaches the design, then drills it twice — a technique practical and a design practical — because the shape transfers: change the pieces, the choices and the conditions, and the same skeleton solves the next problem.
