# The For Instruction in Pascal

## Do it first

The counted loop met in algorithm form returns wearing Pascal syntax. Grade 8 and Grade 10 teach for as the loop of known counts: the whole steering — start, limit, step — declared in its single heading line.

## Sub lesson 1 — for — the counted loop in one line

The **for** instruction reads `for i := 1 to n do <instruction>`: the **control variable** i starts at the first value, the body runs, i climbs by **one**, and the loop ends when i passes the final value. With **downto**, i descends instead: `for i := n downto 1 do`. The control variable must be of **ordinal type**, declared like any variable, and start and final are evaluated **once**, before the first pass. For a count known in advance, for is the exact instrument — no manual counter-keeping anywhere.

[Picture — for — the counted loop in one line]

## Sub lesson 2 — The rules of the control variable

For protects its steering: the body must **not change the control variable** — assigning to i inside its own loop is forbidden, because the loop's counting would break. After the loop ends, the control variable's value is **undefined** (except when the loop was left by goto) — using it afterwards is an error of reasoning even when a machine tolerates it. And the body's one instruction becomes a **compound** begin…end when the repeated work is several instructions: for's single line, steering a block.

[Picture — The rules of the control variable]

## Say it to your companion

Tell your companion, in your own words: The **for** instruction reads `for i := 1 to n do <instruction>`: the **control variable** i starts at the first value, the body runs, i climbs by **one**, and the loop ends when i passes the final value. With **downto**, i descends instead: `for i := n downto 1 do`. The control variable must be of **ordinal type**, declared like any variable, and start and final are evaluated **once**, before the first pass. For a count known in advance, for is the exact instrument — no manual counter-keeping anywhere. For protects its steering: the body must **not change the control variable** — assigning to i inside its own loop is forbidden, because the loop's counting would break. After the loop ends, the control variable's value is **undefined** (except when the loop was left by goto) — using it afterwards is an error of reasoning even when a machine tolerates it. And the body's one instruction becomes a **compound** begin…end when the repeated work is several instructions: for's single line, steering a block. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: for i := 1 to n do <instruction>. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: By one (or descend by one with downto). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Once, before the first pass. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: An ordinal type. Do this with a real example of your own and write or say how you know it is right.
