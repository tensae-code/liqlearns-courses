# Encoders and Decoders

## Do it first

A lift panel has ten buttons, one per floor. You press exactly one. The lift's controller does not want ten wires shouting — it wants the floor number as a code it can compute with. Turning 'one active line out of many' into a binary code is one job. The return job is just as common: the controller holds a binary number, and exactly one thing out of many — one lamp, one memory row, one display digit — must be selected. This lesson teaches the matched pair that do these jobs: the encoder and the decoder.

## Sub lesson 1 — Encoders — many lines in, a code out

An **encoder** answers the question: 'which one is it?' — in binary. It has many input lines and few output lines: one active input line in, and the binary code of that line's number out. With n output bits the code can name 2ⁿ inputs, so a four-output encoder can name up to sixteen input lines.

The book's example is the one inside every keypad: the **decimal-to-BCD encoder**. Ten input lines, one for each digit key 0–9; four output lines carrying the BCD code of the key that is pressed. Press 7 and the outputs read 0111. Press 9 and they read 1001.

Now look at how it is built, because it is only OR gates wearing a plan. Call the four outputs by their BCD weights: 8, 4, 2, 1. The 8-output must be 1 exactly when the pressed digit is 8 or 9 — so the 8-output is the OR of input lines 8 and 9. The 4-output is 1 for digits 4, 5, 6, 7 — the OR of those four lines. The 2-output is the OR of 2, 3, 6, 7, and the 1-output the OR of the odd digits 1, 3, 5, 7, 9. Four OR gates, wired by reading the BCD table column by column — the table *is* the circuit plan.

[Picture — the decimal-to-BCD encoder as a box with ten numbered input lines entering and four outputs leaving, one output opened up to show its OR gate fed by lines 8 and 9]

One honest limitation of the simple encoder: it assumes **only one input is active at a time**. Press two keys together and the outputs OR themselves into a code that matches neither key. Real keypads add priority logic for that case; the book's simple encoder teaches the core idea first.

## Sub lesson 2 — Decoders — a code in, one line out

A **decoder** runs the conversation backwards: a binary code goes in, and exactly **one** output line out of many becomes active — the line whose number the code names. With n inputs there can be up to **2ⁿ outputs**: 2 inputs give 4 outputs, 3 inputs give 8, 4 inputs give 16.

The book's example is the **2-to-4 decoder**. Inputs A and B; outputs numbered 0, 1, 2, 3. Input code 00 activates output 0 and no other; 01 activates output 1; 10 output 2; 11 output 3. Inside, it is AND gates and inverters: each output is one AND gate watching for exactly one pattern — output 2 watches for A = 1, B = 0, so its gate receives A and B̄; output 0 watches Ā · B̄; and so on. Each output is a single row of the truth table, made physical.

[Picture — the 2-to-4 decoder as a box with two inputs and four outputs, output 2 lit for the input 10, and its AND gate shown fed by A and by B through an inverter]

Why the world wants decoders: wherever a binary number must **choose one thing**. A memory chip holds thousands of stored rows; the address is a binary number, and a decoder inside turns it into 'this row, and only this row'. A multiplexed display lights one digit at a time under a decoder's choosing. And the famous partnership: a decoder whose outputs drive a **seven-segment display** turns a BCD code into the lit segments of a visible digit — decoding carried all the way back to something human eyes read.

Hold the pair face to face: **encoder — many lines to a code; decoder — a code to one line**. Same conversation, opposite directions.

## Say it to your companion

Tell your companion, in your own words: an encoder turns one active input line into the binary code of its number — the decimal-to-BCD encoder turns a pressed digit key into BCD using OR gates; a decoder turns a binary code into one active output line — the 2-to-4 decoder uses AND gates and inverters so exactly the matching output wakes; and n bits always mean up to 2ⁿ lines. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what an encoder does and give the outputs of a decimal-to-BCD encoder for any pressed digit. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: derive each output bit of the decimal-to-BCD encoder as an OR of the correct input lines. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: say what a decoder does, and work a 2-to-4 decoder for all four input codes. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: state the 2ⁿ rule both ways: n outputs name up to 2ⁿ encoder inputs; n decoder inputs select up to 2ⁿ outputs — and name jobs each circuit does. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
