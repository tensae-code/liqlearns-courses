# Indentation in Python — spaces that mean something

## Do it first

Look at these two programs. Only one runs. Which — and what is different?

Program A:
```python
if age > 0
    print("positive")
```

Program B:
```python
if age > 0:
print("positive")
```

A is missing its colon. B is missing its indentation. BOTH are broken — this lesson is the two rules that make or break a Python program.

## Sub lesson 1 — The colon rule — and brackets you may leave off

Rule one: **the if expression must be followed by a colon**. Forget it and Python gives a syntax error before anything runs.

Rule one-and-a-half: enclosing the expression in **parentheses is optional** in Python — `if (age > 0):` and `if age > 0:` both work — unlike languages that require the brackets. The colon is not optional; the brackets are.

[Picture 31704 — five mini-programs, ticked or crossed for colon and indentation faults]

[GIF 31730 — a block of code sliding in under an if line as it is indented, then the program running]

## Sub lesson 2 — Indentation — a block is its spaces

In Python, **indentation — the spaces at the start of a line — is not mere readability. It indicates a block of code.**

- A block left unindented **errors**.
- **At least one space** is required to indent.
- The **same block must use the same number of spaces** throughout, or Python errors.

When a branching program fails, indentation is the usual culprit: the statements after the if clause are not properly indented, and at least one indented statement must follow an if. Watch the GIF: the block slides in under the if line — that slide IS the meaning.

## Say it to your companion

Tell your companion the two rules — colon always, brackets optional; indentation same-block same-spaces — and show the sliding block in the GIF.

## Do It Yourself

1. Fix Program A and Program B from Do it first and run both.
2. Indent a block with 4 spaces on one line and 2 on the next — run it, name the error, then fix it.
3. Find the indentation fault in a partner's broken program and repair it.
