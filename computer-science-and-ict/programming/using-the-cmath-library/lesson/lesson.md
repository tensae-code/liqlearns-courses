# Using the cmath Library

## Do it first

You do not have to build a square-root machine before you may use one. This lesson opens the toolbox the language already built for you.

## Sub lesson 1 — Including and calling

Library functions arrive through a **header**: `#include <cmath>` at the top makes them available. A call looks like any function call — **sqrt(81)** has the value **9** wherever it is written, so it can be stored, printed or built into a bigger expression. The functions work on decimal (double) values and return doubles.

[Picture — including and calling]

## Sub lesson 2 — The working set

The book's working set: **sqrt(x)** square root; **pow(x, y)** x raised to the power y; **abs / fabs** absolute value; **floor** and **ceil** rounding down and up; **round** to nearest; and the trigonometric family (sin, cos, tan — in **radians**). Using the library instead of hand-writing these is the modular habit applied: tested once by the library's makers, reused by everyone.

[Picture — the working set]

## Say it to your companion

Tell your companion, in your own words: The cmath library gives C++ programs ready-made mathematical functions — sqrt for square roots, pow for powers, the rounding and absolute-value functions and more — used by including the header and calling the function with its value in brackets, receiving the result as the call's value. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: #include <cmath> at the top. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Stored, printed, or inside a bigger expression. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: x raised to the power y. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Rounds to the nearest whole value. Do this with a real example of your own and write or say how you know it is right.
