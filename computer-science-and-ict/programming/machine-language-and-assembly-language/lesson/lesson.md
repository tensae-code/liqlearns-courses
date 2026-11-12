# Machine language and assembly language

## Do it first

Try this in your head: give a friend an instruction using only the numbers 1 and 0 - no words at all. Hard, is it not? That is exactly how the first programs had to be written. This lesson shows the two lowest-level languages: the binary the computer itself understands, and the symbol language invented to make that binary a little easier for people.

## Sub lesson 1 - Machine language - binary the computer understands

A **program** is a set of instructions telling a computer what to do. Programs are written in a **programming language**, and the low-level kinds come first.

**Machine language** writes everything - instructions, numbers, memory locations - in **binary: 1s and 0s** and nothing else. It is the **only language the computer understands directly**, with no translation step in between. That makes it **very fast** and **memory-efficient**. The price: it is **very hard to write** - a person must think in strings of 1s and 0s.

[Picture 18100 - one instruction, two low-level forms]

## Sub lesson 2 - Assembly language and the assembler

**Assembly language** takes one step towards people: instead of binary, it writes instructions with **symbols called mnemonics** - short word-like codes that stand for operations.

Mnemonics make programs **easier** to write than pure binary - but assembly is **still difficult**, and the computer does **not** understand it directly. So one more program is needed: an **Assembler**, which **translates assembly language into machine language** before the computer can run it.

Remember the chain: people write assembly -> the Assembler translates -> the computer runs machine language.

## Say it to your companion

Tell your companion: what a program is; what machine language is written in and why it is both fast and hard; and what an assembler does. Your companion asks: "Can the computer run assembly language directly?" - you answer no, and say why.

## Do It Yourself

1. Write the words 1 and 0 version of a tiny instruction in your own made-up binary code, then write the same instruction as a mnemonic of your own invention. Say which was easier to read.
2. A friend says: "Assembly language runs on the computer by itself." Correct the sentence in one line.
3. Say, in order, the three steps between a person writing assembly language and the computer doing the work.
