# Recursion and Recursive Functions in Python

## Do it first

A function that calls itself sounds like a dog chasing its tail. With one guard — a case where it stops — it becomes one of programming's most elegant tools. This lesson learns the guard and the chase.

## Sub lesson 1 — What recursion is — the two parts

A **recursive function** solves a problem by calling **itself on a smaller piece** of it. Every working recursion has two parts: the **base case** — the smallest piece, answered directly, where the calls stop — and the **recursive case** — the answer for the whole built from the answer for the smaller piece. Factorial is the book's standing example: n! = n × (n−1)!, with 0! = 1 as the base — the definition and the program have the same shape, which is recursion's beauty and its danger.

In your mind's eye: what recursion is — the two parts.

## Sub lesson 2 — How the calls unwind — and the faults

Each call **waits** on the call-stack for its smaller call's answer; when the base case answers, the stack **unwinds**, each waiting call completing in turn. The faults are the two missing guards: **no base case** (or one never reached) — calls without end, until Python stops the program with a recursion error; and a recursive step that does not **shrink** the problem — the same endlessness by another road. Jordan teaches recursion after the data structures because its finest work is on them: trees and nested lists are smaller-piece-shaped by nature.

In your mind's eye: how the calls unwind — and the faults.

## Say it to your companion

Tell your companion, in your own words: A **recursive function** solves a problem by calling **itself on a smaller piece** of it. Every working recursion has two parts: the **base case** — the smallest piece, answered directly, where the calls stop — and the **recursive case** — the answer for the whole built from the answer for the smaller piece. Factorial is the book's standing example: n! = n × (n−1)!, with 0! = 1 as the base — the definition and the program have the same shape, which is recursion's beauty and its danger. Each call **waits** on the call-stack for its smaller call's answer; when the base case answers, the stack **unwinds**, each waiting call completing in turn. The faults are the two missing guards: **no base case** (or one never reached) — calls without end, until Python stops the program with a recursion error; and a recursive step that does not **shrink** the problem — the same endlessness by another road. Jordan teaches recursion after the data structures because its finest work is on them: trees and nested lists are smaller-piece-shaped by nature. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Itself, on a smaller piece of the problem. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The base case and the recursive case. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The smallest piece, answered directly, where calls stop. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: n! = n × (n−1)!; base 0! = 1. Do this with a real example of your own and write or say how you know it is right.
