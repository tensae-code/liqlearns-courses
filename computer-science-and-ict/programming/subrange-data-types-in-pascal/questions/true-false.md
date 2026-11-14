# Subrange Data Types in Pascal — true or false

Say true or false, and fix the false ones in your own words.

**1. (Sub lesson 1) True or false: By its first and last values — type TDayNum = 1..31;**
**Answer: True**

**2. (Sub lesson 1) True or false: By its first and last values — type TDayNum = 1..31;** — as the answer to: From what kinds of types are subranges cut?
**Answer: False — Ordinal types — integer, char, boolean, enumerations**

**3. (Sub lesson 1) True or false: 'A'..'Z'**
**Answer: True**

**4. (Sub lesson 1) True or false: 'A'..'Z'** — as the answer to: What does the slice state in the open?
**Answer: False — The data's real limits — the promise the type makes**

**5. (Sub lesson 1) True or false: No — only 1 to 31**
**Answer: True**

**6. (Sub lesson 2) True or false: No — only 1 to 31** — as the answer to: What is range checking?
**Answer: False — The guard that stops the program with an error when a value steps outside the slice**

**7. (Sub lesson 2) True or false: An error at that line — the program stops instead of carrying a poisoned value**
**Answer: True**

**8. (Sub lesson 2) True or false: An error at that line — the program stops instead of carrying a poisoned value** — as the answer to: What would an ordinary integer do with 32?
**Answer: False — Hold it silently — the error would surface far away, unfindable**

**9. (Sub lesson 2) True or false: Errors are cheapest where they are made**
**Answer: True**

**10. (Sub lesson 2) True or false: Errors are cheapest where they are made** — as the answer to: Does a subrange need new values of its own?
**Answer: False — No — it borrows its host ordinal type's values, sliced**
