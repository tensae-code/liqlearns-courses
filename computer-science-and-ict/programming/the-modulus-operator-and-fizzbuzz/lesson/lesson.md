# The Modulus Operator — and FizzBuzz

## Do it first

Division has a forgotten half: the remainder. 17 divided by 5 is 3 — and 2 left over. That leftover, ignored in arithmetic class, turns out to be one of programming's hardest-working tools, with a famous little program as its portrait.

## Sub lesson 1 — Modulus — the remainder operator

The **modulus operator %** gives the **remainder** of an integer division: 17 % 5 is **2**, 10 % 2 is **0**, 7 % 10 is **7**. Its superpower is the zero case: **a % b == 0** tests divisibility exactly — even or odd (n % 2), leap years, every third or fifth thing — questions that are painful with division and one line with modulus. It also wraps circles into lines: hours on a clock face (13 % 12 = 1), days of the week, positions in a ring — anywhere the world is round, modulus is the translator.

In your mind's eye: modulus — the remainder operator.

[Picture 47854 — modulus — the remainder operator]

## Sub lesson 2 — FizzBuzz — the portrait program

**FizzBuzz** counts from 1 upward, replacing: multiples of **3** with **Fizz**, multiples of **5** with **Buzz**, multiples of **both** (of 15) with **FizzBuzz**, and leaving the rest as numbers. Its craft is the order of tests: the both-case must be tested **first** (or as % 3 and % 5 combined), for a multiple of 15 passes the 3-test and would be stolen by Fizz before Buzz is ever asked. Small as it is, FizzBuzz holds modulus, selection order, and loops in one page — which is why interviewers and the HSC book alike keep it: a programmer's whole honesty, in miniature.

In your mind's eye: fizzBuzz — the portrait program.

[Picture 47855 — fizzBuzz — the portrait program]

## Say it to your companion

Tell your companion, in your own words: The **modulus operator %** gives the **remainder** of an integer division: 17 % 5 is **2**, 10 % 2 is **0**, 7 % 10 is **7**. Its superpower is the zero case: **a % b == 0** tests divisibility exactly — even or odd (n % 2), leap years, every third or fifth thing — questions that are painful with division and one line with modulus. It also wraps circles into lines: hours on a clock face (13 % 12 = 1), days of the week, positions in a ring — anywhere the world is round, modulus is the translator. **FizzBuzz** counts from 1 upward, replacing: multiples of **3** with **Fizz**, multiples of **5** with **Buzz**, multiples of **both** (of 15) with **FizzBuzz**, and leaving the rest as numbers. Its craft is the order of tests: the both-case must be tested **first** (or as % 3 and % 5 combined), for a multiple of 15 passes the 3-test and would be stolen by Fizz before Buzz is ever asked. Small as it is, FizzBuzz holds modulus, selection order, and loops in one page — which is why interviewers and the HSC book alike keep it: a programmer's whole honesty, in miniature. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The remainder of an integer division. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: 2. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 7. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Divisibility — exactly. Do this with a real example of your own and write or say how you know it is right.
