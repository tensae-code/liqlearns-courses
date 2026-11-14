# Video script — The For Instruction in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **for** instruction reads `for i := 1 to n do <instruction>`: the **control variable** i starts at the first value, the body runs, i climbs by **one**, and the loop ends when i passes the final value. With **downto**, i descends instead: `for i := n downto 1 do`. The control variable must be of **ordinal type**, declared like any variable, and start and final are evaluated **once**, before the first pass. For a count known in advance, for is the exact instrument — no manual counter-keeping anywhere.
For protects its steering: the body must **not change the control variable** — assigning to i inside its own loop is forbidden, because the loop's counting would break. After the loop ends, the control variable's value is **undefined** (except when the loop was left by goto) — using it afterwards is an error of reasoning even when a machine tolerates it. And the body's one instruction becomes a **compound** begin…end when the repeated work is several instructions: for's single line, steering a block.
