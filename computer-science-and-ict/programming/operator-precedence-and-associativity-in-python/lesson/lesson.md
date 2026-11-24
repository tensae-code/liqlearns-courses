# Operator Precedence and Associativity in Python

## Do it first

Python reads 2 + 3 * 4 as 14, and 10 - 4 - 3 as 3 — never 9. Two rules make those answers inevitable. This lesson learns both.

## Sub lesson 1 — Precedence — who goes first

**Precedence** ranks the operators: brackets first, then powers, then multiplication and division, then addition and subtraction; comparisons and logic sit lower in their own ranks. An expression is worked out by precedence, not by reading order — `2 + 3 * 4` is 14 because the multiplication outranks the addition. Jordan's Python lesson teaches the ladder with the standing advice attached: when the order matters to a reader, **brackets** say it — precedence is for reading code, brackets are for writing it kindly.

In your mind's eye: precedence — who goes first.

## Sub lesson 2 — Associativity — ties broken by direction

Operators of **equal precedence** are settled by **associativity**: most work **left to right** (`10 - 4 - 3` = (10−4)−3 = 3), but the power operator works **right to left** (`2 ** 3 ** 2` = 2^(3^2) = 512, not 64). Assignment, too, associates right to left. The pair of rules together — precedence for rank, associativity for ties — decide every expression Python will ever meet, which is why the book drills them before the conditionals that spend them.

In your mind's eye: associativity — ties broken by direction.

## Say it to your companion

Tell your companion, in your own words: **Precedence** ranks the operators: brackets first, then powers, then multiplication and division, then addition and subtraction; comparisons and logic sit lower in their own ranks. An expression is worked out by precedence, not by reading order — `2 + 3 * 4` is 14 because the multiplication outranks the addition. Jordan's Python lesson teaches the ladder with the standing advice attached: when the order matters to a reader, **brackets** say it — precedence is for reading code, brackets are for writing it kindly. Operators of **equal precedence** are settled by **associativity**: most work **left to right** (`10 - 4 - 3` = (10−4)−3 = 3), but the power operator works **right to left** (`2 ** 3 ** 2` = 2^(3^2) = 512, not 64). Assignment, too, associates right to left. The pair of rules together — precedence for rank, associativity for ties — decide every expression Python will ever meet, which is why the book drills them before the conditionals that spend them. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The operators — who is worked out first. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Brackets, then powers, then × and ÷, then + and −. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Multiplication outranks addition. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — by precedence. Do this with a real example of your own and write or say how you know it is right.
