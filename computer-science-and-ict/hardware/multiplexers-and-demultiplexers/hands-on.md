# Hands-on — Multiplexers and Demultiplexers

The lesson with your hands and your feet, not only your eyes.

## Be the MUX
Four classmates each hold a card with a different word and keep changing their words every ten seconds. You are the 4-to-1 MUX: a partner calls select codes (00, 01, 10, 11) in a random order, and you must always read aloud the word on the chosen card only. Sixteen calls; count your mistakes. Then swap roles and explain to the new MUX why the unchosen cards do not matter.

## Design the DEMUX delivery
A 1-to-8 DEMUX must deliver a data stream. Write how many select lines it has, and for select codes 000, 011 and 110, which output receives the data and what all other outputs are. Then say which single change would turn this DEMUX back into the decoder of the last lesson.

## In the simulator
In TINA or Circuit Wizard, build or select a 4-to-1 MUX. Set its four inputs to different steady values (1, 0, 1, 0), then step the select code through 00, 01, 10, 11 and record Y each time. Add the matching 1-to-4 DEMUX on the output of a shared line and deliver a pulse to output 3 only — both select codes must agree; prove it by setting them differently and watching the delivery go to the wrong door.
