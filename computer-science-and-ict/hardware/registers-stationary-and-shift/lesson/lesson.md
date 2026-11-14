# Registers — Stationary and Shift

## Do it first

Hold one bit in one flip-flop — that much you can do. Now the machine hands you a whole word, say 10110100, and says: keep all of it, together, ready. And later a different machine whispers bits down a single wire, one per clock tick: 1… 0… 1… 1… — and asks you to hand back the word they form. A row of flip-flops solves both. Ganged together under one clock they are called a register, and Montenegro's book divides them by how the data moves: registers whose bits stay in place, and registers whose bits shift along the row.

## Sub lesson 1 — Stationary registers — the whole word at once

Take eight D flip-flops. Give each its own data input line, D0 to D7. Join all their clock pins into one clock line. That row is an **8-bit register** — in the book's naming, a **stationary register**, because once stored, the bits stay in their places.

Storing is one single event: present the word on the eight input lines — say 1 0 1 1 0 1 0 0 — and tick the clock once. Every flip-flop copies its own input at the same instant, and the whole word is inside. Reading is even simpler: the eight Q outputs show the stored word continuously, all bits at once, until the next tick overwrites it. Because data enters all together and leaves all together, this is called **parallel-in, parallel-out**.

[Picture — eight D flip-flops in a row under one shared clock line, the word 10110100 entering all eight inputs at once and standing stored on the eight Q outputs]

Two facts to carry. First, **capacity**: a register of n flip-flops holds n bits — 8 flip-flops hold one byte, and 'a 32-bit register' is a row of 32. Second, **purpose**: registers are the fastest, smallest memory in the machine, sitting where the work happens. The CPU's own working registers hold exactly the words the current calculation is chewing on — the adders lesson will feed two registers into an arithmetic circuit and catch the result in a third.

## Sub lesson 2 — Shift registers — the bits move along

Now rewire the row: connect each flip-flop's Q to the *next* flip-flop's D, and feed new data only into the first one. Tick the clock — and every bit **moves one place along the row**, like passengers shuffling one seat down a bench. The bit that was in the last flip-flop falls off the end and is gone. This is a **shift register**, and its whole behaviour follows from that one wiring choice.

Feed it the word 1011, one bit per tick, first bit first into the row's near end. Tick 1: the first 1 is inside, alone. Tick 2: it shifts along and the 0 enters behind it. After four ticks the whole word stands in the row — a word that arrived as a *sequence in time* now stands as a *pattern in space*, ready to be read in parallel. That conversion — serial to parallel — is one of the shift register's main jobs in real machines, because wires are serial and words are parallel.

[Picture — a four-flip-flop shift register shown at four successive ticks, the bits 1, 0, 1, 1 entering one per tick and shuffling one place along at each tick]

Ways in and ways out combine into four named forms. **SISO** — serial in, serial out: the register is a delay line, data emerges the far end after n ticks. **SIPO** — serial in, parallel out: the gatherer just described. **PISO** — parallel in, serial out: load the whole word at once, then tick it out one bit per tick down a single wire — the sender. **PIPO** — parallel in, parallel out: the stationary register of the first part, which can be given shifting as an extra talent. Direction matters too: registers may shift right (toward the low end) or left, and the arithmetic lesson will show that shifting a binary word left multiplies it by two and shifting right divides it by two — the humble shuffle is secretly arithmetic.

## Say it to your companion

Tell your companion, in your own words: a register is a row of flip-flops storing a whole word; a stationary register takes the word in all at once on one tick and shows it all at once; a shift register moves every bit one place along on each tick, so it can gather a serial stream into a word (SIPO) or send a word out serially (PISO). Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a register is and how many flip-flops a register of n bits contains. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: explain how a stationary register stores a whole word in one clock tick (parallel-in) and shows it all at once (parallel-out). Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: trace bits through a shift register tick by tick and say where each bit goes on a tick. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: name SISO, SIPO, PISO and PIPO, and say which form gathers a serial stream into a word and which sends a word out serially. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
