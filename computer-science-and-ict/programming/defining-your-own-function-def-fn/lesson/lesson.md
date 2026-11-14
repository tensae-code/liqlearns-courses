# Defining Your Own Function — DEF FN

## Do it first

Your program squares-and-adds-one in nine different places. Change the formula and you must hunt all nine. In this lesson you write the formula once, give it a name — and hunt nothing ever again.

## Sub lesson 1 — DEF FN — teach BASIC a new function

Built-in functions cover the work everybody needs; **DEF FN** covers yours. With `DEF FN` the programmer **defines her own function**: a name beginning with **FN**, a variable in brackets, and the formula the name stands for — `10 DEF FNA(X) = X * X + 1`. From that line on, the program may write `FNA(3)` anywhere a value is wanted, and BASIC works out 10. Sudan's book gives defined functions the final section of its BASIC course: the learner stops only using the language and starts extending it.

[Picture — DEF FN — teach BASIC a new function]

## Sub lesson 2 — Define once, use many times

The worth of a defined function is the worth of every function: the formula is written **once** and **used many times**, with a fresh value each time — `FNA(3)`, `FNA(7)`, `FNA(T)` — and if the formula must change, it changes in the one DEF line, not in every place it was used. A defined function also names an idea: a program that computes a tax, a mean or a conversion reads like its subject when the work hides behind FN names the reader understands.

[Picture — Define once, use many times]

## Say it to your companion

Tell your companion, in your own words: Built-in functions cover the work everybody needs; DEF FN covers yours. The worth of a defined function is the worth of every function: the formula is written once and used many times, with a fresh value each time — `FNA(3)`, `FNA(7)`, `FNA(T)` — and if the formula must change, it changes in the one DEF line, not in every place it was used. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Defines a function of the programmer's own — a name, a variable and the formula it stands for. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: 10. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: In the one DEF line only. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Readability — the program reads like its subject. Do this with a real example of your own and write or say how you know it is right.
