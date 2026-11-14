# User-Defined Functions in Python — short answer

Answer in a sentence or two, in your own words — or in code where the question asks for code.

**1. (Sub lesson 1) A student writes a correct `def greet():` block and runs the program, but no greeting appears. What is missing?**
**Answer:** The call. The `def` block only defines the function; the student must call it — `greet()` — for the job to run.

**2. (Sub lesson 2) Write a function `double(n)` that returns twice `n`, and show a call that stores its result for 7 in a variable `d`.**
**Answer:** `def double(n):` with body `return n * 2`, then `d = double(7)` — `d` now holds 14.

**3. (Sub lesson 2) Why is a function with parameters stronger than a function that works on one fixed value written inside it?**
**Answer:** The same written block can serve many values: each call hands in its own arguments, so one function squares 3, 10 or any number, instead of only ever squaring the one fixed value.
