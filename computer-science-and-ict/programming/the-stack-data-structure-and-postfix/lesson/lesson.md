# The Stack Data Structure — and Postfix

## Do it first

The stack data structure — a pile where the last value in is the first out, with push and pop; evaluating postfix expressions with a stack; and choosing stack or queue

## Sub lesson 1 — The stack — last in, first out

A **stack** (tumpukan) is a data structure that keeps its values in a pile with one open end — the **top**. Two operations work it: **push** puts a value on top, **pop** takes the top value off. Its law is **LIFO** — the last value in is the first value out — like a pile of plates, or the undo history of an editor. Indonesia meets the stack twice: in Grade 8's computational thinking, and in Grade 10, where it is chosen (against the queue) as the structure a problem needs. A stack is not a list with manners; its restriction — only the top may be touched — is exactly its power.

In your mind's eye: the stack — last in, first out.

[Picture 47887 — the stack — last in, first out]

## Sub lesson 2 — Postfix — the stack computes

Grade 8's jewel is **postfix** evaluation (the book's 'cara Koko' — Koko's way): in postfix notation the operator follows its values — `3 4 +` instead of `3 + 4` — and a stack evaluates it mechanically: read left to right, **push numbers**, and when an **operator** arrives, **pop two values, apply it, push the result**. At the end, the stack holds the single answer. No brackets, no precedence rules — the stack's order does the whole grammar. The same chapter's Grade 10 twin completes the picture: the **queue** beside the stack, first-in-first-out, and simulations that teach choosing between them by the problem's shape.

In your mind's eye: postfix — the stack computes.

[Picture 47888 — postfix — the stack computes]

## Say it to your companion

Tell your companion, in your own words: A **stack** (tumpukan) is a data structure that keeps its values in a pile with one open end — the **top**. Two operations work it: **push** puts a value on top, **pop** takes the top value off. Its law is **LIFO** — the last value in is the first value out — like a pile of plates, or the undo history of an editor. Indonesia meets the stack twice: in Grade 8's computational thinking, and in Grade 10, where it is chosen (against the queue) as the structure a problem needs. A stack is not a list with manners; its restriction — only the top may be touched — is exactly its power. Grade 8's jewel is **postfix** evaluation (the book's 'cara Koko' — Koko's way): in postfix notation the operator follows its values — `3 4 +` instead of `3 + 4` — and a stack evaluates it mechanically: read left to right, **push numbers**, and when an **operator** arrives, **pop two values, apply it, push the result**. At the end, the stack holds the single answer. No brackets, no precedence rules — the stack's order does the whole grammar. The same chapter's Grade 10 twin completes the picture: the **queue** beside the stack, first-in-first-out, and simulations that teach choosing between them by the problem's shape. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A data structure keeping values in a pile with one open end — the top Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Push puts a value on top; pop takes the top value off Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Last in, first out — the stack's law Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A pile of plates, and an editor's undo history Do this with a real example of your own and write or say how you know it is right.
