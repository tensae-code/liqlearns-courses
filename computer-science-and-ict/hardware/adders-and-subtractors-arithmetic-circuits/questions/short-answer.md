# Adders and Subtractors — Arithmetic Circuits — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Build the full adder's hardest row by hand: A = 1, B = 1, Cin = 1. Give Sum and Cout and the reasoning through the two half adders.**
**Answer: First half adder: 1 + 1 gives sum 0, carry 1. Second half adder adds that 0 to Cin 1: sum 1, carry 0. Cout is the OR of the two carries: 1 OR 0 = 1. So Sum = 1, Cout = 1 — indeed 1 + 1 + 1 = 3 = 11₂.**

**2. (Sub lesson 2) Why is it cheaper to build an adder/subtractor than separate adder and subtractor circuits?**
**Answer: Because two's complement reduces subtraction to addition of a complemented number. A row of XOR gates (steered by SUB) and the existing Cin wire supply the complement, so the expensive part — the full-adder chain — is built once and shared by both operations.**
