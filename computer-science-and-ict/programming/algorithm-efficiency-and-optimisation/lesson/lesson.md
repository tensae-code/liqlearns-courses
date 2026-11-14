# Algorithm Efficiency and Optimisation

## Do it first

Both of your searches find the answer. One takes a second, the other takes a year. This lesson is about measuring that difference before it happens.

## Sub lesson 1 — Counting operations, not seconds

A stopwatch measures one machine on one day; **efficiency** is measured by counting the algorithm's **operations** as the input size **n** grows. An algorithm doing about n operations doubles its work when n doubles; one doing about **n²** operations quadruples it — fine for ten items, hopeless for a million. The growth shape, not the constant, decides whether an algorithm survives big data.

[Picture — counting operations, not seconds]

## Sub lesson 2 — Where optimisation finds its wins

**Optimisation** hunts waste: a value **recalculated** inside a loop that could be computed **once before it**; a second pass over data the first pass could have finished; searching an **unsorted** list item by item when sorted data allows halving the search space each step. The rule is to optimise the **growth** first and the details second — and to keep the program correct and readable while making it faster.

[Picture — where optimisation finds its wins]

## Say it to your companion

Tell your companion, in your own words: Two algorithms can solve the same problem at wildly different speeds: efficiency is judged by how the work grows as the input grows — counting operations, not seconds — and optimisation means finding the avoidable work (repeated calculations, needless passes, searching a sorted list the slow way) and removing it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: How the work grows as the input grows. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: It quadruples. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Recalculating inside a loop and needless extra passes (any two from the lesson). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Halving the search space each step. Do this with a real example of your own and write or say how you know it is right.
