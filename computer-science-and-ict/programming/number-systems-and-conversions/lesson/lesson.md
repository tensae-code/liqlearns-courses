# Number Systems and Conversions

## Do it first

Write the number 2026. Now say what each digit is worth: the 2 on the left is worth two thousand, the 0 two places in is worth nothing, and the last 6 is worth only six. The marks are just digits — it is the place that gives each one its worth, and the worth of each place is ten times the place before it. Keep hold of that thought. This lesson shows that ten is a choice, not a law: a computer counts with places worth two times the one before, and the people who build computers write those long binary numbers shortly, in sixteens.

## Sub lesson 1 — Decimal, binary and hexadecimal — bases and place values

Every number system is fixed by one choice: its **base**, also called its radix — how many different digits it has. The system you learned first is **decimal**, base 10. It has ten digits, 0 to 9, and the places are worth powers of ten: 1, 10, 100, 1000, reading from the right. The number 345 means 3×100 + 4×10 + 5×1. Nothing about counting forces ten — ten is a habit of human hands.

A computer's switches are either on or off, two states only, so the computer's own system is **binary**, base 2. It has just two digits, 0 and 1, and each binary digit is called a **bit**. The places are worth powers of two: 1, 2, 4, 8, 16, 32, 64, 128. The binary number 1101 means 1×8 + 1×4 + 0×2 + 1×1 = 13. Reading a binary number is always the same job: write the place values over the digits, add up the places where a 1 stands.

[Picture — the three systems side by side: the same value counted in decimal, in binary and in hexadecimal, with the place values written over each digit]

Binary numbers grow long very fast — the small value 255 already needs eight bits — so the people who build and program computers write them shortly in **hexadecimal**, base 16. Hexadecimal needs sixteen digits: 0 to 9, then the letters A, B, C, D, E, F for the values ten to fifteen. Its places are worth powers of sixteen: 1, 16, 256. The hexadecimal number 2F means 2×16 + 15 = 47. Hexadecimal is not a fourth thing to fear: it is only shorthand, because one hexadecimal digit always stands for exactly four binary digits, as the next part shows.

## Sub lesson 2 — Converting between the systems

Converting never changes a value; it only changes the clothes the value wears. There are four journeys to learn, and each has one steady method.

**Binary to decimal:** add the place values where a 1 stands. 10110₂ = 16 + 4 + 2 = 22.

**Decimal to binary:** divide by 2 again and again, writing down each remainder, until the quotient is 0; then read the remainders from the last one backwards to the first. For 22: 22÷2 = 11 remainder 0; 11÷2 = 5 r 1; 5÷2 = 2 r 1; 2÷2 = 1 r 0; 1÷2 = 0 r 1. Reading backwards: 10110₂ — the same number we started from, which is how you check. A second way to the same answer: take away the biggest power of two that fits, then the biggest that fits what is left, marking 1 under each power used and 0 under the rest.

[Picture — the repeated division of 22 by 2, with the remainders circled and an arrow showing them read backwards into 10110]

**Binary to hexadecimal:** split the bits into groups of four, starting from the right (add zeros at the left if the last group is short), turn each group into its value 0–15, and write that value as one hexadecimal digit. 10110₂ splits as 0001 0110 = 1 and 6, so 10110₂ = 16₁₆.

**Hexadecimal to binary:** do the exact opposite — write exactly four bits for every hexadecimal digit. 2F₁₆ = 0010 1111 = 101111₂.

**Decimal to hexadecimal:** divide by 16 repeatedly and read the remainders backwards, writing remainders of ten or more as letters. Whatever the journey, finish by converting back: if you do not land on the number you started with, the mistake is in the journey, not in the number.

## Say it to your companion

Tell your companion, in your own words: a number system is fixed by its base; decimal counts in tens, binary in twos with bits, hexadecimal in sixteens with digits 0–9 and letters A–F; and converting only changes how a value is written, never the value. Show one conversion each way on paper as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: name the base and the digits of the decimal, binary and hexadecimal number systems. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: work out the decimal value of a binary or hexadecimal number from its place values. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: convert a decimal number into binary by repeated division by 2, and check by converting back. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: convert between binary and hexadecimal by grouping bits in fours. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
