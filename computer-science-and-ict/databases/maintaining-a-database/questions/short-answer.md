# Maintaining a Database — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) Why does an Access file bloat?**
**Answer: Deleted records and objects leave claimed, empty gaps — the file does not shrink**

**2. (Sub lesson 1) What does Compact and Repair do?**
**Answer: Rebuilds the file — records in order, gaps dropped, indexes rebuilt, damage repaired where possible**

**3. (Sub lesson 1) When should compacting happen?**
**Answer: Regularly — weekly in working databases, and always after mass deletions**

**4. (Sub lesson 1) On what should it be run?**
**Answer: On a copy kept safe until the compacted file proves sound**

**5. (Sub lesson 1) Is compacting a rescue or a routine?**
**Answer: A routine — the rescue use is its failure mode**

**6. (Sub lesson 2) What is the only true repair for corruption or loss?**
**Answer: A backup — dated copies kept apart from the working machine**

**7. (Sub lesson 2) What does splitting divide?**
**Answer: A back-end of tables (shared) and front-ends of queries, forms and reports (per user)**

**8. (Sub lesson 2) Why split?**
**Answer: So many users share the data without sharing the damage**

**9. (Sub lesson 2) What does protection add?**
**Answer: Passwords and permissions over the tables**

**10. (Sub lesson 2) How do databases usually die, in the lesson's verdict?**
**Answer: Unkept — not of hard questions**
