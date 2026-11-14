# Type Conversions in C++ — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What happens to an int beside a double?**
**Answer: It is widened to double before the operation — 5 + 2.0 = 7.0**

**2. (Sub lesson 1) What does a char promote to?**
**Answer: An int — its code number**

**3. (Sub lesson 1) What happens when a double is stored into an int?**
**Answer: Narrowing — the fraction is cut off: 7.9 becomes 7**

**4. (Sub lesson 1) Which direction keeps information?**
**Answer: Widening; narrowing destroys it — silently**

**5. (Sub lesson 1) Does the compiler error on narrowing assignment?**
**Answer: No — at default settings it neither errors nor warns**

**6. (Sub lesson 2) How is an explicit conversion written?**
**Answer: As a cast — (double) n or double(n)**

**7. (Sub lesson 2) What does casting n = 7 make n / 2 give?**
**Answer: 3.5 — the real division, not the integer 3**

**8. (Sub lesson 2) What is the cast's virtue?**
**Answer: Visibility — it signs the intended conversion in the text**

**9. (Sub lesson 2) Does a cast change the variable itself?**
**Answer: No — it converts the value for this operation; the variable keeps its type**

**10. (Sub lesson 2) State the section's rule.**
**Answer: Let widening happen; cast every narrowing you mean; never let one happen unmeant**
