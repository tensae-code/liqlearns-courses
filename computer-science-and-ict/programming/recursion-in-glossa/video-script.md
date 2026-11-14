# Video script — Recursion in ΓΛΩΣΣΑ

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In ΓΛΩΣΣΑ a **procedure or function may call itself** — that is recursion in the language. Each call is a **fresh run** of the subprogram with its own parameters and local names, stacked on the unfinished calls beneath it. The book's condition is absolute: somewhere in the subprogram must stand a **stopping case** — a call that answers without calling again — and every self-call must move **closer** to it, or the calls never end and the program fails.
The book traces recursion the exam way: **on paper, call by call**. The factorial function calls itself with n−1 until the stopping case n=1 (or 0) answers 1; then the stacked calls **unwind**, each multiplying its own n by the answer handed back, until the first call gives the final product. Writing that trace — calls going down, answers coming up — is the skill Ch.10 examines, and the same trace serves the chapter's other recursions (greatest common divisor, Fibonacci) taught in the algorithms chapters.
