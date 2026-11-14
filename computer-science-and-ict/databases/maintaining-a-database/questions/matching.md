# Maintaining a Database — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) Why does an Access file bloat?** → **Deleted records and objects leave claimed, empty gaps — the file does not shrink**

**2. (Sub lesson 1) What does Compact and Repair do?** → **Rebuilds the file — records in order, gaps dropped, indexes rebuilt, damage repaired where possible**

**3. (Sub lesson 1) When should compacting happen?** → **Regularly — weekly in working databases, and always after mass deletions**

**4. (Sub lesson 1) On what should it be run?** → **On a copy kept safe until the compacted file proves sound**

**5. (Sub lesson 1) Is compacting a rescue or a routine?** → **A routine — the rescue use is its failure mode**

**6. (Sub lesson 2) What is the only true repair for corruption or loss?** → **A backup — dated copies kept apart from the working machine**

**7. (Sub lesson 2) What does splitting divide?** → **A back-end of tables (shared) and front-ends of queries, forms and reports (per user)**

**8. (Sub lesson 2) Why split?** → **So many users share the data without sharing the damage**

**9. (Sub lesson 2) What does protection add?** → **Passwords and permissions over the tables**

**10. (Sub lesson 2) How do databases usually die, in the lesson's verdict?** → **Unkept — not of hard questions**
