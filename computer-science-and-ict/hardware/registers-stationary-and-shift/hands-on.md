# Hands-on — Registers — Stationary and Shift

The lesson with your hands and your feet, not only your eyes.

## Slide the word
Put four coins in a row as flip-flops. You are the clock. Feed the word 0110 in serially, one bit per 'tick', sliding every coin one place at each tick and writing the row's contents after each tick on paper. After four ticks your paper must show the word standing in the row — and you must be able to point at the first bit you fed in.

## Load and send
On paper, draw a 4-bit register. (a) PIPO: load 1101 in one tick and write the outputs. (b) PISO: starting from 1101 loaded, write the row after each of four shift ticks and the bit that leaves at each tick — the leaving bits, in order, are the serial message. Read them back: what word did the wire carry?

## In the simulator
In TINA or Circuit Wizard, build or select a 4-bit shift register. Drive its serial input with the pattern 1, 0, 1, 1 over four manual clock ticks, recording the row after each tick. Then switch it (or a second register) to parallel loading, load 0110 at once, and shift it out serially, writing the bit that exits at each tick.
