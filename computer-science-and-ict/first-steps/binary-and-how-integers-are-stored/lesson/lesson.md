# Binary — and How Integers Are Stored

## Do it first

the binary system and how integers are stored — counting in base two, and how a fixed row of bits holds whole numbers, including negative ones (Vietnam Grade 10)

## Sub lesson 1 — Binary — counting with two digits

The **binary system** counts with two digits only, **0 and 1**, because a computer's memory is built of two-state switches. Place value still rules: each place is worth **twice** the place before it — 1, 2, 4, 8, 16 — so the binary number 1011 is 8 + 2 + 1 = **11** in decimal. Vietnam's Grade 10 data strand begins here, before sound and image data, because every kind of data the computer holds is, at the bottom, numbers written this way.

In your mind's eye: binary — counting with two digits.

[Picture 45006 — binary place values 8 4 2 1 — 1011 makes 8 + 2 + 1 = 11]

## Sub lesson 2 — Storing integers — a fixed row of bits, and the sign problem

An integer is stored in a **fixed number of bits** — 8, 16, 32 or 64 — and the fixing decides the **range**: 8 bits hold 256 different values. Positive integers are stored as their binary value, padded with zeros. **Negative** integers need a scheme: the book's way is **two's complement** — invert the bits of the positive number and add 1 — which lets the same adder add and subtract, and gives one zero instead of two. The price of a fixed size is **overflow**: a result too big for the row of bits wraps or corrupts, and the program must care.

In your mind's eye: storing integers — a fixed row of bits, and the sign problem.

[Picture 45007 — an integer in a fixed row of 8 bits, and the sign problem]

## Say it to your companion

Tell your companion, in your own words: The **binary system** counts with two digits only, **0 and 1**, because a computer's memory is built of two-state switches. Place value still rules: each place is worth **twice** the place before it — 1, 2, 4, 8, 16 — so the binary number 1011 is 8 + 2 + 1 = **11** in decimal. Vietnam's Grade 10 data strand begins here, before sound and image data, because every kind of data the computer holds is, at the bottom, numbers written this way. An integer is stored in a **fixed number of bits** — 8, 16, 32 or 64 — and the fixing decides the **range**: 8 bits hold 256 different values. Positive integers are stored as their binary value, padded with zeros. **Negative** integers need a scheme: the book's way is **two's complement** — invert the bits of the positive number and add 1 — which lets the same adder add and subtract, and gives one zero instead of two. The price of a fixed size is **overflow**: a result too big for the row of bits wraps or corrupts, and the program must care. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Only 0 and 1 — the two states of the computer's switches Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Each place is worth twice the one before it — 1, 2, 4, 8, 16 Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 11 — that is 8 + 2 + 1 Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Because every kind of data the computer holds is, at the bottom, numbers written in binary Do this with a real example of your own and write or say how you know it is right.
