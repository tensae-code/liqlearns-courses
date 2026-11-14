# Binary Arithmetic — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) 1 + 1 = 10 is a correct way to think about a binary column overflowing.**
**Answer: True** — The value two is written 10 in binary: the 0 stays in this column, the 1 is the carry into the next.

**2. (Sub lesson 1) Inverting every bit of a number gives its two's complement.**
**Answer: False** — Inverting alone gives the ones' complement; two's complement needs the extra step: add 1.

**3. (Sub lesson 2) When a subtraction by complement produces a carry beyond the register's length, the result is wrong and must be redone.**
**Answer: False** — The carry is discarded by design — the register physically has no place for it, and the remaining bits are exactly the correct difference.

**4. (Sub lesson 2) Binary division needs a memorised times table like decimal long division.**
**Answer: False** — Each quotient bit is only 0 or 1, decided by one question — does the divisor fit? — so there is never a digit to guess.
