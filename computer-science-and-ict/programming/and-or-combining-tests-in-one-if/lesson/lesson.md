# and / or — combining tests in one if

## Do it first

A clinic rule: send a patient for a check when they have a high temperature AND they are coughing. One sign alone is not the rule — both together are. Python writes that rule in one line:

```python
temp = True
cough = True
if temp and cough:
    print("see a doctor")
```

Run it: `see a doctor` — verified. Change cough to False and run again: nothing. That is `and`.

## Sub lesson 1 — and — both must be true

The logical operator **`and`** combines two conditions in one `if`. The combined test is **true only when both parts are true**:

| A | B | A and B |
|---|---|---|
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |

One false side is enough to close the gate.

[Picture 31706 — two switches in series labelled AND beside two in parallel labelled OR]

## Sub lesson 2 — or — any one is enough

The logical operator **`or`** is true **if any one** of the compared conditions is satisfied — it is false only when **both** sides are false.

```python
subject = "Biology"
if subject == "Physics" or subject == "Chemistry" or subject == "Geography":
    print("science")
else:
    print("not listed")
```

Biology matches none of the three, so the program falls to `else`: `not listed` — verified. (The example stores its subjects in a variable that can hold multiple values — a list; loops over lists come later in this unit.)

## Say it to your companion

Tell your companion the two truth rules: AND needs both; OR needs any one — and give the clinic and subject examples.

## Do It Yourself

1. Run the clinic program with all four True/False pairs and fill the and table yourself.
2. Run the subject program with Physics, then with Biology.
3. Write one if using or with three alternatives of your own.
