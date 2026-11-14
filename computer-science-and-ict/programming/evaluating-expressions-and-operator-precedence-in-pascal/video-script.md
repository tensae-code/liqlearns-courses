# Video script — Evaluating Expressions — and Operator Precedence in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **expression** is built from **operands** (the values: constants, variables, function results) joined by **operators** (the operations: +, −, *, /, div, mod and the rest). Evaluating it means **working it out to one value**. The parts are read as in algebra, but written flat, in one line: a fraction's numerator and denominator must be bracketed — (a + b) / (c − d) — because the line has no floors. A **standard function call** like sqrt(x) is an operand: it is evaluated to its value wherever it stands.
Operators bind with different strength — **precedence**. The order of evaluation: **brackets first**; then the multiplication family (**, /, div, mod, and*)**; then the addition family (**, −, or*)**; operators of equal strength work **left to right**. So 2 + 3 * 4 is 14, not 20, and (2 + 3) * 4 is 20 because brackets outrank all. Relations (=, <, >…) bind weakest of all, comparing finished values. The professional's rule rides with it: when the reader could hesitate, **bracket** — precedence is for the machine, clarity is for people.
