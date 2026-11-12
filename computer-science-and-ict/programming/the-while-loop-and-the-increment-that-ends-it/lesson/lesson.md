# The while loop — and the increment that ends it

## Do it first

Run this program and count its lines of output:

```python
count = 0
while count < 5:
    print(count)
    count += 1
```

It prints `0 1 2 3 4` — five lines, verified — then stops by itself. Now cover the last line with your hand and think: without `count += 1`, when would it stop? Never. That one line is the difference between a loop and a trap.

## Sub lesson 1 — The while shape — test first, every time

The **while loop** repeats a statement or block controlled by a conditional expression. Its syntax: the `while` keyword, an **expression ending with a colon**, and an **indented block**.

The expression is **checked at the beginning of every loop**. The block runs while it is true. The **first time it evaluates false, the loop stops** without executing further statements.

[Picture 31711 — a loop gate re-asking 'still less than 5?' with a counter climbing inside]

[GIF 31727 — a counter climbing until the gate closes]

## Sub lesson 2 — count += 1 — the line that ends the loop

In the worked program, the line `count += 1` — the **increment** — sits inside the loop and moves the counter toward the gate. **Forget it and the loop continues forever**, because the condition can never turn false.

One problem, two roads: a while loop and a for loop can solve the same counting problem and give the **same output** — different programmers approach the same problem in different ways, and problem-solving needs creative thinking. Watch the GIF: the counter climbs until the gate closes.

## Say it to your companion

Explain the while gate to your companion — tested first, every time — and why the increment line must live inside the block.

## Do It Yourself

1. Run the count program; change the gate to count < 3 and predict before running.
2. Remove the increment, run, and stop the runaway loop — then restore the line.
3. Rewrite the count program as a for loop with range and show the outputs match.
