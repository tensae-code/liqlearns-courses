# Arrays in Pascal and C++ — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) What is an array?** → **A fixed row of values of one type under one name, reached by index**

**2. (Sub lesson 1) How does Pascal declare 30 integers?** → **var a: array[1..30] of integer;**

**3. (Sub lesson 1) How does C++ declare them, and what are its indexes?** → **int a[30]; — indexes 0..29**

**4. (Sub lesson 1) Is a[i] an ordinary variable?** → **Yes — of the element type: assignable, readable, computable**

**5. (Sub lesson 1) Why may the index be an expression?** → **So a loop can compute which element to touch — the array's whole power**

**6. (Sub lesson 2) What walks an array in almost all its work?** → **A for loop carrying the index across the whole range**

**7. (Sub lesson 2) Name three array-processing patterns.** → **Summing, searching for a value, finding the greatest element (also: reading in, printing out)**

**8. (Sub lesson 2) What is the border danger?** → **An out-of-range index touches memory that is not the array's**

**9. (Sub lesson 2) How do the languages differ at the border?** → **Pascal's range checking catches it; C++ lets it pass silently**

**10. (Sub lesson 2) What gathers a sum across the walk?** → **An accumulator**
