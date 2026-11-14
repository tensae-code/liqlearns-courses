# Hands-on — Logic Gates — NOT, AND, OR, NAND, NOR, XOR

The lesson with your hands and your feet, not only your eyes.

## Gates from tables
Without looking, write the truth table of every gate in this lesson: NOT, AND, OR, NAND, NOR, XOR, XNOR. Then check them against the lesson and fix any row. The NAND and NOR tables must be exact flips of AND and OR — if a flip is wrong anywhere, find it by the bubble rule.

## Everything from NAND
On paper, draw: (a) an inverter made from one NAND; (b) an AND made from two NANDs; (c) an OR made from three NANDs, using De Morgan. Under each, write its truth table and check it does the right job.

## In the simulator
This is the book's own way: in TINA or Circuit Wizard, place each gate, drive its inputs with switches and its output with a lamp, and record the full table for NAND and for XOR. Then build the AND-OR-INVERT complex gate and verify its output against the expression Y = NOT(A·B + C·D) on all sixteen input combinations — or as many as time allows, chosen to cover each AND pair.
