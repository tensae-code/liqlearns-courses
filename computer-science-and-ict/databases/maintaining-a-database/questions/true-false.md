# Maintaining a Database — true or false

Say true or false, and fix the false ones in your own words.

**1. (Sub lesson 1) True or false: Deleted records and objects leave claimed, empty gaps — the file does not shrink**
**Answer: True**

**2. (Sub lesson 1) True or false: Deleted records and objects leave claimed, empty gaps — the file does not shrink** — as the answer to: What does Compact and Repair do?
**Answer: False — Rebuilds the file — records in order, gaps dropped, indexes rebuilt, damage repaired where possible**

**3. (Sub lesson 1) True or false: Regularly — weekly in working databases, and always after mass deletions**
**Answer: True**

**4. (Sub lesson 1) True or false: Regularly — weekly in working databases, and always after mass deletions** — as the answer to: On what should it be run?
**Answer: False — On a copy kept safe until the compacted file proves sound**

**5. (Sub lesson 1) True or false: A routine — the rescue use is its failure mode**
**Answer: True**

**6. (Sub lesson 2) True or false: A routine — the rescue use is its failure mode** — as the answer to: What is the only true repair for corruption or loss?
**Answer: False — A backup — dated copies kept apart from the working machine**

**7. (Sub lesson 2) True or false: A back-end of tables (shared) and front-ends of queries, forms and reports (per user)**
**Answer: True**

**8. (Sub lesson 2) True or false: A back-end of tables (shared) and front-ends of queries, forms and reports (per user)** — as the answer to: Why split?
**Answer: False — So many users share the data without sharing the damage**

**9. (Sub lesson 2) True or false: Passwords and permissions over the tables**
**Answer: True**

**10. (Sub lesson 2) True or false: Passwords and permissions over the tables** — as the answer to: How do databases usually die, in the lesson's verdict?
**Answer: False — Unkept — not of hard questions**
