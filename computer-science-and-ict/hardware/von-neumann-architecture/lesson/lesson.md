# Von Neumann Architecture

## Do it first

Every program you have ever run was stored somewhere before it ran. This lesson shows the one design that made that normal: program and data sharing a single memory.

## Sub lesson 1 — One memory for program and data

In the **von Neumann architecture** the computer keeps **both** in the **same memory**: the **data** being worked on and the **program** — the list of instructions that says what to do with it. Because the program itself is stored, it can be loaded, changed and replaced like any other data, which is why one machine can run many different programs. The memory is a row of numbered cells (addresses), and each instruction or value sits in a cell the processor can name.

[Picture — one memory for program and data]

## Sub lesson 2 — The processor at work — fetch, decode, execute

The **central processing unit (CPU)** works in a steady cycle: **fetch** the next instruction from memory, **decode** it (work out what it asks for), then **execute** it — with the **control unit** directing the traffic and the **arithmetic-logic unit (ALU)** doing the sums and comparisons. Registers hold the instruction being carried out and the values in play. The single shared path between processor and memory is the design's famous narrow point — the von Neumann bottleneck.

[Picture — the processor at work — fetch, decode, execute]

## Say it to your companion

Tell your companion, in your own words: Almost every computer today follows one stored-program design: the program and the data it works on live together in the same memory, and a processor fetches instructions from that memory one after another, carries them out, and repeats. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The program and the data it works on. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: One machine can load and run many different programs. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Fetch, decode, execute. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Sums and comparisons — the arithmetic and logic. Do this with a real example of your own and write or say how you know it is right.
