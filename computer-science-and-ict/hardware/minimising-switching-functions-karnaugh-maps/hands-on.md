# Hands-on — Minimising Switching Functions — Karnaugh Maps

The lesson with your hands and your feet, not only your eyes.

## Algebra against map
Take Y = Ā·B̄·C + Ā·B·C + A·B·C (three variables). Minimise it algebraically first, writing the law at each step. Then draw the three-variable map, place the 1s, group them, and read the answer off. The two methods must land on the same expression — if they do not, one of them has a mistake, and the truth table is the judge.

## The wrapping group
On a four-variable map, place 1s in the four corner cells only. Find the group that covers them (it wraps around both edges) and read off the term. Then say in words why the corners are neighbours even though the drawing puts them far apart.

## In the simulator
In TINA or Circuit Wizard, build a function before and after minimising (use the gate symbols from the logic gates lesson). Count the gates in each version and run both through all input combinations. Same table, fewer gates — write down the saving.
