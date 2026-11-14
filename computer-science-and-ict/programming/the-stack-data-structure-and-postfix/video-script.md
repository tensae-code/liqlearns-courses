# Video script — The Stack Data Structure — and Postfix

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **stack** (tumpukan) is a data structure that keeps its values in a pile with one open end — the **top**. Two operations work it: **push** puts a value on top, **pop** takes the top value off. Its law is **LIFO** — the last value in is the first value out — like a pile of plates, or the undo history of an editor. Indonesia meets the stack twice: in Grade 8's computational thinking, and in Grade 10, where it is chosen (against the queue) as the structure a problem needs. A stack is not a list with manners; its restriction — only the top may be touched — is exactly its power.
Grade 8's jewel is **postfix** evaluation (the book's 'cara Koko' — Koko's way): in postfix notation the operator follows its values — `3 4 +` instead of `3 + 4` — and a stack evaluates it mechanically: read left to right, **push numbers**, and when an **operator** arrives, **pop two values, apply it, push the result**. At the end, the stack holds the single answer. No brackets, no precedence rules — the stack's order does the whole grammar. The same chapter's Grade 10 twin completes the picture: the **queue** beside the stack, first-in-first-out, and simulations that teach choosing between them by the problem's shape.
