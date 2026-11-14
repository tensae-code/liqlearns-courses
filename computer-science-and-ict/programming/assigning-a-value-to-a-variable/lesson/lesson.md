# Assigning a Value to a Variable

## Do it first

One small sign does the most common job in programming, and it does not mean what it means in maths. This lesson makes assignment exact.

## Sub lesson 1 — Right side first, then store

In **x = expression;** the machine **evaluates the right side completely**, then **copies the result into x**, destroying x's previous value. `int x;` alone leaves x holding garbage until an assignment (or input) gives it a real value — a variable's **initialisation** is simply its first assignment, often written with the declaration: `int x = 0;`.

[Picture — right side first, then store]

## Sub lesson 2 — Store, not equals — and growing a value

Because = means store, **x = x + 1** reads: take x's current value, add 1, store it back — the standard **counter** step, impossible as an equation and ordinary as an instruction. Chained thinking follows: swap two variables needs a **third** to hold one value during the exchange, because the first store destroys what the second still needs.

[Picture — store, not equals — and growing a value]

## Say it to your companion

Tell your companion, in your own words: Assignment stores a value into a variable: the right-hand side is worked out first, then its result replaces whatever the variable held before — the old value is gone — and the sign is a single = which means 'store', never 'equals', which is why x = x + 1 is a sensible instruction and a false equation. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The right-hand side, completely. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Garbage, until assignment or input. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Store — not equals. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The counter step. Do this with a real example of your own and write or say how you know it is right.
