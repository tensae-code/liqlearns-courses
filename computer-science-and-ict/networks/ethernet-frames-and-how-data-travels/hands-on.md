# Hands-on — Ethernet Frames and How Data Travels

The lesson with your hands and your feet, not only your eyes.

## Read a frame by hand
Take the printed frame from the lesson. With a ruler, mark off the fields: preamble, six bytes of destination, six bytes of source, two bytes of type, the data, the last four bytes of check. Write each field's job beside it. Then answer in writing: who sent this frame, who receives it, and what would happen if one byte of the data flipped on the way?

## Catch your own (if Wireshark is available)
Open Wireshark, start a capture on the local network for ten seconds, and stop it. Pick one frame. Find its destination and source MAC addresses and its type field, and write down what it was carrying. Compare with a partner: did your frames go to the same kinds of addresses?
