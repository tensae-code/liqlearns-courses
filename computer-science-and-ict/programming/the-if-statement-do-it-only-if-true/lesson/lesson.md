# The if statement — do it only if it's true

## Do it first

Type this program and run it twice — once with age 1, once with age −1. Watch what happens to the two indented lines.

```python
age = 1
if age > 0:
    print("positive")
    print("runs")
```

With age 1 it prints both lines. With age −1 it prints nothing at all. That gate — open when true, shut when false — is the `if` statement.

## Sub lesson 1 — The gate — the indented block runs only when the test is true

The **if statement** is the simplest conditional:

```python
age = 1
if age > 0:
    print("positive")
    print("runs")
```

The `if` is followed by a **condition** — an expression that is true or false — and the condition **must end with a colon `:`**. Missing the colon is a syntax error. After the colon comes an **indented block**: at least one statement, indented. If the condition holds, the block runs. If not, the block is skipped completely. Output with age 1: `positive` then `runs` — verified. Output with age −1: nothing — verified.

[Picture 31702 — a gate that opens for a true test and stays shut for a false one, over the age program]

## Sub lesson 2 — What is NOT part of the if

Statements before or after the `if` that are **not indented** are not part of it — they execute as normal, whichever way the test goes.

So entering age 0 makes the test `age > 0` false, and an age test prints nothing; and any age under 18 in an adult test produces the 'child' side of the program's logic. The gate only guards its own indented block — nothing else.

## Say it to your companion

Explain the if gate to your companion: the condition, the colon, the indented block — and what happens when the test is false.

## Do It Yourself

1. Run the age program with age 1, 0 and −1. Write what prints each time before you run it.
2. Add one non-indented print after the if block and show it runs in every case.
3. Remove the colon and run — name the error, then fix it.
