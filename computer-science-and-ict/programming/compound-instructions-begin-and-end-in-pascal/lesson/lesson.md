# Compound Instructions — begin and end in Pascal

## Do it first

Instructions that govern — if, while, for — govern exactly one instruction. Real work is rarely one step. Grade 8 and Grade 10 teach the wrapper that resolves the tension: begin…end.

## Sub lesson 1 — begin…end — many instructions, one place

A **compound instruction** is a sequence of instructions enclosed by **begin** and **end**, treated by the grammar as **one instruction**. The instructions inside are separated by semicolons — none is needed after the last, before end (a semicolon there only adds an empty instruction). C++ wraps the same idea in **braces { }**. Wherever the grammar asks for one instruction — an if's branch, a loop's body, a case's label — a compound instruction can stand, carrying as many steps as the work needs.

In your mind's eye: begin…end — many instructions, one place.

[Picture 46906 — begin…end — many instructions, one place]

## Sub lesson 2 — Why the wrapper matters — the governed block

Without the wrapper, governance leaks: in `if x > 0 then a := 1; b := 2;` only a := 1 is conditional — b := 2 runs always, because the if governs one instruction. With begin…end around both, the pair stands or falls together. The lesson's reading habit follows: to know what any governing instruction commands, find its **one instruction** — a single step, or the whole begin…end block — and draw its border before judging the program. Most beginner logic errors are border errors.

In your mind's eye: why the wrapper matters — the governed block.

[Picture 46907 — why the wrapper matters — the governed block]

## Say it to your companion

Tell your companion, in your own words: A **compound instruction** is a sequence of instructions enclosed by **begin** and **end**, treated by the grammar as **one instruction**. The instructions inside are separated by semicolons — none is needed after the last, before end (a semicolon there only adds an empty instruction). C++ wraps the same idea in **braces { }**. Wherever the grammar asks for one instruction — an if's branch, a loop's body, a case's label — a compound instruction can stand, carrying as many steps as the work needs. Without the wrapper, governance leaks: in `if x > 0 then a := 1; b := 2;` only a := 1 is conditional — b := 2 runs always, because the if governs one instruction. With begin…end around both, the pair stands or falls together. The lesson's reading habit follows: to know what any governing instruction commands, find its **one instruction** — a single step, or the whole begin…end block — and draw its border before judging the program. Most beginner logic errors are border errors. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A sequence of instructions in begin…end, treated as one instruction. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: By semicolons — none is needed after the last, before end. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Braces { }. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Wherever the grammar asks for one instruction — if branches, loop bodies, case labels. Do this with a real example of your own and write or say how you know it is right.
