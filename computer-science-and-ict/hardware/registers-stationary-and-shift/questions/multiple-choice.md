# Registers — Stationary and Shift — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) A register is —**
a) A new kind of gate  b) A row of flip-flops sharing a clock, storing a whole binary word  c) A type of wire  d) A decoder with memory
**Answer: b) A row of flip-flops sharing a clock, storing a whole binary word** — Registers are built from D flip-flops — one per bit — clocked together.

**2. (Sub lesson 1) How many flip-flops does a 16-bit register contain?**
a) 2  b) 8  c) 16  d) 32
**Answer: c) 16** — One flip-flop stores one bit, so n bits need n flip-flops: 16.

**3. (Sub lesson 1) A stationary register stores a word —**
a) One bit per tick, in order  b) All bits at the same instant, on one clock tick  c) Without a clock  d) Only when read
**Answer: b) All bits at the same instant, on one clock tick** — Parallel-in: every flip-flop copies its own input on the same tick, so the whole word lands at once.

**4. (Sub lesson 2) On each clock tick, every bit in a shift register —**
a) Is erased  b) Moves one place along the row  c) Doubles  d) Stays exactly where it was
**Answer: b) Moves one place along the row** — Each flip-flop copies its neighbour's output, so the whole pattern shuffles one place per tick.

**5. (Sub lesson 2) The form that gathers bits arriving one by one on a wire into a standing word is —**
a) SISO  b) SIPO  c) PISO  d) PIPO
**Answer: b) SIPO** — Serial-In, Parallel-Out: bits enter in series over time, then the complete word is read in parallel.

**6. (Sub lesson 2) A PISO register is used to —**
a) Store a word forever  b) Load a word in parallel, then send it out one bit at a time down a single wire  c) Count clock pulses  d) Decode an address
**Answer: b) Load a word in parallel, then send it out one bit at a time down a single wire** — Parallel-In, Serial-Out is the sender: whole word in, then one bit per tick out.
