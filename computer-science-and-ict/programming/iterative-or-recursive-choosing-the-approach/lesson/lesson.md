# Iterative or Recursive — Choosing the Approach

## Do it first

Grade 12's complexity chapter asks its practical question. Almost every recursive solution has an iterative twin and vice versa; the craft is not in writing either, but in knowing what each will cost.

## Sub lesson 1 — The two engines — state kept by hand, or by the call stack

An **iterative** solution drives its work with a **loop and explicit variables**: the programmer keeps the state, step by visible step. A **recursive** solution lets a subprogram **call itself** on a smaller part, the state kept implicitly in the **chain of calls** — each call's own variables waiting on the stack until its inner call returns. The recursion reads as the problem's own definition (factorial, tree walks, divide-and-conquer); the iteration shows its machinery. Same answers — different bookkeeping.

In your mind's eye: the two engines — state kept by hand, or by the call stack.

## Sub lesson 2 — Costs and the choice — stack depth against clarity

Recursion pays in **memory**: every pending call holds a stack frame, so a recursion as deep as its input (a million-deep factorial) can **overflow the stack**, while iteration's variables are a fixed few. Recursion often pays also in repeated work when subcalls overlap (the naive Fibonacci computes the same values exponentially often) — unless its structure is a true division with no overlap. The chapter's rule: **recurse where the problem is self-similar and division is clean and depth is modest; iterate where depth is huge, overlap would repeat work, or the loop is simply plain**. Judge by the structure, not by fashion.

In your mind's eye: costs and the choice — stack depth against clarity.

## Say it to your companion

Tell your companion, in your own words: An **iterative** solution drives its work with a **loop and explicit variables**: the programmer keeps the state, step by visible step. A **recursive** solution lets a subprogram **call itself** on a smaller part, the state kept implicitly in the **chain of calls** — each call's own variables waiting on the stack until its inner call returns. The recursion reads as the problem's own definition (factorial, tree walks, divide-and-conquer); the iteration shows its machinery. Same answers — different bookkeeping. Recursion pays in **memory**: every pending call holds a stack frame, so a recursion as deep as its input (a million-deep factorial) can **overflow the stack**, while iteration's variables are a fixed few. Recursion often pays also in repeated work when subcalls overlap (the naive Fibonacci computes the same values exponentially often) — unless its structure is a true division with no overlap. The chapter's rule: **recurse where the problem is self-similar and division is clean and depth is modest; iterate where depth is huge, overlap would repeat work, or the loop is simply plain**. Judge by the structure, not by fashion. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Explicitly — in variables the programmer manages, step by step. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Implicitly — in the chain of calls, each call's variables waiting on the stack. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Where the problem defines itself — factorial, tree walks, divide-and-conquer. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Its machinery — the state and step order in the open. Do this with a real example of your own and write or say how you know it is right.
