# Video script — Binary Arithmetic

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Binary columns are small. Two 1s already overflow: write 0, carry 1.

That one rule is all of binary addition. Column by column, carries hopping left.

A minus sign cannot be drawn in bits. So negative numbers wear a code: two's complement.

Invert every bit. Add 1. That is the negative. In four bits, minus 5 is 1011.

Now subtraction vanishes: A minus B is A plus the complement of B. Throw the extra carry away.

Multiplication: copy the number for each 1 in the multiplier, shift, and add.

Division: compare, subtract, shift — the quotient grows one bit at a time.
