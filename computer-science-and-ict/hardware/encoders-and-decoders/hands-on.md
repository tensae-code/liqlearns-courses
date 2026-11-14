# Hands-on — Encoders and Decoders

The lesson with your hands and your feet, not only your eyes.

## Derive the encoder
On paper, write the BCD table for digits 0–9. Read it column by column and write the OR expression for each of the four outputs (weights 8, 4, 2, 1). Check your 1-output expression has exactly the five odd digits in it. You have just designed the encoder from its table.

## Run the decoder backwards and forwards
For the 2-to-4 decoder, write the AND expression of each output (one uses A and B̄ — find which). Then answer as the decoder: inputs 01 → which output? Inputs 11 → which output? Then as its designer: to wake output 0 only, what must each AND gate receive?

## In the simulator
In TINA or Circuit Wizard, build the 2-to-4 decoder from AND gates and inverters (or select it ready-made) and run all four input codes, recording the single active output each time. Then wire a decimal-to-BCD encoder from OR gates if the library allows, and test digits 3, 6 and 9 against your derived expressions.
