# Encoders and Decoders — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) An encoder's job is to turn —**
a) A binary code into one active line  b) One active input line into its binary code  c) Analogue into digital  d) Serial data into parallel
**Answer: b) One active input line into its binary code** — The encoder encodes: which-one (of many lines) becomes a number (in bits).

**2. (Sub lesson 1) In the decimal-to-BCD encoder, pressing key 6 gives the outputs (8, 4, 2, 1) —**
a) 0110  b) 1001  c) 0101  d) 1110
**Answer: a) 0110** — Six in BCD is 0110: the 4 and 2 outputs are 1.

**3. (Sub lesson 1) The 2-weight output of the decimal-to-BCD encoder is the OR of input lines —**
a) 2 and 3  b) 2, 3, 6, 7  c) 1, 3, 5, 7, 9  d) 8 and 9
**Answer: b) 2, 3, 6, 7** — The digits whose BCD has the 2-bit set are 2, 3, 6 and 7.

**4. (Sub lesson 2) A decoder with 3 inputs can have at most how many outputs?**
a) 3  b) 6  c) 8  d) 9
**Answer: c) 8** — Three bits have 2³ = 8 patterns, so up to 8 outputs can be named.

**5. (Sub lesson 2) In a 2-to-4 decoder, input code 10 activates —**
a) Output 0  b) Output 1  c) Output 2  d) Outputs 1 and 3
**Answer: c) Output 2** — The code is read as a binary number: 10₂ = 2, so output 2 — and only output 2 — is active.

**6. (Sub lesson 2) Inside a decoder, each output is produced by —**
a) An OR gate fed by all inputs  b) An AND gate watching for exactly one input pattern, with inverters where the pattern has 0s  c) A flip-flop  d) A resistor
**Answer: b) An AND gate watching for exactly one input pattern, with inverters where the pattern has 0s** — Each output is one truth-table row: an AND of the inputs, each plain or inverted to match that row's pattern.
