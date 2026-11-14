# Minimising Switching Functions — Karnaugh Maps — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) Minimising a switching function means finding —**
a) A longer expression  b) The smallest expression with the same truth table  c) An expression with no ANDs  d) The truth table
**Answer: b) The smallest expression with the same truth table** — The behaviour (truth table) must stay identical; only the size shrinks — fewer gates, fewer inputs.

**2. (Sub lesson 1) The pair A·B·C̄ and A·B·C merge into —**
a) A·B  b) A·C  c) B·C  d) A·B·C
**Answer: a) A·B** — The two terms differ only in C, so C drops out: A·B·(C̄ + C) = A·B.

**3. (Sub lesson 1) To merge, two terms must differ in —**
a) Every variable  b) Exactly one variable  c) No variables  d) Two variables
**Answer: b) Exactly one variable** — Only a single differing variable can be factored out and killed by X + X̄ = 1.

**4. (Sub lesson 2) Karnaugh map rows and columns are labelled in the order —**
a) 00, 01, 10, 11  b) 00, 01, 11, 10  c) 01, 00, 10, 11  d) 00, 10, 01, 11
**Answer: b) 00, 01, 11, 10** — Gray-code order 00, 01, 11, 10 makes each step change exactly one bit, so neighbours differ in one variable.

**5. (Sub lesson 2) Legal group sizes on a Karnaugh map are —**
a) Any size  b) 1, 2, 3, 4  c) 1, 2, 4, 8  d) 2, 4, 6, 8
**Answer: c) 1, 2, 4, 8** — Groups must be powers of two — 1, 2, 4, 8 — because each doubling drops exactly one more variable.

**6. (Sub lesson 2) A group of 4 ones on a four-variable map drops how many variables from its term?**
a) None  b) One  c) Two  d) Three
**Answer: c) Two** — Each doubling drops one variable: a group of 4 = 2² drops two, leaving a two-variable term.
