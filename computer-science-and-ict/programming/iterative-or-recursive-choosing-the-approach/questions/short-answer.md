# Iterative or Recursive — Choosing the Approach — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) How does an iterative solution keep its state?**
**Answer: Explicitly — in variables the programmer manages, step by step**

**2. (Sub lesson 1) How does a recursive solution keep its state?**
**Answer: Implicitly — in the chain of calls, each call's variables waiting on the stack**

**3. (Sub lesson 1) Where does recursion read most naturally?**
**Answer: Where the problem defines itself — factorial, tree walks, divide-and-conquer**

**4. (Sub lesson 1) What does iteration show that recursion hides?**
**Answer: Its machinery — the state and step order in the open**

**5. (Sub lesson 1) Do the two engines give the same answers?**
**Answer: Yes — they differ in bookkeeping, cost and reading, not in results**

**6. (Sub lesson 2) What does recursion pay in memory?**
**Answer: A stack frame for every pending call — deep recursions can overflow the stack**

**7. (Sub lesson 2) What is the naive Fibonacci's flaw?**
**Answer: Overlapping subcalls — the same values recomputed exponentially often**

**8. (Sub lesson 2) When should you recurse?**
**Answer: When the problem is self-similar, division is clean and depth is modest**

**9. (Sub lesson 2) When should you iterate?**
**Answer: When depth is huge, overlap would repeat work, or the loop is simply plain**

**10. (Sub lesson 2) By what is the choice judged?**
**Answer: By the problem's structure — not by fashion**
