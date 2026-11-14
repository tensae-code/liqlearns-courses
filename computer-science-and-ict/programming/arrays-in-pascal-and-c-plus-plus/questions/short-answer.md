# Arrays in Pascal and C++ — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What is an array?**
**Answer: A fixed row of values of one type under one name, reached by index**

**2. (Sub lesson 1) How does Pascal declare 30 integers?**
**Answer: var a: array[1..30] of integer;**

**3. (Sub lesson 1) How does C++ declare them, and what are its indexes?**
**Answer: int a[30]; — indexes 0..29**

**4. (Sub lesson 1) Is a[i] an ordinary variable?**
**Answer: Yes — of the element type: assignable, readable, computable**

**5. (Sub lesson 1) Why may the index be an expression?**
**Answer: So a loop can compute which element to touch — the array's whole power**

**6. (Sub lesson 2) What walks an array in almost all its work?**
**Answer: A for loop carrying the index across the whole range**

**7. (Sub lesson 2) Name three array-processing patterns.**
**Answer: Summing, searching for a value, finding the greatest element (also: reading in, printing out)**

**8. (Sub lesson 2) What is the border danger?**
**Answer: An out-of-range index touches memory that is not the array's**

**9. (Sub lesson 2) How do the languages differ at the border?**
**Answer: Pascal's range checking catches it; C++ lets it pass silently**

**10. (Sub lesson 2) What gathers a sum across the walk?**
**Answer: An accumulator**
