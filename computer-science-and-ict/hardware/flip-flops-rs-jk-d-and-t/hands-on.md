# Hands-on — Flip-Flops — RS, JK, D and T

The lesson with your hands and your feet, not only your eyes.

## Run the RS story
On paper, start an RS flip-flop at Q = 0. Apply this story in order: set; nothing; nothing; reset; nothing; set; reset. Write Q after each step. Then write one sentence on what would make the last two steps dangerous if they overlapped in time.

## Tick by tick
A D flip-flop's input D over six clock ticks is: 1, 0, 1, 1, 0, 0. Write Q after each tick. Beside it, a T flip-flop has T = 1 for all six ticks starting from Q = 0: write its Q after each tick, and state in one line why its output wave is half the clock's speed.

## In the simulator
In TINA or Circuit Wizard, build or select a D flip-flop, drive D with a switch and the clock with a pulse button. Write D's value, press the clock, and record Q — five times with different D values. Then hold the clock still and flip D: watch Q refuse to follow until the next tick. That refusal is storage, seen with your own eyes.
