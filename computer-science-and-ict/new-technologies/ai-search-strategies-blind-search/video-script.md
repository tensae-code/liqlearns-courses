# Video script — AI Search Strategies — Blind Search

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Blind search** (uninformed search) explores the search tree using only the problem's own information — no hint about how near the goal is. Its strategies differ by the order of visiting: **breadth-first** expands level by level (every node at one depth before any deeper), **depth-first** dives down one branch to its end before backtracking. Both are complete on finite trees in their own ways; both can waste ages in branches a glance at the goal would have pruned.
Breadth-first guarantees the **shallowest** goal but must **remember the whole frontier** — its space cost explodes. Depth-first remembers only its path — cheap in space, but it may dive past the goal's level forever on an infinite branch. Jordan teaches blind search first because it is the baseline every smarter strategy must beat, and because some problems genuinely offer no guidance to be smart with.
