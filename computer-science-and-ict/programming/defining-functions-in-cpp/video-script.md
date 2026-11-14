# Video script — Defining Functions in C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **function definition** has four parts: the **return type** (what kind of value it gives back, or **void** for none), the **name**, the **parameters** in round brackets (the inputs it accepts, each with its type), and the **body** in braces — the statements that do the work, ending with **return** when a value goes back. Until it is **called**, a defined function does nothing at all.
A **call** writes the function's name with **arguments** — real values for the parameters — and the program jumps into the body, runs it, and **returns to the exact place of the call**, carrying the returned value if there is one. One definition then serves every call site: fix the body once and every call is fixed. main() itself is a function — the one the system calls first.
