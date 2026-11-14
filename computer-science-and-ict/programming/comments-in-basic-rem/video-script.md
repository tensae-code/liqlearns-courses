# Video script — Comments in BASIC — REM

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A BASIC program can carry notes to its human readers: any line (or part of a line) beginning with **REM** — short for **remark** — is a **comment**. The computer **ignores** REM lines completely when the program runs: they change nothing, print nothing, compute nothing. They exist for the people — the programmer returning to the program in a month, or another programmer reading it for the first time. Sudan's book gives comments their own short section because a program nobody can read is a program nobody can fix.
A good REM says **why**, not what: the line `30 LET T = P * R / 100` is clearer with `25 REM T IS THE TAX ON PAY P AT RATE R` than with a remark repeating the arithmetic. Comments belong at the **head of the program** (its name, its job, its writer) and **before any part whose purpose is not obvious**. The rule of proportion is the lesson's rule: comment the thinking, not every line — a program drowned in remarks hides its own code.
