# Iterative or Recursive — Choosing the Approach — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) How does an iterative solution keep its state?**
a) Explicitly — in variables the programmer manages, step by step  b) Implicitly — in the chain of calls, each call's variables waiting on the stack  c) Where the problem defines itself — factorial, tree walks, divide-and-conquer  d) Its machinery — the state and step order in the open
**Answer: a**

**2. (Sub lesson 1) How does a recursive solution keep its state?**
a) Implicitly — in the chain of calls, each call's variables waiting on the stack  b) Where the problem defines itself — factorial, tree walks, divide-and-conquer  c) Its machinery — the state and step order in the open  d) Yes — they differ in bookkeeping, cost and reading, not in results
**Answer: a**

**3. (Sub lesson 1) Where does recursion read most naturally?**
a) Where the problem defines itself — factorial, tree walks, divide-and-conquer  b) Its machinery — the state and step order in the open  c) Yes — they differ in bookkeeping, cost and reading, not in results  d) A stack frame for every pending call — deep recursions can overflow the stack
**Answer: a**

**4. (Sub lesson 1) What does iteration show that recursion hides?**
a) Its machinery — the state and step order in the open  b) Yes — they differ in bookkeeping, cost and reading, not in results  c) A stack frame for every pending call — deep recursions can overflow the stack  d) Overlapping subcalls — the same values recomputed exponentially often
**Answer: a**

**5. (Sub lesson 1) Do the two engines give the same answers?**
a) Yes — they differ in bookkeeping, cost and reading, not in results  b) A stack frame for every pending call — deep recursions can overflow the stack  c) Overlapping subcalls — the same values recomputed exponentially often  d) When the problem is self-similar, division is clean and depth is modest
**Answer: a**

**6. (Sub lesson 2) What does recursion pay in memory?**
a) A stack frame for every pending call — deep recursions can overflow the stack  b) Overlapping subcalls — the same values recomputed exponentially often  c) When the problem is self-similar, division is clean and depth is modest  d) When depth is huge, overlap would repeat work, or the loop is simply plain
**Answer: a**

**7. (Sub lesson 2) What is the naive Fibonacci's flaw?**
a) Overlapping subcalls — the same values recomputed exponentially often  b) When the problem is self-similar, division is clean and depth is modest  c) When depth is huge, overlap would repeat work, or the loop is simply plain  d) By the problem's structure — not by fashion
**Answer: a**

**8. (Sub lesson 2) When should you recurse?**
a) When the problem is self-similar, division is clean and depth is modest  b) When depth is huge, overlap would repeat work, or the loop is simply plain  c) By the problem's structure — not by fashion  d) Explicitly — in variables the programmer manages, step by step
**Answer: a**

**9. (Sub lesson 2) When should you iterate?**
a) When depth is huge, overlap would repeat work, or the loop is simply plain  b) By the problem's structure — not by fashion  c) Explicitly — in variables the programmer manages, step by step  d) Implicitly — in the chain of calls, each call's variables waiting on the stack
**Answer: a**

**10. (Sub lesson 2) By what is the choice judged?**
a) By the problem's structure — not by fashion  b) Explicitly — in variables the programmer manages, step by step  c) Implicitly — in the chain of calls, each call's variables waiting on the stack  d) Where the problem defines itself — factorial, tree walks, divide-and-conquer
**Answer: a**
