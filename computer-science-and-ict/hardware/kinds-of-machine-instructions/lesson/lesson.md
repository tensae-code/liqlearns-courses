# Kinds of Machine Instructions

## Do it first

An opcode field promises a set of operations. Grade 11 sorts that set into its working families — the four jobs every processor's instructions divide among themselves.

## Sub lesson 1 — Movers and workers — transfer, arithmetic, logic

The **data-transfer** instructions **move** values without changing them: load (memory → register), store (register → memory), move between registers, push and pop on the stack. The **arithmetic** instructions **compute**: add, subtract, multiply, divide, increment, decrement — on the registers' contents. The **logic** instructions compute **bitwise**: AND, OR, NOT, XOR applied to every bit of a word at once, and **shifts** that slide a word's bits left or right — the same operations the Boolean chapter built from gates, now wearing opcodes.

In your mind's eye: movers and workers — transfer, arithmetic, logic.

## Sub lesson 2 — Choosers and speakers — control and input/output

The **control** instructions steer the program counter: **jumps** (go to another instruction), **conditional branches** (jump only if a test on the last result holds — the machine's if), **calls** (jump to a subprogram, remembering the return) and **returns**, and **halt**. The **input/output** instructions speak to the **devices** — reading a key, sending a character to the display — through the machine's ports. Four families, and the count is closed: every program ever written for the machine is these, in some order.

In your mind's eye: choosers and speakers — control and input/output.

## Say it to your companion

Tell your companion, in your own words: The **data-transfer** instructions **move** values without changing them: load (memory → register), store (register → memory), move between registers, push and pop on the stack. The **arithmetic** instructions **compute**: add, subtract, multiply, divide, increment, decrement — on the registers' contents. The **logic** instructions compute **bitwise**: AND, OR, NOT, XOR applied to every bit of a word at once, and **shifts** that slide a word's bits left or right — the same operations the Boolean chapter built from gates, now wearing opcodes. The **control** instructions steer the program counter: **jumps** (go to another instruction), **conditional branches** (jump only if a test on the last result holds — the machine's if), **calls** (jump to a subprogram, remembering the return) and **returns**, and **halt**. The **input/output** instructions speak to the **devices** — reading a key, sending a character to the display — through the machine's ports. Four families, and the count is closed: every program ever written for the machine is these, in some order. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: They move values without changing them — load, store, move, push, pop. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Load goes memory → register; store goes register → memory. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Add, subtract, multiply, divide, increment, decrement. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Bitwise — to every bit of a word at once. Do this with a real example of your own and write or say how you know it is right.
