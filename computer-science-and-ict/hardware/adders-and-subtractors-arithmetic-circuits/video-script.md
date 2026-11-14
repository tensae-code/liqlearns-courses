# Video script — Adders and Subtractors — Arithmetic Circuits

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Add 1 + 1 and the answer needs two wires: sum 0, carry 1.

The sum column is XOR. The carry column is AND. Two gates — a half adder.

But a real column also has the carry from its neighbour. The full adder takes all three.

Two half adders and an OR gate make a full adder. Chain them, and whole words can be added.

Subtraction needs no second machine. Two's complement turns it into addition.

One control line, SUB: at 0 the circuit adds; at 1 the XOR gates flip B, the carry-in adds the missing 1 — and the adder subtracts.
