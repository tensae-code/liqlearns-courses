# Video script — Adversarial Search and the Minimax Algorithm

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Adversarial search** studies games as search trees where two players alternate: **MAX**, who wants the highest final score, and **MIN**, who wants it lowest. A position's value is no longer found but **fought over**: MAX chooses the move leading to the best value she can force; MIN chooses the move leading to the worst for her. The tree's leaves are scored by a **utility function** — win, loss, draw, or a number.
The **minimax algorithm** values a position by supposing both play perfectly: at MAX's nodes take the **maximum** of the children's values, at MIN's nodes the **minimum**, working up from the leaves — and MAX then chooses the move whose minimax value is highest. Jordan's Grade 12 lesson programs it in Python for tic-tac-toe (the next programming lesson): a game small enough to search whole, teaching the shape every game AI — chess engines included — still stands on, pruned and heuristically trimmed.
