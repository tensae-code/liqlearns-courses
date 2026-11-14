# Counters — Series, Parallel and Ring — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) In a series (ripple) counter, each flip-flop after the first is clocked by —**
a) The main pulse line  b) The previous flip-flop's output  c) Its own output  d) A battery
**Answer: b) The previous flip-flop's output** — Chaining output-to-clock is what makes each stage toggle at half the previous stage's rate — and what makes the change ripple.

**2. (Sub lesson 1) A 4-bit binary counter counts modulo —**
a) 4  b) 10  c) 16  d) 100
**Answer: c) 16** — Four flip-flops give 2⁴ = 16 states, 0000 to 1111, then it wraps to 0000: modulo 16.

**3. (Sub lesson 1) The weakness of the series counter is —**
a) It cannot count past 8  b) The counting change ripples stage by stage, so far stages settle late and outputs briefly spell wrong values  c) It needs no clock  d) It counts in decimal
**Answer: b) The counting change ripples stage by stage, so far stages settle late and outputs briefly spell wrong values** — Asynchronous clocking means delays accumulate down the chain — the price of its simplicity.

**4. (Sub lesson 2) In a parallel (synchronous) counter, all flip-flops —**
a) Clock each other  b) Receive the same clock pulse at the same instant  c) Have no clock  d) Toggle on every pulse
**Answer: b) Receive the same clock pulse at the same instant** — One shared clock heard by everyone at once removes the ripple; gates decide which stages toggle on each pulse.

**5. (Sub lesson 2) A stage in a binary counter toggles exactly when —**
a) The clock stops  b) All lower stages stand at 1  c) Its own output is 0  d) The counter is reset
**Answer: b) All lower stages stand at 1** — That is binary counting's carry rule: a higher place changes only when every lower place is full of 1s rolling over.

**6. (Sub lesson 2) A ring counter with 6 flip-flops has how many states, and what marks each state?**
a) 64 states; the outputs spell a binary number  b) 6 states; exactly one output is 1 in each state  c) 12 states; two outputs are 1  d) 6 states; all outputs are 1 in turn together
**Answer: b) 6 states; exactly one output is 1 in each state** — The single circulating 1 has six positions — six states, each announced directly by its one active output, no decoding needed.
