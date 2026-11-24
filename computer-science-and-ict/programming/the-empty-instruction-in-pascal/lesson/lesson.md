# The Empty Instruction in Pascal

## Do it first

The smallest instruction in Pascal is no instruction at all. Both Moldova books give it a section of its own — not because it does anything, but because *accidentally* writing it changes what a program does.

## Sub lesson 1 — Nothing, in an instruction's place

The **empty instruction** is the **absence of an instruction where one is grammatically allowed**: between two semicolons (`;;`), after begin, or before end. It **does nothing** — no action, no state change — and it is legal everywhere an instruction may stand. Its honest uses are rare: a loop whose work is all in its condition, a placeholder kept while building. Pascal's grammar treats the semicolon as a **separator** between instructions, not a terminator — which is exactly why an empty instruction can slip in unnoticed.

In your mind's eye: nothing, in an instruction's place.

## Sub lesson 2 — The classic trap — the stray semicolon

The empty instruction's famous crime: `if x > 0 then ; writeln(x)` — the semicolon after then makes the if's body the **empty instruction**, so writeln runs **always**, not conditionally; and `while not eof do ;` hangs forever, its body empty, its condition never changed by nothing. The defence is reading: a semicolon before a body that matters should ring a bell. What the machine executes is what is written — an empty body is executed, obediently, a million times a second.

In your mind's eye: the classic trap — the stray semicolon.

## Say it to your companion

Tell your companion, in your own words: The **empty instruction** is the **absence of an instruction where one is grammatically allowed**: between two semicolons (`;;`), after begin, or before end. It **does nothing** — no action, no state change — and it is legal everywhere an instruction may stand. Its honest uses are rare: a loop whose work is all in its condition, a placeholder kept while building. Pascal's grammar treats the semicolon as a **separator** between instructions, not a terminator — which is exactly why an empty instruction can slip in unnoticed. The empty instruction's famous crime: `if x > 0 then ; writeln(x)` — the semicolon after then makes the if's body the **empty instruction**, so writeln runs **always**, not conditionally; and `while not eof do ;` hangs forever, its body empty, its condition never changed by nothing. The defence is reading: a semicolon before a body that matters should ring a bell. What the machine executes is what is written — an empty body is executed, obediently, a million times a second. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The absence of an instruction where one is grammatically allowed — it does nothing. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Between two semicolons, after begin, or before end. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — it is a separator between instructions. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A loop whose work is all in its condition (or a placeholder while building). Do this with a real example of your own and write or say how you know it is right.
