# Video script — The Counted Loop in Algorithms

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **counted loop** repeats its body a **known number of times**. Its steersman is the **counter**: a variable that starts at an initial value (usually 1), **increases by a step** (usually 1) after each pass through the body, and is compared each time with the **final value**; when the counter passes the final value, the loop ends. Body, counter, limit: name the three and any counted loop in any notation — flowchart, pseudocode or Pascal's for — is the same animal.
The counted loop's classic work: anything with a **fixed count of like steps** — drawing a fence of n posts, reading n marks, summing the first n numbers. Tracing is its proof: for the sum 1+2+3, the counter walks 1, 2, 3 while the sum grows 1, 3, 6 — a table of counter, body action and accumulator shows the loop **must** end (the counter climbs to its limit without fail) and **must** be right (each value enters exactly once). An **accumulator** — a variable gathering the running total — is the counted loop's usual partner.
