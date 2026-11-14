# Iterative or Recursive — Choosing the Approach — true or false

Say true or false, and fix the false ones in your own words.

**1. (Sub lesson 1) True or false: Explicitly — in variables the programmer manages, step by step**
**Answer: True**

**2. (Sub lesson 1) True or false: Explicitly — in variables the programmer manages, step by step** — as the answer to: How does a recursive solution keep its state?
**Answer: False — Implicitly — in the chain of calls, each call's variables waiting on the stack**

**3. (Sub lesson 1) True or false: Where the problem defines itself — factorial, tree walks, divide-and-conquer**
**Answer: True**

**4. (Sub lesson 1) True or false: Where the problem defines itself — factorial, tree walks, divide-and-conquer** — as the answer to: What does iteration show that recursion hides?
**Answer: False — Its machinery — the state and step order in the open**

**5. (Sub lesson 1) True or false: Yes — they differ in bookkeeping, cost and reading, not in results**
**Answer: True**

**6. (Sub lesson 2) True or false: Yes — they differ in bookkeeping, cost and reading, not in results** — as the answer to: What does recursion pay in memory?
**Answer: False — A stack frame for every pending call — deep recursions can overflow the stack**

**7. (Sub lesson 2) True or false: Overlapping subcalls — the same values recomputed exponentially often**
**Answer: True**

**8. (Sub lesson 2) True or false: Overlapping subcalls — the same values recomputed exponentially often** — as the answer to: When should you recurse?
**Answer: False — When the problem is self-similar, division is clean and depth is modest**

**9. (Sub lesson 2) True or false: When depth is huge, overlap would repeat work, or the loop is simply plain**
**Answer: True**

**10. (Sub lesson 2) True or false: When depth is huge, overlap would repeat work, or the loop is simply plain** — as the answer to: By what is the choice judged?
**Answer: False — By the problem's structure — not by fashion**
