# Recursion in ΓΛΩΣΣΑ

## Do it first

The general recursion lesson taught the idea: a procedure that calls itself. Greece's exam course makes you write it — in ΓΛΩΣΣΑ, with real parameters, on paper, in the exam. This lesson is that writing.

## Sub lesson 1 — A subprogram that calls itself

In ΓΛΩΣΣΑ a **procedure or function may call itself** — that is recursion in the language. Each call is a **fresh run** of the subprogram with its own parameters and local names, stacked on the unfinished calls beneath it. The book's condition is absolute: somewhere in the subprogram must stand a **stopping case** — a call that answers without calling again — and every self-call must move **closer** to it, or the calls never end and the program fails.

In your mind's eye: a subprogram that calls itself.

[Picture 47567 — a subprogram that calls itself]

## Sub lesson 2 — Tracing the chain — factorial in ΓΛΩΣΣΑ

The book traces recursion the exam way: **on paper, call by call**. The factorial function calls itself with n−1 until the stopping case n=1 (or 0) answers 1; then the stacked calls **unwind**, each multiplying its own n by the answer handed back, until the first call gives the final product. Writing that trace — calls going down, answers coming up — is the skill Ch.10 examines, and the same trace serves the chapter's other recursions (greatest common divisor, Fibonacci) taught in the algorithms chapters.

In your mind's eye: tracing the chain — factorial in ΓΛΩΣΣΑ.

[Picture 47568 — tracing the chain — factorial in ΓΛΩΣΣΑ]

## Say it to your companion

Tell your companion, in your own words: In ΓΛΩΣΣΑ a **procedure or function may call itself** — that is recursion in the language. Each call is a **fresh run** of the subprogram with its own parameters and local names, stacked on the unfinished calls beneath it. The book's condition is absolute: somewhere in the subprogram must stand a **stopping case** — a call that answers without calling again — and every self-call must move **closer** to it, or the calls never end and the program fails. The book traces recursion the exam way: **on paper, call by call**. The factorial function calls itself with n−1 until the stopping case n=1 (or 0) answers 1; then the stacked calls **unwind**, each multiplying its own n by the answer handed back, until the first call gives the final product. Writing that trace — calls going down, answers coming up — is the skill Ch.10 examines, and the same trace serves the chapter's other recursions (greatest common divisor, Fibonacci) taught in the algorithms chapters. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A procedure or function that calls itself. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A fresh run with its own parameters and local names, stacked on the unfinished calls. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A stopping case — a call that answers without calling again. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Move closer to the stopping case. Do this with a real example of your own and write or say how you know it is right.
