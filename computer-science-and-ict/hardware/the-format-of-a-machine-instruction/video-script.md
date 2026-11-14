# Video script — The Format of a Machine Instruction

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **machine instruction** is a row of bits divided into **fields**. The **operation code (opcode)** field names **what to do** — add, load, store, jump — from the processor's fixed instruction set. The **address field(s)** name **where the operands are** — which registers, or which memory addresses, hold the data the operation works on. An instruction of 16 bits might spend 4 on the opcode (16 possible operations) and 12 on an address (4096 addressable cells): the format is a budget of bits, spent between variety of operations and reach of addresses.
Instructions are classed by their **address count**: a **three-address** instruction names both operands and the result's place (add a, b, c); **two-address** overwrites one operand with the result; **one-address** works with an implied **accumulator**; **zero-address** works on a **stack**, its operands understood. Fewer addresses make **shorter instructions and a simpler processor**, at the price of more instructions per job. The format chosen is the architecture's founding compromise, visible in every program the machine will ever run.
