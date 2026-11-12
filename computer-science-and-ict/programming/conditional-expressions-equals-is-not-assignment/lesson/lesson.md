# Conditional expressions — == is not =

## Do it first

Answer quickly: is 3 equal to 4? You said no — in Python that answer is written `False`, and the test is written `3 == 4`. Notice the double equals. In this lesson you learn to write tests that answer True or False — and why the test sign has two strokes while the putting-in sign has one.

## Sub lesson 1 — Tests that answer true or false

A **conditional expression** is a test. It uses **comparison operators** or **Boolean operators** (`and`, `or`, `not`), and its result is always **True** or **False**.

```python
print(3 == 4)
```

Run it: the output is `False` — verified. Conditionals are used most commonly inside `if` statements and loops, which fill the rest of this unit.

[Picture 31701 — a two-column Python-versus-maths operator chart, with = and == marked as different jobs]

## Sub lesson 2 — Python signs versus maths signs — and = versus ==

Python's signs differ slightly from the mathematics signs:

| Meaning | Python | Mathematics |
|---|---|---|
| equals | `==` | = |
| not equals | `!=` | ≠ |
| less than | `<` | < |
| greater than | `>` | > |
| less than or equal | `<=` | ≤ |
| greater than or equal | `>=` | ≥ |

The trap: a single `=` does not test anything — it **assigns**, putting a value into a variable. The double `==` **compares**.

```python
height = 2.5
print(height == 2.5)
```

The first line assigns 2.5 to `height`. The second line compares — and prints `True`, verified. A not-equal test on two equal numbers is False, and a greater-or-equal test that fails is False — tests always tell the truth about the values they are given.

## Say it to your companion

Tell your companion why `=` and `==` are different signs doing different jobs, then test them: give a value with `=`, and ask a question with `==`.

## Do It Yourself

1. Run `3 == 4`, `5 != 5` and `7 >= 9` in the shell and write each result.
2. Assign your height to a variable, then test with `==` whether it equals that value.
3. Write the Python sign for 'not equals' and for 'less than or equal' from memory.
