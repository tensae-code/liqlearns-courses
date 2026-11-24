# How Real Numbers Are Represented Inside the Computer

## Do it first

Integers got fixed patterns; reals cannot have them — between 0 and 1 alone there are infinitely many. Grade 11's representation chapter ends with the computer's ingenious compromise: the floating point.

## Sub lesson 1 — Sign, exponent, mantissa — the three fields

A real is stored as **three fields in a fixed row of bits**: the **sign** (0 for +, 1 for −), the **exponent** (a shifted power of two), and the **mantissa** (the number's significant digits in binary, normalised so its first digit is 1). The value is **sign × mantissa × 2^exponent** — the binary twin of the written form 1.25×10³. Doubling a field's share widens what it governs: more exponent bits, a **wider range**; more mantissa bits, **finer precision**. The fixed total is the budget both are paid from.

In your mind's eye: sign, exponent, mantissa — the three fields.

## Sub lesson 2 — Range and precision — the two edges of the compromise

The representation has **two edges**. Beyond the exponent's reach lie numbers **too large (overflow)** and **too small (underflow toward zero)** — the type's range. Between two neighbouring stored mantissas lie all the true values that must share them — the type's **precision limit**, the reason 0.1 is stored as a close stranger and errors accumulate in long computations (Grade 12's error lessons are seated here). The compromise is chosen, not suffered: science needs range and the school needs honesty about precision — the floating point is both, in one row of bits.

In your mind's eye: range and precision — the two edges of the compromise.

## Say it to your companion

Tell your companion, in your own words: A real is stored as **three fields in a fixed row of bits**: the **sign** (0 for +, 1 for −), the **exponent** (a shifted power of two), and the **mantissa** (the number's significant digits in binary, normalised so its first digit is 1). The value is **sign × mantissa × 2^exponent** — the binary twin of the written form 1.25×10³. Doubling a field's share widens what it governs: more exponent bits, a **wider range**; more mantissa bits, **finer precision**. The fixed total is the budget both are paid from. The representation has **two edges**. Beyond the exponent's reach lie numbers **too large (overflow)** and **too small (underflow toward zero)** — the type's range. Between two neighbouring stored mantissas lie all the true values that must share them — the type's **precision limit**, the reason 0.1 is stored as a close stranger and errors accumulate in long computations (Grade 12's error lessons are seated here). The compromise is chosen, not suffered: science needs range and the school needs honesty about precision — the floating point is both, in one row of bits. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Sign, exponent and mantissa. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: sign × mantissa × 2^exponent. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The mantissa's first digit is 1. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Wider range; finer precision. Do this with a real example of your own and write or say how you know it is right.
