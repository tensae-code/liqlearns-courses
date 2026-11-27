# The Integer Data Type in Pascal

## Do it first

A variable is a box, and its type is the box's shape. Grade 7's Pascal course takes the types one by one; first is the type of counting — integer, the whole numbers.

## Sub lesson 1 — Integer — whole numbers in a fixed range

The **integer** type holds **whole numbers** — counts, ages, scores — with no fractional part. Its values run in a **fixed range** set by the memory the type occupies: the classic Pascal integer runs from **−32768 to 32767**. A value outside the range cannot be held — the type refuses by wrapping or erroring, never by quietly stretching. Declaring is one word: `var n: integer;` — from then on, n may hold only integers, and the compiler guards the promise.

In your mind's eye: integer — whole numbers in a fixed range.

[Picture 47848 — integer — whole numbers in a fixed range]

## Sub lesson 2 — Operations on integers — and div and mod

Integers add, subtract and multiply into integers; the surprise is division. In Pascal, `/` on integers gives a **real** result, while **div** gives the **whole quotient** (7 div 2 = 3) and **mod** gives the **remainder** (7 mod 2 = 1). The pair div/mod is the counting toolkit: div counts whole groups, mod finds what is left — coins into whole notes and change, minutes into hours and minutes left over. Choosing integer is choosing this arithmetic: exact, whole, and remainder-aware.

In your mind's eye: operations on integers — and div and mod.

[Picture 47849 — operations on integers — and div and mod]

## Say it to your companion

Tell your companion, in your own words: The **integer** type holds **whole numbers** — counts, ages, scores — with no fractional part. Its values run in a **fixed range** set by the memory the type occupies: the classic Pascal integer runs from **−32768 to 32767**. A value outside the range cannot be held — the type refuses by wrapping or erroring, never by quietly stretching. Declaring is one word: `var n: integer;` — from then on, n may hold only integers, and the compiler guards the promise. Integers add, subtract and multiply into integers; the surprise is division. In Pascal, `/` on integers gives a **real** result, while **div** gives the **whole quotient** (7 div 2 = 3) and **mod** gives the **remainder** (7 mod 2 = 1). The pair div/mod is the counting toolkit: div counts whole groups, mod finds what is left — coins into whole notes and change, minutes into hours and minutes left over. Choosing integer is choosing this arithmetic: exact, whole, and remainder-aware. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Whole numbers — counts, ages, scores — with no fractional part. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: −32768 to 32767. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The memory the type occupies. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: var n: integer;. Do this with a real example of your own and write or say how you know it is right.
