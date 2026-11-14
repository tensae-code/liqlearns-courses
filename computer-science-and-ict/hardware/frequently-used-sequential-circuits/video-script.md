# Video script — Frequently Used Sequential Circuits

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **register** is a **row of flip-flops holding one word** — 8, 16, 32 or 64 bits kept together, loaded together, read together: the processor's hands, holding the numbers it is working on *now*. A **shift register** adds motion: at each clock pulse its bits **move one place** along the row — the circuit form of the binary multiplication-by-2 the arithmetic lessons met, and the bridge that turns parallel words into serial streams (one bit at a time) for transmission, and back.
A **counter** is a sequential circuit whose state, advanced by each incoming **pulse**, **counts in binary**: 000, 001, 010, 011… each flip-flop a place, the clock's ticks its input. Counters **divide frequency** (each stage's output pulses at half the rate of the one before), time events, and sequence operations — the machine's patience made of gates. With them the chapter closes its ladder: gates → functions → adders and routers → memory → registers and counters → (next chapter) the whole computer's architecture.
