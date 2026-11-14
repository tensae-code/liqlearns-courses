# Video script — Combinational and Sequential Logic Circuits

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **combinational circuit's** output depends **only on the inputs it holds now**: same inputs, same output, always, with no memory of before. Its crown example is the **adder**: the **half-adder** adds two bits into a **sum and a carry** (XOR for the sum, AND for the carry); the **full-adder** adds **three** — two bits and the carry-in from the place before — and chains of full-adders add whole numbers place by place, the arithmetic heart the CPU lessons will meet.
A **sequential circuit's** output depends on its inputs **and on what it remembers** — its stored state. Its atom is the **flip-flop**: a circuit holding **one bit**, set and reset by its inputs, keeping its bit until told to change — memory made of gates. Chained and clocked, flip-flops become **counters** (counting pulses in binary, each flip-flop a place) and the registers of later chapters. The chapter's test for any circuit is now one question: does it remember? Combinational answers; sequential answers *and* remembers.
