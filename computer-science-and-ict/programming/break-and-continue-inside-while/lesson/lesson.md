# break and continue inside while

## Do it first

Run both programs and count the printed lines:

```python
count = 0
while True:
    count += 1
    if count == 5:
        break
    print(count)
```

```python
count = 0
while count < 9:
    count += 1
    if count == 5:
        continue
    print(count)
```

First prints 1, 2, 3, 4 — four lines. Second prints 1, 2, 3, 4, 6, 7, 8, 9 — eight lines out of nine turns. Same two keywords as in for — new behaviour to trace carefully.

## Sub lesson 1 — break in while — out even while the condition is true

**break** also stops a **while** loop — **even while its condition is still true**. In the first program the loop's own condition (`True`) would never end it; the break terminates it when the count **reaches 5, in the fifth iteration** — and because break sits before the print, 5 itself never prints. Output: 1, 2, 3, 4 — verified.

[Picture 31712 — a while loop with one value jumping the exit and another being skipped over]

## Sub lesson 2 — continue in while — nine turns, eight prints

**continue** in a while loop stops the current iteration and moves to the next. The second program is set to iterate **nine times but prints eight values**, because the print is **escaped when the count equals the escape value** (5). Output: 1, 2, 3, 4, 6, 7, 8, 9 — verified.

Warning that belongs to while: the increment must happen **before** continue is reached, or the skipped turn never advances the counter and the loop can stick forever. In this program `count += 1` sits above the continue test — that placement is what makes it safe.

## Say it to your companion

Trace both programs aloud for your companion: where break fires, which turn continue escapes, and why eight prints come from nine turns.

## Do It Yourself

1. Change the break value to 3 and predict the output before running.
2. Change the escape value to 7 — how many lines print now? Predict, then run.
3. Move the increment below the continue test in a copy, run it briefly, and explain what goes wrong — then fix the copy.
