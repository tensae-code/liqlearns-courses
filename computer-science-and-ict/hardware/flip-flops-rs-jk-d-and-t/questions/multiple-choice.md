# Flip-Flops — RS, JK, D and T — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) A flip-flop differs from a logic gate because a flip-flop —**
a) Has more inputs  b) Remembers one bit: it holds its state until ordered to change  c) Is faster  d) Uses no electricity
**Answer: b) Remembers one bit: it holds its state until ordered to change** — Gates answer only the present; a flip-flop's feedback loop gives it two stable states — a one-bit memory.

**2. (Sub lesson 1) In an RS flip-flop, the set input's job is to make —**
a) Q = 0  b) Q = 1  c) Q̄ = Q  d) The clock stop
**Answer: b) Q = 1** — Set writes the bit: Q becomes 1. Reset makes Q = 0.

**3. (Sub lesson 1) The input combination forbidden in an RS flip-flop is —**
a) Neither input active  b) Set active only  c) Reset active only  d) Both inputs active at once
**Answer: d) Both inputs active at once** — Both active forces Q and Q̄ to the same value and leaves the next state to chance — designers forbid it.

**4. (Sub lesson 2) In a JK flip-flop, when J and K are both active, the flip-flop —**
a) Breaks  b) Holds  c) Toggles on the clock tick  d) Sets Q to 1 forever
**Answer: c) Toggles on the clock tick** — JK repairs the RS flaw: the both-active case becomes the useful toggle.

**5. (Sub lesson 2) A D flip-flop's Q after a clock tick equals —**
a) Always 1  b) Whatever D was at the tick  c) The opposite of D  d) Whatever Q was before
**Answer: b) Whatever D was at the tick** — D is the copying cell: Q next = D now, at the tick; between ticks it holds.

**6. (Sub lesson 2) A T flip-flop with T = 1, fed a clock of 8 ticks, flips its output —**
a) Never  b) 8 times, at the clock's own rate  c) On every tick, so its output completes a full on-off cycle every 2 ticks — half the clock's rate  d) Once
**Answer: c) On every tick, so its output completes a full on-off cycle every 2 ticks — half the clock's rate** — Toggling every tick means the output needs two ticks per full cycle: its frequency is half the clock's.
