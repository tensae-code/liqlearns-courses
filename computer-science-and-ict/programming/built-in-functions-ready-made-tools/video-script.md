# Video script — Built-In Functions — Ready-Made Tools

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **built-in function** is a function the language itself provides: it exists before your program starts, is called by name with **arguments**, and hands back a **result**. Every language's toolbox differs, but the families repeat: mathematics (`abs`, `round`, `sqrt`), text (`len`, `upper`), conversion (`int`, `str`), and input/output (`print`, `input`). Armenia meets predefined functions in the Grade 7 guide's programme (§21) and opens Grade 12 with them: built-in functions in JavaScript (Lesson 1).
Built-ins compose: a result can feed the next call — `int(round(x))` — **nesting** calls inside-out. They are also **trusted but verified**: a built-in does exactly its documented job, so the programmer's duty is to call it with the right kind of argument and to know its edges (what `round` does at .5, what `int` does with text). The professional habit: reach for a built-in before writing your own — a tested tool beats a fresh invention — and read its documentation line before first use, not after the surprise.
