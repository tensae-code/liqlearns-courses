# Video script — Declaring, Initialising and Assigning Variables

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Declaration** brings the variable into being: a **type** and a **name** — int score; — after which the name exists but holds nothing usable. **Initialisation** gives the **first value**, often in the same breath: int score = 0;. Java refuses to use a variable that has not been given a value — reading an uninitialised variable is an error the compiler catches. A **constant** is declared with **final** and initialised once: final int PASS_MARK = 50; — its initialisation is also its only assignment, by law.
**Assignment** replaces a variable's value while the program runs: score = score + 5; — read it as 'score becomes score plus 5': the right side is worked out with the **old** value, then the result replaces it. Assignments may happen any number of times; a declaration happens **once** — declaring the same name twice is an error, assigning twice is ordinary work. Malaysia's three acts, kept apart, explain most beginner compiler messages: 'cannot find symbol' is a missing declaration, 'might not have been initialised' is a missing first value, and 'cannot assign to final' is an assignment aimed at a constant.
