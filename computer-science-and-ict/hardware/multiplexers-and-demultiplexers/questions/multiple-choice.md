# Multiplexers and Demultiplexers — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) A multiplexer connects —**
a) All its inputs to the output at once  b) The one input chosen by its select code to the output  c) Its output to one input  d) The select lines to each other
**Answer: b) The one input chosen by its select code to the output** — The MUX is a digitally controlled switch: the select code picks one input, and only that one reaches the output.

**2. (Sub lesson 1) An 8-to-1 multiplexer needs how many select lines?**
a) 2  b) 3  c) 4  d) 8
**Answer: b) 3** — The select code must name 8 inputs: 2³ = 8, so 3 select lines.

**3. (Sub lesson 1) In a 4-to-1 MUX, select code 10 connects —**
a) D0  b) D1  c) D2  d) D3
**Answer: c) D2** — The code is the input's number in binary: 10₂ = 2, so D2 is connected to Y.

**4. (Sub lesson 2) In a 1-to-4 demultiplexer with select code 01, the data input appears at —**
a) All outputs  b) Output 1 only  c) Output 0 only  d) No output
**Answer: b) Output 1 only** — The DEMUX delivers to the chosen output only; outputs 0, 2 and 3 stay 0.

**5. (Sub lesson 2) A demultiplexer is most closely related to which earlier circuit?**
a) An encoder  b) A decoder with an enable input  c) A flip-flop  d) An adder
**Answer: b) A decoder with an enable input** — Same AND-gate-per-output structure: the decoder's pattern input becomes the DEMUX's data input (enable).

**6. (Sub lesson 2) For a MUX–DEMUX pair to deliver sender 3's data to receiver 3, —**
a) Only the MUX needs the code 11  b) Only the DEMUX needs the code 11  c) Both select codes must be 11 at the same time  d) The select codes must count continuously
**Answer: c) Both select codes must be 11 at the same time** — The MUX must pick sender 3 and the DEMUX must deliver to receiver 3 simultaneously — the two ends share one code.
