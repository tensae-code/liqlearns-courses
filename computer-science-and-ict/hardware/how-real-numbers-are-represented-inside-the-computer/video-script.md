# Video script — How Real Numbers Are Represented Inside the Computer

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A real is stored as **three fields in a fixed row of bits**: the **sign** (0 for +, 1 for −), the **exponent** (a shifted power of two), and the **mantissa** (the number's significant digits in binary, normalised so its first digit is 1). The value is **sign × mantissa × 2^exponent** — the binary twin of the written form 1.25×10³. Doubling a field's share widens what it governs: more exponent bits, a **wider range**; more mantissa bits, **finer precision**. The fixed total is the budget both are paid from.
The representation has **two edges**. Beyond the exponent's reach lie numbers **too large (overflow)** and **too small (underflow toward zero)** — the type's range. Between two neighbouring stored mantissas lie all the true values that must share them — the type's **precision limit**, the reason 0.1 is stored as a close stranger and errors accumulate in long computations (Grade 12's error lessons are seated here). The compromise is chosen, not suffered: science needs range and the school needs honesty about precision — the floating point is both, in one row of bits.
