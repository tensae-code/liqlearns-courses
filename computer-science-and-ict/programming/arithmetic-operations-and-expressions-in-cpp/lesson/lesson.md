# Arithmetic Operations and Expressions in C++

## Do it first

A calculator follows rules you never see. In C++ you write the calculation yourself — so you must know exactly what the machine will do with it.

## Sub lesson 1 — The operators — and the remainder

C++ computes with **+** (add), **−** (subtract), **\*** (multiply), **/** (divide) and **%** — **modulo**, the **remainder** after division: 17 % 5 = **2**. Watch division: between **integers**, / keeps only the whole part — 17 / 5 = **3**, the fraction is dropped. Between decimal numbers it divides fully. Mixing the two kinds without care is a classic beginner surprise.

[Picture — the operators — and the remainder]

## Sub lesson 2 — Order — precedence and brackets

Expressions are evaluated by **precedence**: brackets first, then **\* / %**, then **+ −**; equal ranks go left to right. So 2 + 3 * 4 = **14**, not 20 — and (2 + 3) * 4 = **20** because the brackets reorder it. An expression's single final **value** is what an assignment stores or an output prints, so reading an expression means working out that one value step by step.

[Picture — order — precedence and brackets]

## Say it to your companion

Tell your companion, in your own words: In C++ an arithmetic expression is built from values, variables and the operators + − * / and % (remainder); division between integers drops the fraction, multiplication and division are done before addition and subtraction, and brackets change the order — the value of the whole expression is what gets stored or printed. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The remainder after division. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: 3 — the fraction is dropped. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Brackets. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: 14. Do this with a real example of your own and write or say how you know it is right.
