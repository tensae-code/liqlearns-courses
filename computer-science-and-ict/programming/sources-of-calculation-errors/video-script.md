# Video script — Sources of Calculation Errors

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The first source is the **model error**: the model simplifies the world (a frictionless fall, a spherical cow of a problem) — the answer is exact *for the model* and off *for the world*, before any computing. The second is the **input-data error**: measurements carry their absolute and relative errors into the computation as its inheritance — no downstream exactness can wash them out. Both are **irreducible at the desk**: they can be shrunk only by a better model or better measuring, never by more arithmetic.
The third source is the **method error**: numerical methods approximate by design — the bisection's half-interval, the rectangle sum's steps — shrinking as the method refines (more steps, narrower intervals), at the price of more work. The fourth is **rounding error**: the machine's finite mantissa rounds at every operation, and billions of operations accumulate the dust — reducible by wider types and by arranging operations kindly (adding smalls before larges). The chapter's bookkeeping rule: **name every answer's error sources before trusting its digits** — a result whose error budget is unknown is an opinion, not a computation.
