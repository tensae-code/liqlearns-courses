# Ones and Twos Complement and Signed Binary Numbers

## Do it first

Write the number 5 in 8-bit binary: 00000101. Now flip every bit — every 0 becomes 1, every 1 becomes 0 — and look at what you have made. You have just built the machine's way of writing minus 5, without any minus sign. Keep both rows — the lesson names what you did and then improves it.

## Sub lesson 1 — Signed numbers and the ones complement

Binary digits have no minus sign, yet computers must store negative numbers. The fix is to give one bit a second job: in a **signed** binary number, the leftmost bit — the **most significant bit** — is the **sign bit**. 0 means positive, 1 means negative. In 8 bits, the other seven bits hold the size of the number, so an 8-bit signed number runs from −128 to +127.

The first scheme is the **ones complement**: to write a negative number, take its positive pattern and **flip every bit** — 0s become 1s, 1s become 0s. Plus 5 is 00000101, so minus 5 in ones complement is 11111010. Flipping again brings you back, which makes negation easy.

Ones complement has a wart: zero comes in two forms, 00000000 (+0) and 11111111 (−0), which wastes a pattern and confuses comparisons. That wart is why machines moved on to the twos complement, next.

In your mind's eye: two rows of eight bit boxes: 00000101 labelled +5, and beneath it 11111010 with curved arrows showing every bit flipped.

## Sub lesson 2 — Twos complement — and subtracting by adding

The **twos complement** of a number is its ones complement **plus 1**. Minus 5: flip 00000101 to 11111010, add 1, and you get 11111011. That pattern is how real machines store −5 in 8 bits. Twos complement has only one zero (flipping 00000000 and adding 1 overflows back to 00000000), and its range is uneven in a useful direction: −128 to +127.

The payoff is subtraction. A computer's adder circuit only adds — so the machine turns A − B into A + (twos complement of B). Example: 9 − 5. Take 00001001 (9), add 11111011 (−5 in twos complement): the sum is 1 00000100 — nine bits. Throw away the carry that falls off the left end of the 8-bit register and 00000100 remains: 4, correct, with sign bit 0.

If the answer is negative it comes out already written in twos complement: 5 − 9 gives 11111100, whose sign bit is 1; flip and add 1 to read its size — 00000100, so the answer is −4. Kenya's Form 3 data-representation chapter teaches signed numbers and complement subtraction as the closing step of its number-systems work, because this is the point where binary stops being notation and becomes machinery.

In your mind's eye: the addition 00001001 + 11111011 lined up in columns, with the ninth carry bit circled and crossed out, leaving 00000100.

## Say it to your companion

Tell your companion, in your own words: A computer stores negative numbers in binary by complementing: the ones complement flips every bit, and the twos complement flips every bit and adds 1 — with the leftmost bit acting as the sign, twos complement lets the machine subtract by adding, using the same adder circuit it already has. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: read the sign of a binary number from its leftmost bit and state the range of an 8-bit signed number. Do this with a real example of your own, and write or say how you know it is right.
2. Show it, don't just say it: write the ones complement of any binary number by flipping its bits. Do this with a real example of your own, and write or say how you know it is right.
3. Show it, don't just say it: write the twos complement by flipping the bits and adding 1. Do this with a real example of your own, and write or say how you know it is right.
4. Show it, don't just say it: subtract two binary numbers by adding the twos complement of the number being taken away. Do this with a real example of your own, and write or say how you know it is right.
