# Video script — The Integer Data Type in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **integer** type holds **whole numbers** — counts, ages, scores — with no fractional part. Its values run in a **fixed range** set by the memory the type occupies: the classic Pascal integer runs from **−32768 to 32767**. A value outside the range cannot be held — the type refuses by wrapping or erroring, never by quietly stretching. Declaring is one word: `var n: integer;` — from then on, n may hold only integers, and the compiler guards the promise.
Integers add, subtract and multiply into integers; the surprise is division. In Pascal, `/` on integers gives a **real** result, while **div** gives the **whole quotient** (7 div 2 = 3) and **mod** gives the **remainder** (7 mod 2 = 1). The pair div/mod is the counting toolkit: div counts whole groups, mod finds what is left — coins into whole notes and change, minutes into hours and minutes left over. Choosing integer is choosing this arithmetic: exact, whole, and remainder-aware.
