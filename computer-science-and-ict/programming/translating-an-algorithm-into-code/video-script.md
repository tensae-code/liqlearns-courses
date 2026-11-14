# Video script — Translating an Algorithm into Code

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Translation works **structure by structure**, not line by wandering line: a pseudocode **sequence** becomes statements in the same order; a **selection** (IF…THEN…ELSE) becomes Java's if…else with its condition in brackets and its branches in braces; a **repetition** (WHILE or FOR) becomes Java's while or for. Variables in the algorithm are declared in the code before their first use, with the types the algorithm's values need. The flowchart translates the same way — each box and diamond has its code shape, and the arrows become the code's order and nesting.
Translation changes the **language**, never the **logic**: the translated program must do **exactly** what the algorithm does — same steps, same tests, same order. Malaysia's check is a **parallel trace**: run one set of test values through the algorithm by hand and through the program, and the two must agree at every step. A disagreement is a translation fault — a dropped branch, a swapped comparison, a loop test turned upside down — and it is repaired in the code, against the algorithm, which remains the authority. Code written without an algorithm to answer to cannot be checked this way, which is why this course never writes it.
