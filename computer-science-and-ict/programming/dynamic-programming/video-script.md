# Video script — Dynamic Programming

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Some problems split into pieces that **overlap**: the pieces share smaller pieces, so a plain recursive attack solves the same small problem again and again — the work explodes while the answers repeat. **Dynamic programming** (pemrograman dinamis) is the discipline that refuses the waste: solve each distinct small piece **once**, **store** its answer in a table, and let every bigger piece **read** the stored answer instead of solving again. Indonesia's Grade 11 algorithm chapter teaches it as the third of its advanced strategies, after recursion and greedy — the strategy for problems whose shape is a family of overlapping subproblems.
The method has a working order: name the **subproblems** (what exactly a small piece asks), solve them **smallest first** so every answer a bigger piece needs is already in the table, and state the **joining rule** — how a piece's answer is built from the smaller answers beneath it. Its price is memory (the table) and its profit is time (each piece solved once), and its tell is the question a programmer learns to ask of any slow recursion: 'am I solving this piece before?' — where the answer is yes, a table is waiting to be built.
