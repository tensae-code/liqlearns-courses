# Video script — The Sifting Method — Generating and Testing Candidates

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **sifting method** solves a problem in two exhaustive halves: **generate** the complete list of **candidates** (every combination, arrangement or value the problem allows), and **test** each candidate against **all** the problem's conditions, keeping those that pass every test. Its guarantee is total: if a solution exists among the candidates, sifting **finds it** — nothing clever was skipped, because nothing was skipped at all. Its textbook examples are the honest searches: numbers with given digits and properties, arrangements meeting constraints, triples satisfying an equation.
Sifting's price is the size of its candidate space: permutations and combinations grow **factorially/exponentially**, so the method that is instant for hundreds drowns at millions. The craft inside sifting is **pruning**: generate candidates **in parts** and test each partial candidate early, abandoning a whole family the moment a part already fails — the seed of backtracking. And the method's second office is as a **measure**: the clever method (greedy, dynamic) must beat sifting's time while matching its answers on small cases — sifting is the examiner that never lies.
