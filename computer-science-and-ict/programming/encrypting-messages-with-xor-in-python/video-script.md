# Video script — Encrypting Messages with XOR in Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**XOR** compares two bits and answers 1 when they **differ**, 0 when they are the **same**: 0⊕0=0, 0⊕1=1, 1⊕0=1, 1⊕1=0. Applied to a whole character's bits against a key's bits, it scrambles. The accident that makes the lesson: **XOR with the same key twice returns the original** — because each bit is flipped, then flipped back. So one operation is both encryptor and decryptor: ciphertext = plaintext ⊕ key, and plaintext = ciphertext ⊕ key. No separate decryption method exists to invent, carry or lose — the same line of code, run on the ciphertext with the same key, gives the message back.
The book's program assembles the term: each **character** of the message is taken in a **loop**, turned into its **code number**, XORed with the **key** number, and the results gathered — as numbers, or turned back into characters — into the ciphertext. Decryption is the identical program fed the ciphertext. The teaching then turns critic, as Egypt's course keeps doing: this cipher is a perfect **teaching** cipher and a weak **real** one — a single short key repeats its pattern across a long message, and patterns are what codebreakers eat. The pupil who can say both things — how it works, and why the real world needs more — has learned the lesson the book placed last on purpose.
