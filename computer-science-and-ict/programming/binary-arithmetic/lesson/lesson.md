# Binary Arithmetic

## Do it first

Add 7 + 5 in decimal and notice the moment of the carry: the ones column overflows, you write 2 and carry 1 into the tens. Binary arithmetic is that same dance on a smaller floor. A binary column holds only 0 and 1, so it overflows the moment it tries to hold 2 — and 2, in binary, is written 10: write 0, carry 1. Every operation in this lesson — addition, subtraction with negative numbers, multiplication, division — is built from that one overflow rule and the place values you already know.

## Sub lesson 1 — Binary addition, complements and negative numbers

**Addition.** Work column by column from the right, exactly as in decimal, with binary's tiny table: 0 + 0 = 0; 0 + 1 = 1; **1 + 1 = 0, carry 1**; and a column holding 1 + 1 with a carried 1 gives **1, carry 1**. Example — 1011 + 0110 (11 + 6): ones column 1 + 0 = 1; twos 1 + 1 = 0 carry 1; fours 0 + 1 + carry 1 = 0 carry 1; eights 1 + 0 + carry 1 = 0 carry 1; the final carry stands as a new column: **10001** = 17. Correct — and checking in decimal at the end is a habit, not a shame.

**Negative numbers.** A machine's bits have no room for a minus sign drawn in front, so the sign must live *in* the bits. The book's method is the one every real computer uses: **two's complement**. To write a negative number in, say, 4 bits: write the positive number, **invert every bit** (0s become 1s, 1s become 0s — that intermediate step is the **ones' complement**), then **add 1**. So −5 in 4 bits: 5 is 0101; inverted, 1010; add 1 → **1011**. In a fixed bit length, the top bit now works as the sign: numbers starting with 0 are positive, with 1 negative, and a 4-bit two's-complement register holds −8 to +7.

[Picture — the making of −5 in four bits in three frames: 0101, its bits flipped to 1010, then +1 arriving to give 1011, with the sign bit shaded]

The payoff, next part, is enormous: with two's complement, a machine needs no subtraction circuit at all.

## Sub lesson 2 — Subtraction, multiplication and division

**Subtraction.** With two's complement in hand, subtraction dissolves into addition: **A − B = A + (two's complement of B)**. Compute 7 − 5 in 4 bits: 7 is 0111; the two's complement of 5 is 1011 (from the first part); add: 0111 + 1011 = 10010 — five bits, but the register is four, so the leading carry is **discarded**, leaving **0010 = 2**. Correct. The discarding is not sloppiness: in a fixed-length register the overflow bit physically falls off the end, and two's complement is designed so that the answer left behind is exactly right. One circuit — the adder — now does both jobs, which is why the next lesson's arithmetic circuits are built from adders alone.

**Multiplication.** Use the school method, where every partial product is trivial: multiplying by a 0 bit gives a row of zeros; by a 1 bit, a copy of the number. Compute 101 × 11 (5 × 3): partial product for the ones bit: 101; for the twos bit: 101 shifted one place left, 1010; add them: 101 + 1010 = **1111** = 15. Correct. Notice the engine inside: **shifting a binary number one place left multiplies it by 2** — the same fact the shift register lesson met — so multiplication is 'shift and add the copies where the multiplier has 1s'.

[Picture — the multiplication 101 × 11 laid out in columns: the two partial products, the second shifted one place left, and their sum 1111 beneath]

**Division.** The mirror of multiplication and the inverse of subtraction: work from the left, at each step ask 'does the divisor fit into the current part of the dividend?' — write 1 in the quotient and subtract if it fits, write 0 and shift if not, exactly the rhythm of decimal long division but with only two possible quotient digits, so there is never any guessing of times tables. Compute 1111 ÷ 11 (15 ÷ 3): 11 fits into 11 → quotient bit 1, subtract, remainder 0; bring down the next 1: 01 — 11 does not fit → quotient bit 0, shift; bring down the last 1: 11 fits → quotient bit 1, remainder 0. Quotient **101** = 5, remainder 0. Correct.

Four operations, one small set of rules — and the next lesson wires them into gates: adders and subtractors that do in a flash what your pencil just did in columns.

## Say it to your companion

Tell your companion, in your own words: binary addition carries the moment a column reaches 2; a negative number is stored as two's complement — invert and add 1 — so subtraction becomes addition with the overflow carry discarded; multiplication is shift-and-add; division is compare, subtract and shift, building the quotient bit by bit. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: add two binary numbers column by column, handling 1 + 1 = 0 carry 1 and 1 + 1 + 1 = 1 carry 1. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: form the ones' complement and the two's complement of a binary number for a stated bit length. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: subtract by adding the two's complement and discarding the carry beyond the register length. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: multiply by shift-and-add partial products, and divide by repeated compare-and-subtract, giving quotient and remainder. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
