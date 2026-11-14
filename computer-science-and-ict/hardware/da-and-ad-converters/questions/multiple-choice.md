# DA and AD Converters — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) An 8-bit DAC with Vref = 5 V receives the code 10000000. Its output is —**
a) 5 V  b) 2.5 V  c) 1.25 V  d) 0 V
**Answer: b) 2.5 V** — Output = Vref × value/2ⁿ = 5 × 128/256 = 2.5 V — half the code range gives half the voltage.

**2. (Sub lesson 1) As a DAC's input counts upward one step at a time, its output —**
a) Moves smoothly like a ramp  b) Climbs in equal small steps — a staircase  c) Jumps randomly  d) Stays at half scale
**Answer: b) Climbs in equal small steps — a staircase** — Each code step adds one equal voltage step (Vref/2ⁿ); only with many bits do the steps become hard to see.

**3. (Sub lesson 1) In the R–2R ladder, the most significant bit contributes —**
a) The same as every other bit  b) Half of full scale, with each next bit contributing half of the previous  c) One volt always  d) Nothing until others are set
**Answer: b) Half of full scale, with each next bit contributing half of the previous** — The ladder weights the bits by place value: ½, ¼, ⅛… of full scale — binary weights built from resistors.

**4. (Sub lesson 2) An ADC's resolution of n bits means it distinguishes —**
a) n levels  b) 2n levels  c) 2ⁿ levels  d) n² levels
**Answer: c) 2ⁿ levels** — Each added bit doubles the levels: 2ⁿ — 8 bits give 256.

**5. (Sub lesson 2) A 4-bit ADC over a 0–8 V range receives 5.2 V. Its output code is —**
a) 0110  b) 1010  c) 0101  d) 1100
**Answer: b) 1010** — Each level is 8/16 = 0.5 V wide; 5.2 V falls in level 10 (5.0–5.5 V), and 10 in binary is 1010.

**6. (Sub lesson 2) Flash ADCs are extremely fast mainly because —**
a) They use no electricity  b) All comparators judge the input at the same instant  c) They have many bits  d) They skip quantisation
**Answer: b) All comparators judge the input at the same instant** — Every level boundary is tested simultaneously by its own comparator; the price is one comparator per level, so flash converters use few bits.
