# The Sifting Method — Generating and Testing Candidates

## Do it first

Grade 12's technique chapter gives brute force its formal name and its dignity. Sifting is what you do when you cannot be clever: make every candidate, test every candidate, keep those that pass.

## Sub lesson 1 — Generate and test — the method's two halves

The **sifting method** solves a problem in two exhaustive halves: **generate** the complete list of **candidates** (every combination, arrangement or value the problem allows), and **test** each candidate against **all** the problem's conditions, keeping those that pass every test. Its guarantee is total: if a solution exists among the candidates, sifting **finds it** — nothing clever was skipped, because nothing was skipped at all. Its textbook examples are the honest searches: numbers with given digits and properties, arrangements meeting constraints, triples satisfying an equation.

[Picture — Generate and test — the method's two halves]

## Sub lesson 2 — The cost — and making sifting less blind

Sifting's price is the size of its candidate space: permutations and combinations grow **factorially/exponentially**, so the method that is instant for hundreds drowns at millions. The craft inside sifting is **pruning**: generate candidates **in parts** and test each partial candidate early, abandoning a whole family the moment a part already fails — the seed of backtracking. And the method's second office is as a **measure**: the clever method (greedy, dynamic) must beat sifting's time while matching its answers on small cases — sifting is the examiner that never lies.

[Picture — The cost — and making sifting less blind]

## Say it to your companion

Tell your companion, in your own words: The **sifting method** solves a problem in two exhaustive halves: **generate** the complete list of **candidates** (every combination, arrangement or value the problem allows), and **test** each candidate against **all** the problem's conditions, keeping those that pass every test. Its guarantee is total: if a solution exists among the candidates, sifting **finds it** — nothing clever was skipped, because nothing was skipped at all. Its textbook examples are the honest searches: numbers with given digits and properties, arrangements meeting constraints, triples satisfying an equation. Sifting's price is the size of its candidate space: permutations and combinations grow **factorially/exponentially**, so the method that is instant for hundreds drowns at millions. The craft inside sifting is **pruning**: generate candidates **in parts** and test each partial candidate early, abandoning a whole family the moment a part already fails — the seed of backtracking. And the method's second office is as a **measure**: the clever method (greedy, dynamic) must beat sifting's time while matching its answers on small cases — sifting is the examiner that never lies. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Generate every candidate; test each against all the conditions. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Total — if a solution exists among the candidates, sifting finds it. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Because nothing was skipped — the generation is exhaustive. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Numbers with given digits and properties (also: arrangements under constraints, triples satisfying an equation). Do this with a real example of your own and write or say how you know it is right.
