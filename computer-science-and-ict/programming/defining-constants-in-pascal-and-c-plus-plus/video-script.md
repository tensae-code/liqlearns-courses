# Video script — Defining Constants in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **constant definition** binds a **name to a value that never changes** in the run. Pascal gathers them in a **const section**: `const pi = 3.14159; maxMark = 10;` — the type follows from the value written. C++ writes **`const`** before a typed declaration: `const double pi = 3.14159;` (its older #define also names constants, without a type). Using the name where the value belongs makes the compiler the guard: an assignment to a constant is an **error**, not a temptation.
The reasons echo the type chapter's: **readability** (maxMark speaks; 10 is silent), **one place of truth** (the tax rate changes once, in the const section — not in forty hunted lines), and **safety** (a value the program must not alter is made unalterable). Constants, types and declarations together are the program's front matter: read them and the data's whole constitution is known before the first instruction. Grade 10's data theory ends here — with the program fully described before it acts.
