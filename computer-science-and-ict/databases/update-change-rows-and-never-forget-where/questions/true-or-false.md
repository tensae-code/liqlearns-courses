# UPDATE — change rows, and never forget WHERE — true or false

Say true or false.

**1. (Sub lesson 1)** UPDATE Teacher SET Salary = 15000 WHERE Salary < 10000 also raises a salary of 12,000.
**Answer: False** — 12,000 fails the WHERE, so it is untouched.

**2. (Sub lesson 2)** SET can set more than one column in a single UPDATE.
**Answer: True** — the form sets one or more columns.

**3. (Sub lesson 3)** An UPDATE without WHERE is refused by Access.
**Answer: False** — it runs — on every row. The danger is that it succeeds.

**4. (Sub lesson 3)** Reading the WHERE aloud before running an UPDATE is part of this lesson's method.
**Answer: True** — no spoken WHERE, no run.
