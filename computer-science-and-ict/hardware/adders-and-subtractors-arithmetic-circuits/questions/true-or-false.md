# Adders and Subtractors — Arithmetic Circuits — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) The carry output of a half adder is A · B.**
**Answer: True** — Carry is 1 only on the row 1 + 1 — the AND table exactly.

**2. (Sub lesson 1) A chain of half adders can add two 8-bit words correctly.**
**Answer: False** — Half adders have no carry-in door, so columns beyond the first would ignore the carries arriving from their right-hand neighbours. Full adders are required.

**3. (Sub lesson 2) With SUB = 0, the adder/subtractor adds A + B unchanged.**
**Answer: True** — X ⊕ 0 = X, so B passes through the XORs untouched and Cin = 0: plain addition.

**4. (Sub lesson 2) The adder/subtractor contains a separate subtraction circuit beside the adder.**
**Answer: False** — There is only the adder chain; the XOR steering and Cin = SUB re-purpose it for subtraction. That economy is the whole design.
