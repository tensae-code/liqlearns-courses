# Video script — Search Trees and Problem Solving in AI

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

AI search begins by stating a problem as **states** (the situations that can arise), an **initial state** (where we start), **actions** (the moves that change a state), and a **goal test** (how we know a state is the answer). A route problem: states are places, actions are roads. A puzzle: states are arrangements, actions are legal slides. The statement is the solving's first half — a badly stated problem has no search that can save it.
Applying actions to states grows a **search tree**: the initial state at the root, each branch an action, each node a reached state, the goal sitting somewhere in the branches. **Solving is searching** — walking the tree by a strategy until a goal node is found, then reading the path back down as the solution's steps. The tree is usually far too big to draw fully; the art of the next lessons is searching it without visiting every branch.
