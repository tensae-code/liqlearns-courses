# Encrypting Messages with XOR in Python

## Do it first

The final lesson of Egypt's Grade 8 Term 2 is a program: encryption using the XOR operation, in Python. It is a small masterpiece of placement — the term's Python (conditions, loops, functions, collections) and its encryption idea meet in one short program whose secret is a beautiful arithmetical accident.

## Sub lesson 1 — XOR — the operation that undoes itself

**XOR** compares two bits and answers 1 when they **differ**, 0 when they are the **same**: 0⊕0=0, 0⊕1=1, 1⊕0=1, 1⊕1=0. Applied to a whole character's bits against a key's bits, it scrambles. The accident that makes the lesson: **XOR with the same key twice returns the original** — because each bit is flipped, then flipped back. So one operation is both encryptor and decryptor: ciphertext = plaintext ⊕ key, and plaintext = ciphertext ⊕ key. No separate decryption method exists to invent, carry or lose — the same line of code, run on the ciphertext with the same key, gives the message back.

[Picture — XOR — the operation that undoes itself]

## Sub lesson 2 — The program — characters, codes, a key, a loop

The book's program assembles the term: each **character** of the message is taken in a **loop**, turned into its **code number**, XORed with the **key** number, and the results gathered — as numbers, or turned back into characters — into the ciphertext. Decryption is the identical program fed the ciphertext. The teaching then turns critic, as Egypt's course keeps doing: this cipher is a perfect **teaching** cipher and a weak **real** one — a single short key repeats its pattern across a long message, and patterns are what codebreakers eat. The pupil who can say both things — how it works, and why the real world needs more — has learned the lesson the book placed last on purpose.

[Picture — The program — characters, codes, a key, a loop]

## Say it to your companion

Tell your companion, in your own words: **XOR** compares two bits and answers 1 when they **differ**, 0 when they are the **same**: 0⊕0=0, 0⊕1=1, 1⊕0=1, 1⊕1=0. Applied to a whole character's bits against a key's bits, it scrambles. The accident that makes the lesson: **XOR with the same key twice returns the original** — because each bit is flipped, then flipped back. So one operation is both encryptor and decryptor: ciphertext = plaintext ⊕ key, and plaintext = ciphertext ⊕ key. No separate decryption method exists to invent, carry or lose — the same line of code, run on the ciphertext with the same key, gives the message back. The book's program assembles the term: each **character** of the message is taken in a **loop**, turned into its **code number**, XORed with the **key** number, and the results gathered — as numbers, or turned back into characters — into the ciphertext. Decryption is the identical program fed the ciphertext. The teaching then turns critic, as Egypt's course keeps doing: this cipher is a perfect **teaching** cipher and a weak **real** one — a single short key repeats its pattern across a long message, and patterns are what codebreakers eat. The pupil who can say both things — how it works, and why the real world needs more — has learned the lesson the book placed last on purpose. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: 1 when the two bits differ, 0 when they are the same. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: 0 — the bits are the same. Do this with a real example of your own and write or say how you know it is right.
6. Show it, don't just say it: Takes it in a loop, turns it into its code number, XORs it with the key. Do this with a real example of your own and write or say how you know it is right.
7. Show it, don't just say it: The XORed results — as numbers, or turned back into characters. Do this with a real example of your own and write or say how you know it is right.
