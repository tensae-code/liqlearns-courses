# Video script — Arithmetic Operations and Expressions in C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

C++ computes with **+** (add), **−** (subtract), **\*** (multiply), **/** (divide) and **%** — **modulo**, the **remainder** after division: 17 % 5 = **2**. Watch division: between **integers**, / keeps only the whole part — 17 / 5 = **3**, the fraction is dropped. Between decimal numbers it divides fully. Mixing the two kinds without care is a classic beginner surprise.
Expressions are evaluated by **precedence**: brackets first, then **\* / %**, then **+ −**; equal ranks go left to right. So 2 + 3 * 4 = **14**, not 20 — and (2 + 3) * 4 = **20** because the brackets reorder it. An expression's single final **value** is what an assignment stores or an output prints, so reading an expression means working out that one value step by step.
