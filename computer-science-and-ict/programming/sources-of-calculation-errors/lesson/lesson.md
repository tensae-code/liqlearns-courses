# Sources of Calculation Errors

## Do it first

Before blaming a wrong answer, Grade 12's modelling chapter holds an inquest. Every numerical answer's error has a birthplace — and there are exactly four places it can be born.

## Sub lesson 1 — Born before the machine — model and data errors

The first source is the **model error**: the model simplifies the world (a frictionless fall, a spherical cow of a problem) — the answer is exact *for the model* and off *for the world*, before any computing. The second is the **input-data error**: measurements carry their absolute and relative errors into the computation as its inheritance — no downstream exactness can wash them out. Both are **irreducible at the desk**: they can be shrunk only by a better model or better measuring, never by more arithmetic.

In your mind's eye: born before the machine — model and data errors.

## Sub lesson 2 — Born in the work — method and rounding errors

The third source is the **method error**: numerical methods approximate by design — the bisection's half-interval, the rectangle sum's steps — shrinking as the method refines (more steps, narrower intervals), at the price of more work. The fourth is **rounding error**: the machine's finite mantissa rounds at every operation, and billions of operations accumulate the dust — reducible by wider types and by arranging operations kindly (adding smalls before larges). The chapter's bookkeeping rule: **name every answer's error sources before trusting its digits** — a result whose error budget is unknown is an opinion, not a computation.

In your mind's eye: born in the work — method and rounding errors.

## Say it to your companion

Tell your companion, in your own words: The first source is the **model error**: the model simplifies the world (a frictionless fall, a spherical cow of a problem) — the answer is exact *for the model* and off *for the world*, before any computing. The second is the **input-data error**: measurements carry their absolute and relative errors into the computation as its inheritance — no downstream exactness can wash them out. Both are **irreducible at the desk**: they can be shrunk only by a better model or better measuring, never by more arithmetic. The third source is the **method error**: numerical methods approximate by design — the bisection's half-interval, the rectangle sum's steps — shrinking as the method refines (more steps, narrower intervals), at the price of more work. The fourth is **rounding error**: the machine's finite mantissa rounds at every operation, and billions of operations accumulate the dust — reducible by wider types and by arranging operations kindly (adding smalls before larges). The chapter's bookkeeping rule: **name every answer's error sources before trusting its digits** — a result whose error budget is unknown is an opinion, not a computation. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The gap from the model's simplification — exact for the model, off for the world. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The measurements' own errors, inherited by the whole computation. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — it is irreducible at the desk. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Only by a better model or better measuring. Do this with a real example of your own and write or say how you know it is right.
