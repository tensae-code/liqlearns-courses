# Integer Representation and Data Range

## Do it first

A type is a box of a fixed size. This lesson is about how big the box is, how negative numbers fit inside it, and what happens when the number does not fit.

## Sub lesson 1 — Bits fix the range

With **n bits** a type can hold **2ⁿ different patterns**. An unsigned type spends them all on 0 and positives (8 bits: **0 to 255**); a signed type spends about half on negatives (8 bits: **−128 to 127**). Bigger types widen the range: more bits, astronomically more values. Choosing a type is choosing a range big enough for the job — and no bigger than needed.

[Picture — bits fix the range]

## Sub lesson 2 — Negatives and overflow

Signed integers are stored in **two's complement**, the scheme that lets the same addition circuits work for negative and positive numbers. The danger at the edges is **overflow**: add 1 to the maximum and the value wraps to the minimum — 127 + 1 in a signed byte becomes **−128** — with no error message. Programs that count people, money or measurements must use types whose range the data can never outgrow.

[Picture — negatives and overflow]

## Say it to your companion

Tell your companion, in your own words: An integer type stores whole numbers in a fixed number of bits, which fixes its range — with some bits the smallest and largest values are set, negative numbers are held by a sign scheme (in practice two's complement), and pushing past the top of the range overflows into wrong values instead of stopping. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Its fixed number of bits. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: 0 to 255. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Two's complement. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Passing the end of the range and wrapping around. Do this with a real example of your own and write or say how you know it is right.
