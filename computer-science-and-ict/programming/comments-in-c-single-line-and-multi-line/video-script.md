# Video script — Comments in C — Single-Line and Multi-Line

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **single-line comment** begins with **//** and runs to the line's end: `// read the marks` — the margin note, for one statement's reason. A **multi-line comment** opens with **/\*** and closes with **\*/** and may span many lines — the paragraph at a function's head, the licence, the explanation of a hard algorithm. Both are removed before compilation as surely as Python's # comments (the comments lessons of other languages agree on the purpose while differing in dress): the machine never sees them.
A good comment says **why**, or what the code below must never break — never merely repeats the code in words ('add 1 to i' above `i = i + 1` is noise wearing a comment's coat). Comments also carry the working programmer's second tool: **commenting out** — wrapping a troublesome block in /* … */ to silence it while debugging, instead of deleting what may be innocent. And a rotten comment is worse than none: a note that lies about the code below it will be believed once, at the worst moment — so comments are maintained like code, changed when the code changes, or struck out with it.
