# Flip-Flops — RS, JK, D and T — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Why must a flip-flop be built with a feedback loop — what goes wrong without one?**
**Answer: Without feedback, a circuit's outputs depend only on its present inputs, like every gate — the moment inputs change, all trace of the past is lost. The loop feeds the output back as an input, so the circuit's present depends on its own past state: that is exactly what remembering one bit means.**

**2. (Sub lesson 2) Which flip-flop would you choose to store a bit written from a data line, and which to build a counter from — and why?**
**Answer: The D flip-flop for storage: Q copies the data line on the clock tick and holds it between ticks. The T (or JK wired as T) for counting: it toggles on every tick, and a chain of togglers counts in binary, as the counters lesson shows.**
