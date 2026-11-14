# Subrange Data Types in Pascal — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) How is a subrange type defined?** → **By its first and last values — type TDayNum = 1..31;**

**2. (Sub lesson 1) From what kinds of types are subranges cut?** → **Ordinal types — integer, char, boolean, enumerations**

**3. (Sub lesson 1) Give a char subrange.** → **'A'..'Z'**

**4. (Sub lesson 1) What does the slice state in the open?** → **The data's real limits — the promise the type makes**

**5. (Sub lesson 1) Can a TDayNum variable hold 47?** → **No — only 1 to 31**

**6. (Sub lesson 2) What is range checking?** → **The guard that stops the program with an error when a value steps outside the slice**

**7. (Sub lesson 2) What happens to dn := 32 with checks on?** → **An error at that line — the program stops instead of carrying a poisoned value**

**8. (Sub lesson 2) What would an ordinary integer do with 32?** → **Hold it silently — the error would surface far away, unfindable**

**9. (Sub lesson 2) What is the subrange's argument in one line?** → **Errors are cheapest where they are made**

**10. (Sub lesson 2) Does a subrange need new values of its own?** → **No — it borrows its host ordinal type's values, sliced**
