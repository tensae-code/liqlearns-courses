# Using a Standard Library

## Do it first

No programmer writes their own square root twice. Every serious language ships with a standard library — Malaysia's scripting chapter teaches its use as a skill. In this lesson you learn what the library holds, and how a program calls on it.

## Sub lesson 1 — The library — the language's ready-made shelves

A **standard library** is the collection of **ready-made** functions and objects that **ships with the language itself** — no installing, no importing from strangers. In JavaScript the shelves this chapter uses include **Math** (Math.sqrt, Math.floor, Math.random, PI as Math.PI) and **Date** (the current date and time, and their parts). A library member is known by its **documentation**: what it takes, what it returns, what it promises — the programmer's job is to know the shelves and read the labels, not to rebuild the goods.

[Picture — The library — the language's ready-made shelves]

## Sub lesson 2 — Calling the library — trust, but verify the label

Using the library is a **call**: name the member, hand it its values, take its return — let root = Math.sqrt(81); gives 9 without one line of root-finding written. Malaysia's disciplines of use are two: call the library **instead of hand-writing** what it already does correctly (a hand-written random or date routine is a fault waiting), and **check the label** before calling — Math.floor(3.9) gives 3, not 4, because floor promises the whole number **below**; most library 'faults' are labels misread. The standard library is the language's gift of other programmers' tested work; using it well is a form of reading.

[Picture — Calling the library — trust, but verify the label]

## Say it to your companion

Tell your companion, in your own words: A **standard library** is the collection of **ready-made** functions and objects that **ships with the language itself** — no installing, no importing from strangers. In JavaScript the shelves this chapter uses include **Math** (Math.sqrt, Math.floor, Math.random, PI as Math.PI) and **Date** (the current date and time, and their parts). A library member is known by its **documentation**: what it takes, what it returns, what it promises — the programmer's job is to know the shelves and read the labels, not to rebuild the goods. Using the library is a **call**: name the member, hand it its values, take its return — let root = Math.sqrt(81); gives 9 without one line of root-finding written. Malaysia's disciplines of use are two: call the library **instead of hand-writing** what it already does correctly (a hand-written random or date routine is a fault waiting), and **check the label** before calling — Math.floor(3.9) gives 3, not 4, because floor promises the whole number **below**; most library 'faults' are labels misread. The standard library is the language's gift of other programmers' tested work; using it well is a form of reading. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The ready-made collection of functions and objects that ships with the language itself. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: No — it ships with the language. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Math and Date. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: 9 — and no root-finding code at all. Do this with a real example of your own and write or say how you know it is right.
