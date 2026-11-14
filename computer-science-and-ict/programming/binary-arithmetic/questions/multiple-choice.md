# Binary Arithmetic — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) In binary addition, 1 + 1 + 1 (a column with a carried 1) gives —**
a) 3  b) Write 1, carry 1  c) Write 0, carry 1  d) Write 1, carry 0
**Answer: b) Write 1, carry 1** — Three ones total 3, which in binary is 11: write the 1, carry the 1.

**2. (Sub lesson 1) The two's complement of 0011 (the number 3) in 4 bits is —**
a) 1100  b) 1101  c) 0011  d) 1011
**Answer: b) 1101** — Invert: 1100; add 1: 1101 — this is −3, and 0011 + 1101 = 10000, zero in a 4-bit register.

**3. (Sub lesson 1) In 4-bit two's complement, numbers beginning with bit 1 are —**
a) Larger than 8  b) Negative  c) Invalid  d) Odd
**Answer: b) Negative** — The top bit acts as the sign: 0 for positive (0 to +7), 1 for negative (−1 to −8).

**4. (Sub lesson 2) To compute A − B with an adder, the machine actually adds —**
a) A + B  b) A + (ones' complement of B)  c) A + (two's complement of B), discarding the final carry  d) B + (two's complement of A)
**Answer: c) A + (two's complement of B), discarding the final carry** — A − B = A + (−B), and −B in machine form is the two's complement; the overflow carry beyond the register length is discarded.

**5. (Sub lesson 2) Shifting a binary number one place to the left —**
a) Divides it by 2  b) Multiplies it by 2  c) Adds 1 to it  d) Inverts it
**Answer: b) Multiplies it by 2** — Each place is worth double the previous, so moving every bit one place left doubles the value — the engine of shift-and-add multiplication.

**6. (Sub lesson 2) 110 ÷ 10 in binary (6 ÷ 2) gives quotient —**
a) 10  b) 11  c) 101  d) 110
**Answer: b) 11** — Compare-and-subtract: 10 fits into 11 → 1, remainder 1; bring down 0 → 10 fits → 1. Quotient 11₂ = 3, remainder 0.
