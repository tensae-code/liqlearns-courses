# if…elif…else — a chain of choices

## Do it first

A mark needs a word, not just a number: Excellent, Very Good, Good, Satisfactory or Fail. One if gives two roads — not five. Run this chain with mark = 85:

```python
mark = 85
if mark >= 90:
    print("Excellent")
elif mark >= 75:
    print("Very Good")
elif mark >= 60:
    print("Good")
elif mark >= 50:
    print("Satisfactory")
else:
    print("Fail")
```

It prints `Very Good` — verified. The value stepped down the chain until the second test caught it.

## Sub lesson 1 — The chain — first true block wins

**elif** means: 'if the previous conditions are not true, then try this condition.' It adds any number of alternatives between `if` and a final `else`.

The rules of the chain:

- Expressions are evaluated **one after another**, top to bottom.
- The **first true block runs** — and the rest of the chain is skipped.
- If **none** is true, the **else block runs** — the net that catches anything not caught before.

Watch the GIF: the value steps down the staircase until a condition catches it.

[Picture 31705 — a staircase of conditions with a value stepping down until one catches it, and a final else net]

[GIF 31722 — a value stepping down the elif chain until a condition catches it]

## Sub lesson 2 — Worked chains — marks, ages, and type()

Age chain:

```python
age = 80
if age < 13:
    print("child")
elif age < 20:
    print("adolescent")
elif age < 60:
    print("adult")
else:
    print("senior adult")
```

Age 80 passes every test uncaught and lands in `else`: output `senior adult` — verified.

A chain can also test types: with `type()` in the conditions, a chain reports that a price variable holds a **floating number** — and the type puzzle behind it is that a variable holding a string makes only the string-type comparison true.

## Say it to your companion

Explain the chain to your companion: tests in order, first true wins, else catches the rest — using the staircase GIF.

## Do It Yourself

1. Run the marks chain with 95, 85, 62, 50 and 49. Predict each word first — 50 must give Satisfactory.
2. Run the age chain with 10, 16, 40 and 80.
3. Add one more elif rung to the marks chain for marks of 40–49: 'Try again'.
4. Build the four-operation calculator (the guide's keyed review program — teacher guide evidence, in sources). The program asks the user to choose **1 for add, 2 for subtract, 3 for multiply, 4 for divide**, reads two numbers, and prints the sum, difference, product or division — with an **"invalid operation"** branch for any other choice:

```python
choice = int(input("Choose 1 add, 2 subtract, 3 multiply, 4 divide: "))
a = float(input("First number: "))
b = float(input("Second number: "))
if choice == 1:
    print(a + b)
elif choice == 2:
    print(a - b)
elif choice == 3:
    print(a * b)
elif choice == 4:
    print(a / b)
else:
    print("invalid operation")
```

Run it with choice 1 and the numbers 6 and 3 — it must print 9. Then run choice 3 with 6 and 3 (18), and choice 9 (invalid operation). Say why this program is a chain and not four separate ifs.
