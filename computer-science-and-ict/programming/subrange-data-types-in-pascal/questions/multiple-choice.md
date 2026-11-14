# Subrange Data Types in Pascal — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) How is a subrange type defined?**
a) By its first and last values — type TDayNum = 1..31;  b) Ordinal types — integer, char, boolean, enumerations  c) 'A'..'Z'  d) The data's real limits — the promise the type makes
**Answer: a**

**2. (Sub lesson 1) From what kinds of types are subranges cut?**
a) Ordinal types — integer, char, boolean, enumerations  b) 'A'..'Z'  c) The data's real limits — the promise the type makes  d) No — only 1 to 31
**Answer: a**

**3. (Sub lesson 1) Give a char subrange.**
a) 'A'..'Z'  b) The data's real limits — the promise the type makes  c) No — only 1 to 31  d) The guard that stops the program with an error when a value steps outside the slice
**Answer: a**

**4. (Sub lesson 1) What does the slice state in the open?**
a) The data's real limits — the promise the type makes  b) No — only 1 to 31  c) The guard that stops the program with an error when a value steps outside the slice  d) An error at that line — the program stops instead of carrying a poisoned value
**Answer: a**

**5. (Sub lesson 1) Can a TDayNum variable hold 47?**
a) No — only 1 to 31  b) The guard that stops the program with an error when a value steps outside the slice  c) An error at that line — the program stops instead of carrying a poisoned value  d) Hold it silently — the error would surface far away, unfindable
**Answer: a**

**6. (Sub lesson 2) What is range checking?**
a) The guard that stops the program with an error when a value steps outside the slice  b) An error at that line — the program stops instead of carrying a poisoned value  c) Hold it silently — the error would surface far away, unfindable  d) Errors are cheapest where they are made
**Answer: a**

**7. (Sub lesson 2) What happens to dn := 32 with checks on?**
a) An error at that line — the program stops instead of carrying a poisoned value  b) Hold it silently — the error would surface far away, unfindable  c) Errors are cheapest where they are made  d) No — it borrows its host ordinal type's values, sliced
**Answer: a**

**8. (Sub lesson 2) What would an ordinary integer do with 32?**
a) Hold it silently — the error would surface far away, unfindable  b) Errors are cheapest where they are made  c) No — it borrows its host ordinal type's values, sliced  d) By its first and last values — type TDayNum = 1..31;
**Answer: a**

**9. (Sub lesson 2) What is the subrange's argument in one line?**
a) Errors are cheapest where they are made  b) No — it borrows its host ordinal type's values, sliced  c) By its first and last values — type TDayNum = 1..31;  d) Ordinal types — integer, char, boolean, enumerations
**Answer: a**

**10. (Sub lesson 2) Does a subrange need new values of its own?**
a) No — it borrows its host ordinal type's values, sliced  b) By its first and last values — type TDayNum = 1..31;  c) Ordinal types — integer, char, boolean, enumerations  d) 'A'..'Z'
**Answer: a**
