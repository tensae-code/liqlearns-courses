# LOGO procedures — giving a name to a set of commands

## Do it first

Write out every command needed to draw one square: forward, turn, forward, turn… Now imagine drawing five squares. How many commands will you type? What if one word — SQUARE — could carry the whole list? That word is this lesson's subject.

## A name for a set of commands

A **procedure** is a **set of instructions given a descriptive one-word name**. Built-in commands like FORWARD are **primitive procedures** — words Logo already owns. When you define a procedure, you **add new words to the language**: your own words, doing your own jobs. The book's example: a procedure named **SQUARE** — or the same drawing compressed as **REPEAT 4 [FORWARD 100 RIGHT 90]** — replaces retyping a long sequence every time. One rule governs all of it: **a procedure must be defined before use** — otherwise LOGO answers that the procedure **is not in its vocabulary yet**. Teach the word first; then use it. The guide adds why this is worth doing, in its own keyed phrase: defining a procedure **spares the typing of the whole instruction set each time**.

[Picture 10530 — a procedure has a name]

[GIF 10561 — SQUARE drawing itself]

## Procedures live in a workspace — Grade 8, taken further

Typing commands one by one makes the turtle move at once — but it does not remember how a shape was made. A procedure makes the turtle **remember** a set of commands. Procedures **live in memory as part of a LOGO workspace**, which can be **saved and loaded like other documents** — teach SQUARE today, load the workspace tomorrow, and SQUARE is still yours. Every procedure is made with the word **TO plus the name** — **TO SQUARE**, **TO HOUSE** — and a name has **no spaces**. Teach the turtle that SQUARE means **REPEAT 4 [FD 50 RT 90]**, and afterwards the word alone makes the shape.

[Picture 12313 — one word holds the whole list]

## Say it to your companion

Tell your companion what a procedure is, what a primitive is, and the rule that must come before any procedure can run.

## Do It Yourself

1. Write a procedure name and its instruction list for drawing a simple house shape.
2. Explain LOGO's 'not in its vocabulary' answer to a friend.
3. Say what REPEAT 4 [FORWARD 100 RIGHT 90] draws, and how you know.
