# Scratch loops and conditions

## Do it first

The cat from the last lesson only walks right and says hello. Now it must survive the edge of its world, obey four arrow keys, meow ten times audibly, and count its own meows to twelve. Four control problems, in the book's order — conditions first, keys second, loops last. Prove each sub lesson before the next opens.

## Sub lesson 1 — If and if…else at the edge

Begin by modifying the earlier script with chosen Motion, Looks and Sound blocks, discussing each change. Then change Move 10 to Move 100 and click 5–6 times — the sprite leaves the visible stage and stops at the right edge (the stage's coordinates run X −240 to 240, Y −180 to 180). Control it with an if block (Control) plus 'touching mouse pointer' (Sensing) using if…else — the worked reading: if the sprite touches the rightmost edge, set its x position to −100, otherwise move 10 steps right — and compare that script with a given alternative, judging which is better. The teacher's keyed solutions add the edge behaviour in full: Solution A bounces with the Motion palette's 'if on edge, bounce' block (the GIF shows it); Solution B uses an if with the Sensing 'touching edge' block to set the sprite's x position to −93 when the edge is touched, and does nothing when the condition is false — one-way; Solution C is the two-way version, with an else. Pupils are to be asked the difference (teacher guide — evidence).

[Picture 20939 — Scratch loops — a repeat-until script and its count]

## Sub lesson 2 — Arrow-key control inside forever

Move 10 steps left, right, up and down by arrow keys: 'key … pressed' blocks from Sensing, with when-flag-clicked and forever, change x by… and change y by… . The teacher's key states it plainly: keyboard control is built inside a forever loop from 'when key … pressed' sensing blocks for the four arrow keys, each moving the sprite 10 steps (teacher guide — evidence).

## Sub lesson 3 — Repeat and repeat until

Make the cat meow 10 times with a repeat loop and a wait, so each meow is heard clearly — the guide's key adds that a fixed-round loop uses Control's repeat block with a wait block so the sounds are heard distinctly. Then repeat-until: a count variable set to 0, meowing and adding 1 to count inside the loop until count reaches 12 — watch the GIF count. The guide keys the same pattern counting to 5 (repeat-until with an equality operator), and contrasts the loop kinds in words: forever has no stopping condition and runs until the application closes or code interrupts it; repeat-N is count-controlled and stops when the count reaches N; repeat-until does not know its count in advance — the condition can even be fed by input while the chart runs — and Flowgorithm and other languages also offer while, for and do loops (teacher guide — evidence). Close with the group discussion: how if…, if…else, forever, repeat… and repeat until… each work.

[GIF 20953 — the cat meowing in a loop, the counter ticking up]

[GIF 20956 — Solution A: the sprite bounces at the edge]

## Say it to your companion

Tell your companion, in your own words: Scratch control in one graduated set: an if…else at the stage edge, arrow-key control inside forever, a repeat loop for ten meows, and repeat-until counting to 12. Then name the key words of this lesson — the stage's coordinates, the worked if…else, keyboard control, repeat until — and say what each one means.

## Do It Yourself

1. State the difference between Solution B and Solution C.
2. Write what the wait block is for in the meow loop.
3. Say why repeat-until cannot always be replaced by repeat-N.
