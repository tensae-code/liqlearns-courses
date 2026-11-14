# Video script — Binary — and How Integers Are Stored

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **binary system** counts with two digits only, **0 and 1**, because a computer's memory is built of two-state switches. Place value still rules: each place is worth **twice** the place before it — 1, 2, 4, 8, 16 — so the binary number 1011 is 8 + 2 + 1 = **11** in decimal. Vietnam's Grade 10 data strand begins here, before sound and image data, because every kind of data the computer holds is, at the bottom, numbers written this way.
An integer is stored in a **fixed number of bits** — 8, 16, 32 or 64 — and the fixing decides the **range**: 8 bits hold 256 different values. Positive integers are stored as their binary value, padded with zeros. **Negative** integers need a scheme: the book's way is **two's complement** — invert the bits of the positive number and add 1 — which lets the same adder add and subtract, and gives one zero instead of two. The price of a fixed size is **overflow**: a result too big for the row of bits wraps or corrupts, and the program must care.
