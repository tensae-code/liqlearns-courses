# Solving Problems by Enumeration — short answer

Answer each question in a few sentences.

**1. (Sub lesson 1) A two-digit locker code: the digits add to 11 and both digits are odd. Enumerate in order and find all codes that fit.**
**Answer:** Odd digits are 1, 3, 5, 7, 9. Testing pairs in counting order: 1 needs 10 (not a digit), 3 needs 8 (even), 5 needs 6 (even), 7 needs 4 (even), 9 needs 2 (even) — every pair needs one even digit, because odd + odd is always even and 11 is odd. So the list of solutions is empty: enumeration, honestly finished, proves no such code exists, and one of the remembered conditions must be wrong.

**2. (Sub lesson 2) When should a problem-solver choose enumeration over looking for a formula?**
**Answer:** When the candidate list is small enough to finish and each candidate is easy to test — especially when no formula is known or finding one is harder than searching. If the list explodes, enumeration stops being practical and the analytic route (or shrinking the list with conditions) must come first.
