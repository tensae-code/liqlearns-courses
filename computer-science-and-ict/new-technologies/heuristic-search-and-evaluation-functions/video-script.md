# Video script — Heuristic Search and Evaluation Functions

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **heuristic function h(n)** estimates the cost from a node n to the goal: straight-line distance for a route (whatever the roads do), tiles out of place for a puzzle. A good heuristic is **informed** (it uses the problem's own knowledge), **cheap to compute**, and ideally **admissible** — never overestimating the true cost, so the search it guides stays optimal. Heuristic search orders its frontier by promise, expanding the most hopeful node first.
An **evaluation function f(n)** scores a node for expanding: it may join the cost already spent, g(n), with the heuristic estimate, h(n) — f(n) = g(n) + h(n), the shape of the famous A* search — balancing 'how far I've come' against 'how far I seem to go'. Jordan's lesson closes with the craft's warning: a heuristic is a guess with consequences — a lying heuristic doesn't just slow the search, it can walk it confidently away from the goal.
