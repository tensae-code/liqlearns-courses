# Signed Numbers — Using a Sign Bit

## Do it first

Binary so far counts only the positive world. Real programs must hold debts, temperatures below zero, movements backward. The machine has no minus sign to write — only bits. The first idea for giving it one is beautifully simple, and its flaw is the reason the next lesson exists.

## Sub lesson 1 — The sign bit — one bit for the sign

In **sign-and-magnitude** writing, the **first bit is the sign**: **0 means positive, 1 means negative**, and the remaining bits hold the number's size (its magnitude) exactly as before. In 8 bits, 00000101 is +5 and 10000101 is −5 — one bit spent, the whole positive-and-negative world in reach. The programmer reading a register reads the sign first, then the size, like reading '−' before a decimal number — the scheme is decimal habit, mechanised.

[Picture — The sign bit — one bit for the sign]

## Sub lesson 2 — The trouble — two zeros and hard arithmetic

The scheme's flaw shows at zero: **00000000 is +0 and 10000000 is −0** — two writings of nothing, wasting a pattern and confusing every comparison (are they equal?). Worse, arithmetic breaks its school rules: adding a positive and a negative with the ordinary adder gives wrong answers, because the sign bit is being added as if it were size. The machine needs a writing where one adder serves everything — and that need, named here, is answered by two's complement in the next placement's lesson.

[Picture — The trouble — two zeros and hard arithmetic]

## Say it to your companion

Tell your companion, in your own words: In **sign-and-magnitude** writing, the **first bit is the sign**: **0 means positive, 1 means negative**, and the remaining bits hold the number's size (its magnitude) exactly as before. In 8 bits, 00000101 is +5 and 10000101 is −5 — one bit spent, the whole positive-and-negative world in reach. The programmer reading a register reads the sign first, then the size, like reading '−' before a decimal number — the scheme is decimal habit, mechanised. The scheme's flaw shows at zero: **00000000 is +0 and 10000000 is −0** — two writings of nothing, wasting a pattern and confusing every comparison (are they equal?). Worse, arithmetic breaks its school rules: adding a positive and a negative with the ordinary adder gives wrong answers, because the sign bit is being added as if it were size. The machine needs a writing where one adder serves everything — and that need, named here, is answered by two's complement in the next placement's lesson. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The first bit, given to the sign — 0 positive, 1 negative. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The number's magnitude — its size. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 10000101. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Sign first, then the size. Do this with a real example of your own and write or say how you know it is right.
