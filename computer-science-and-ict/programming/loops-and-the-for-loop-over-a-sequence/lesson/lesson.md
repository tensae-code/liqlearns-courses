# Loops — and the for loop over a sequence

## Do it first

A teacher must grade 50 students. Writing the grade block 50 times would fill pages — and one change would mean 50 fixes. Instead the teacher writes the block ONCE and lets the computer go round it 50 times. That going-round is a **loop**. Watch the GIF: a variable travels along a row of items, visiting each one in turn. That travelling variable is the `for` loop.

## Sub lesson 1 — Why loops exist — 50 students, one grading block

Most real problems repeat an action. A **loop** is code that repeats a statement or group of statements:

- a **fixed number of times**, or
- **until a condition is satisfied**.

Counting itself is the everyday looping problem: start at 1, add 1 to reach the next number, and repeat until 100. Python has **two built-in loops**: `for` and `while`.

[Picture 31707 — a loop arrow carrying a variable through a row of items one by one]

[GIF 31723 — a variable moving item to item along a list]

## Sub lesson 2 — The for loop — a variable that visits every item

The **for loop** iterates over the items of any **sequence** — a list, string, tuple, dictionary or other container:

```python
for item in sequence:
    # indented block — runs once per item
```

Its syntax names:

- a **temporary variable** that takes each item's value in turn;
- the **sequence** it walks;
- a **colon**, and an **indented block** of statements.

Each pass through the block is one **iteration**, with the variable holding the next item.

## Say it to your companion

Tell your companion what a loop is, name Python's two loops, and walk the for skeleton part by part.

## Do It Yourself

1. Say which loop problems in your day are fixed-count and which are until-a-condition.
2. Write the for skeleton from memory, naming each part.
3. Explain to yourself why grading 50 students needs one block, not fifty.
