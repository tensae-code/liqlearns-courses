# Video script — Numbers in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **integer constant** is a whole number written with digits and an optional sign: 42, −7, +1000. No spaces or commas may interrupt it — 1 000 is two constants, not one. Pascal writes integers in **decimal** only. C++ adds writings by base: a leading **0** means octal (017 = 15), **0x** means hexadecimal (0x1F = 31) — the same value in other clothes, useful where bits matter. A constant's form announces its reading before its value is computed.
A **real constant** carries a fractional part or an exponent: 3.14, 0.5, and the exponent forms 2.5E3, 1.2E−4 — the letter E reads 'times ten to the power'. The decimal separator is a **point**, never a comma, in both languages: 3,14 is a syntax error, not a number. A constant with a point or an E is **real-typed**; without, integer-typed — the writing decides the type before any operation touches it, the fact the type-of-expression lessons will spend.
