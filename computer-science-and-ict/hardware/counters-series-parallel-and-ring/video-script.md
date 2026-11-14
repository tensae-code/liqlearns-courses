# Video script — Counters — Series, Parallel and Ring

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Pulses arrive. Somebody must count them. A chain of flip-flops can.

First flip-flop toggles every pulse. It clocks the second, which toggles every two. The third, every four.

Read the outputs together: 000, 001, 010, 011 — binary counting, done by toggling cells.

n flip-flops, 2-to-the-n states, then back to zero. That is the modulus.

In the series counter the change ripples down the chain — simple, but the far end settles late.

In the parallel counter every stage hears the same clock and changes at the same instant. Faster, cleaner, more wiring.

Close a shift register into a ring with a single 1 inside: the 1 walks round, one output per state, nothing to decode.
