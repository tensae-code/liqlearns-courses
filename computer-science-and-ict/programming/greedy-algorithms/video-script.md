# Video script — Greedy Algorithms

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **greedy algorithm** (algoritma greedy) builds its answer in steps and, at each step, takes the **locally best** choice — the largest coin, the earliest-finishing activity, the nearest city — never looking back and never reconsidering. Indonesia's Grade 11 chapter teaches it between recursion and dynamic programming as the fastest of the three tempers: where it works, it is beautifully simple — no table, no backtracking, just a rule for 'best now' applied until the answer stands. Coin change with the right coin system is its school example: always take the largest coin that fits, and the fewest coins result.
Greedy's speed is bought with a risk: the best now can poison the whole — a coin system of 1, 3 and 4 making 6 greedily takes 4+1+1 (three coins) where 3+3 (two) was waiting. So the chapter's real skill is the **greedy test**: before trusting hunger, ask whether a locally best choice can ever block a globally best answer — some problems are built so it cannot (their choices never close a needed door), and for those, greedy is not a gamble but a proof. Name the temper, test the problem, then let it run.
