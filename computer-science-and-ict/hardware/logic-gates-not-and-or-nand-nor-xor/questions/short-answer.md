# Logic Gates — NOT, AND, OR, NAND, NOR, XOR — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) A learner says: 'NAND is just a faulty AND.' Correct them in two sentences.**
**Answer: NAND is AND with an inverter deliberately added on its output — the bubble on its symbol. Its table is AND's table flipped, and that flip is exactly what makes it universal: from NAND alone every other gate can be built.**

**2. (Sub lesson 2) Using De Morgan, explain how an OR gate is made from NAND gates.**
**Answer: De Morgan says A + B = NOT(NOT A · NOT B). So invert A and invert B (two NANDs with tied inputs), feed both into a third NAND: its output is NOT(Ā · B̄) = A + B — an OR built from three NANDs.**
