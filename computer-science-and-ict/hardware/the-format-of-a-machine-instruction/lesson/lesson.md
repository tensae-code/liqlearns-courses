# The Format of a Machine Instruction

## Do it first

Grade 11's architecture chapter reaches the machine's own sentences. An instruction is not words but a pattern of bits in fields — and the pattern's layout, the format, is designed before the processor is.

## Sub lesson 1 — Fields — operation code and addresses

A **machine instruction** is a row of bits divided into **fields**. The **operation code (opcode)** field names **what to do** — add, load, store, jump — from the processor's fixed instruction set. The **address field(s)** name **where the operands are** — which registers, or which memory addresses, hold the data the operation works on. An instruction of 16 bits might spend 4 on the opcode (16 possible operations) and 12 on an address (4096 addressable cells): the format is a budget of bits, spent between variety of operations and reach of addresses.

[Picture — Fields — operation code and addresses]

## Sub lesson 2 — Formats by address count — three, two, one, zero

Instructions are classed by their **address count**: a **three-address** instruction names both operands and the result's place (add a, b, c); **two-address** overwrites one operand with the result; **one-address** works with an implied **accumulator**; **zero-address** works on a **stack**, its operands understood. Fewer addresses make **shorter instructions and a simpler processor**, at the price of more instructions per job. The format chosen is the architecture's founding compromise, visible in every program the machine will ever run.

[Picture — Formats by address count — three, two, one, zero]

## Say it to your companion

Tell your companion, in your own words: A **machine instruction** is a row of bits divided into **fields**. The **operation code (opcode)** field names **what to do** — add, load, store, jump — from the processor's fixed instruction set. The **address field(s)** name **where the operands are** — which registers, or which memory addresses, hold the data the operation works on. An instruction of 16 bits might spend 4 on the opcode (16 possible operations) and 12 on an address (4096 addressable cells): the format is a budget of bits, spent between variety of operations and reach of addresses. Instructions are classed by their **address count**: a **three-address** instruction names both operands and the result's place (add a, b, c); **two-address** overwrites one operand with the result; **one-address** works with an implied **accumulator**; **zero-address** works on a **stack**, its operands understood. Fewer addresses make **shorter instructions and a simpler processor**, at the price of more instructions per job. The format chosen is the architecture's founding compromise, visible in every program the machine will ever run. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: An operation code field and address field(s). Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: What to do — add, load, store, jump — from the processor's instruction set. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Where the operands are — registers or memory addresses. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: 16 operations; a 12-bit address reaches 4096 cells. Do this with a real example of your own and write or say how you know it is right.
