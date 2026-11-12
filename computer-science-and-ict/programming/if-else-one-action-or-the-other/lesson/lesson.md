# if…else — one action or the other

## Do it first

Run this program with n = 4, then run it again with n = 7.

```python
n = 4
if n % 2 == 0:
    print(n, "is even")
else:
    print(n, "is odd")
```

First run: `4 is even`. Second run: `7 is odd`. One program, two roads — and every number takes exactly one of them. That is `if…else`.

## Sub lesson 1 — Two roads — if runs on true, else runs on false

**If…else** gives two alternative blocks:

- the statements under `if` run when the expression is **true**;
- the statements under `else` run when it is **false**.

The program chooses between two actions — one road or the other, never both, never neither. Walk an age example the same way: predict the output from the stored value first, then run and check.

[Picture 31703 — a fork with true and false roads, a number arriving at each end labelled even or odd]

[GIF 31721 — a number travelling down the true road, then another down the false road]

## Sub lesson 2 — The even/odd program — remainder divided by 2

The running problem: is a number even or odd? Divide by 2 and look at the **remainder** — in Python, `n % 2`.

```python
n = 4
if n % 2 == 0:
    print(n, "is even")
else:
    print(n, "is odd")
```

Remainder 0 means the number divides exactly by 2 — even. Any other remainder falls to `else` — odd. Outputs verified: n = 4 prints `4 is even`; n = 7 prints `7 is odd`. Watch the GIF: one number travels the true road, another travels the false road.

## Say it to your companion

Walk your companion down both roads of the even/odd program: which test is asked, and which block runs for 4 and for 7.

## Do It Yourself

1. Run even/odd with 10, 15 and 100. Predict each answer first.
2. Write an if…else that prints 'pass' when a mark is 50 or more, else 'fail'. Test mark 50 — it must print pass.
3. Explain in one sentence why exactly one block runs every time.
