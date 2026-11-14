# Video script — Signed Numbers — Using a Sign Bit

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In **sign-and-magnitude** writing, the **first bit is the sign**: **0 means positive, 1 means negative**, and the remaining bits hold the number's size (its magnitude) exactly as before. In 8 bits, 00000101 is +5 and 10000101 is −5 — one bit spent, the whole positive-and-negative world in reach. The programmer reading a register reads the sign first, then the size, like reading '−' before a decimal number — the scheme is decimal habit, mechanised.
The scheme's flaw shows at zero: **00000000 is +0 and 10000000 is −0** — two writings of nothing, wasting a pattern and confusing every comparison (are they equal?). Worse, arithmetic breaks its school rules: adding a positive and a negative with the ordinary adder gives wrong answers, because the sign bit is being added as if it were size. The machine needs a writing where one adder serves everything — and that need, named here, is answered by two's complement in the next placement's lesson.
