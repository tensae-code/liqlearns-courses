# Video script — AI Search Algorithms and Problem Representation

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Problem representation** is the choosing of how states, actions and goals are written for a computer: what a state records (and what it leaves out), how actions are generated, how the goal is tested. A good representation keeps everything the solution depends on and nothing else — the city's map keeps roads and distances, drops the colour of the houses. Every search algorithm's speed is half-decided here, before any searching begins.
A **search algorithm** is a strategy for exploring the tree: which node to expand next, what to remember, when to stop. Algorithms are judged by four measures the book names: **completeness** (does it find a solution if one exists?), **optimality** (is the found solution the best?), **time** and **space** (what do they cost?). The next lessons meet the families — blind search, which walks without guidance, and heuristic search, which walks toward a guess of the goal.
