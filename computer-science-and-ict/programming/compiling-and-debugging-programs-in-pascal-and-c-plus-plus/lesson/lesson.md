# Compiling and Debugging Programs in Pascal and C++

## Do it first

Grade 10's book ends not with theory but with the workshop: two annexes, one per language, on the two acts every program in the upper grades will pass through — being compiled, and being debugged.

## Sub lesson 1 — Compiling — from text to running program

**Compilation** translates the whole program text into the machine's language before any of it runs: the **compiler** checks the text against the language's grammar, and a text with **syntax errors does not compile at all** — the compiler lists the errors, by line, in its own terse tongue the annexes teach to read. The translated parts are then **linked** with the libraries' ready pieces into one executable file. Compile-time is the grammar's judgement; a clean compile says the text is *legal* — it does not yet say the program is *right*.

[Picture — Compiling — from text to running program]

## Sub lesson 2 — Debugging — hunting the errors the compiler cannot see

The errors that remain are **runtime and logic errors**: the program runs, and divides by zero, or answers wrong, or loops forever. **Debugging (depanare)** hunts them with a method: **reproduce** the failure on the smallest input, **watch** the values (by inserted prints, or the debugger's stepping and breakpoints — pausing the run at a chosen line to inspect the state), **locate** the first moment the state goes wrong, **fix**, and **test again**. The annexes' stance is the profession's: debugging is not shame — it is half the craft, practised by method, not by staring.

[Picture — Debugging — hunting the errors the compiler cannot see]

## Say it to your companion

Tell your companion, in your own words: **Compilation** translates the whole program text into the machine's language before any of it runs: the **compiler** checks the text against the language's grammar, and a text with **syntax errors does not compile at all** — the compiler lists the errors, by line, in its own terse tongue the annexes teach to read. The translated parts are then **linked** with the libraries' ready pieces into one executable file. Compile-time is the grammar's judgement; a clean compile says the text is *legal* — it does not yet say the program is *right*. The errors that remain are **runtime and logic errors**: the program runs, and divides by zero, or answers wrong, or loops forever. **Debugging (depanare)** hunts them with a method: **reproduce** the failure on the smallest input, **watch** the values (by inserted prints, or the debugger's stepping and breakpoints — pausing the run at a chosen line to inspect the state), **locate** the first moment the state goes wrong, **fix**, and **test again**. The annexes' stance is the profession's: debugging is not shame — it is half the craft, practised by method, not by staring. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: It translates the whole program text into machine language before any of it runs. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: It stops compilation — the compiler lists errors by line. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The libraries' ready pieces, joined into one executable file. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: That the text is legal — not yet that the program is right. Do this with a real example of your own and write or say how you know it is right.
