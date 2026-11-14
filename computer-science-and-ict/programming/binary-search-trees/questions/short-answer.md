# Binary Search Trees — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What rule rules a binary search tree?**
**Answer: At every node, the left subtree holds smaller values and the right subtree larger ones**

**2. (Sub lesson 1) How is a value searched for?**
**Answer: Compare with the node: smaller goes left, larger goes right, equal is found**

**3. (Sub lesson 1) What is discarded at each step?**
**Answer: Half the remaining tree**

**4. (Sub lesson 1) What can a BST do that a sorted list cannot easily do?**
**Answer: Grow — new values are inserted into their place in the structure**

**5. (Sub lesson 1) What is the root's role in a search?**
**Answer: The first comparison — its value sends the search left or right**

**6. (Sub lesson 2) How is a value inserted?**
**Answer: Walk the search path and attach it as a leaf where the path runs out**

**7. (Sub lesson 2) How is a leaf deleted?**
**Answer: It is simply removed**

**8. (Sub lesson 2) How is a node with two children deleted?**
**Answer: Its value is replaced by a value from below — its successor — so the ordering rule survives**

**9. (Sub lesson 2) What does the tree's speed depend on?**
**Answer: Its shape — a balanced tree is fast, a crooked line is a list**

**10. (Sub lesson 2) What insertion order ruins the shape?**
**Answer: Already-sorted values, one after another**
