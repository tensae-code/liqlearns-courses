# Video script — Kinds of Machine Instructions

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **data-transfer** instructions **move** values without changing them: load (memory → register), store (register → memory), move between registers, push and pop on the stack. The **arithmetic** instructions **compute**: add, subtract, multiply, divide, increment, decrement — on the registers' contents. The **logic** instructions compute **bitwise**: AND, OR, NOT, XOR applied to every bit of a word at once, and **shifts** that slide a word's bits left or right — the same operations the Boolean chapter built from gates, now wearing opcodes.
The **control** instructions steer the program counter: **jumps** (go to another instruction), **conditional branches** (jump only if a test on the last result holds — the machine's if), **calls** (jump to a subprogram, remembering the return) and **returns**, and **halt**. The **input/output** instructions speak to the **devices** — reading a key, sending a character to the display — through the machine's ports. Four families, and the count is closed: every program ever written for the machine is these, in some order.
