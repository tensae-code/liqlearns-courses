# Registers — Stationary and Shift — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) An 8-bit register can hold the word 10110100.**
**Answer: True** — Eight flip-flops hold eight bits — exactly one byte, such as 10110100.

**2. (Sub lesson 1) Reading a stationary register destroys its stored word.**
**Answer: False** — Reading just observes the Q outputs; the word stays stored until the next clock tick overwrites it.

**3. (Sub lesson 2) In a shift register, the bit in the last flip-flop is lost when the next tick comes.**
**Answer: True** — Each tick moves every bit one place; the last bit shifts out of the row (in SISO it is delivered as the output) and leaves the register.

**4. (Sub lesson 2) SISO and SIPO shift registers contain different numbers of flip-flops for the same word length.**
**Answer: False** — The in/out names describe how data enters and leaves, not the row itself — both hold one flip-flop per bit.
