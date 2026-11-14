# Logic Gates — NOT, AND, OR, NAND, NOR, XOR — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) A logic gate remembers the inputs it received a moment ago.**
**Answer: False** — A gate answers its present inputs only; memory appears later, when gates are wired in a loop as flip-flops.

**2. (Sub lesson 1) The OR gate's output is 0 only when all its inputs are 0.**
**Answer: True** — OR is 'at least one': a single 1 is enough for output 1, so all-zeros is the only 0-row.

**3. (Sub lesson 2) XNOR gives 1 when its two inputs are the same.**
**Answer: True** — XNOR is XOR with a bubble — it checks equality: 00 → 1, 11 → 1, different inputs → 0.

**4. (Sub lesson 2) A circuit can be built using only NAND gates.**
**Answer: True** — NAND is universal: it builds NOT (inputs tied), AND (NAND + NOT) and OR (De Morgan), and those build everything.
