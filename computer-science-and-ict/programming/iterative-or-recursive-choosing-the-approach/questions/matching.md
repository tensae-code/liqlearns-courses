# Iterative or Recursive — Choosing the Approach — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) How does an iterative solution keep its state?** → **Explicitly — in variables the programmer manages, step by step**

**2. (Sub lesson 1) How does a recursive solution keep its state?** → **Implicitly — in the chain of calls, each call's variables waiting on the stack**

**3. (Sub lesson 1) Where does recursion read most naturally?** → **Where the problem defines itself — factorial, tree walks, divide-and-conquer**

**4. (Sub lesson 1) What does iteration show that recursion hides?** → **Its machinery — the state and step order in the open**

**5. (Sub lesson 1) Do the two engines give the same answers?** → **Yes — they differ in bookkeeping, cost and reading, not in results**

**6. (Sub lesson 2) What does recursion pay in memory?** → **A stack frame for every pending call — deep recursions can overflow the stack**

**7. (Sub lesson 2) What is the naive Fibonacci's flaw?** → **Overlapping subcalls — the same values recomputed exponentially often**

**8. (Sub lesson 2) When should you recurse?** → **When the problem is self-similar, division is clean and depth is modest**

**9. (Sub lesson 2) When should you iterate?** → **When depth is huge, overlap would repeat work, or the loop is simply plain**

**10. (Sub lesson 2) By what is the choice judged?** → **By the problem's structure — not by fashion**
