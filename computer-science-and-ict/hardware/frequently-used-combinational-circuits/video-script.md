# Video script — Frequently Used Combinational Circuits

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **encoder** turns **one active input line** (of 2ⁿ) into its **n-bit binary code** — the keyboard's innards, naming the pressed key. A **decoder** does the reverse: an n-bit code **activates exactly one** of 2ⁿ output lines — the circuit that chooses which memory bank, display digit or device a code addresses. The pair are mirror images around a code: the encoder compresses lines into bits; the decoder expands bits back into one chosen line.
A **multiplexer (MUX)** chooses **one of several inputs** to send to its single output — a selector switch for signals, steered by control bits; a **demultiplexer** routes one input to **one of several outputs**. A **comparator** judges two binary numbers and reports **greater, equal or less** in three outputs. Route, choose, judge: with gates, adders and these, the combinational toolkit is the whole of the machine's **present-tense** electronics — everything memoryless the CPU does is built from them.
