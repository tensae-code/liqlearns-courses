# Hands-on — Adders and Subtractors — Arithmetic Circuits

The lesson with your hands and your feet, not only your eyes.

## Trace the chain
On paper, draw four full-adder boxes in a chain. Add 1011 + 0110 through them stage by stage, writing each stage's Sum and Cout. Your stage sums, read together, must be 10001 with the final carry — the same answer the arithmetic lesson's pencil found.

## One circuit, two jobs
Using the same drawing, set SUB = 1 and compute 0111 − 0101 through the adder/subtractor: write B inverted, Cin = 1, add, discard the final carry. Then set SUB = 0 and add the same pair. Under each, write the decimal check.

## In the simulator
In TINA or Circuit Wizard, build the half adder from one XOR and one AND gate and run its four input combinations against the truth table. Extend to a full adder from two half adders if the library allows, and feed it A = 1, B = 1, Cin = 1 — the hardest row: predict Sum and Cout before you run it.
