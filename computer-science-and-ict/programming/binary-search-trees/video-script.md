# Video script — Binary Search Trees

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **binary search tree** (cây tìm kiếm nhị phân) is a binary tree under one discipline: for **every node**, all values in its **left subtree are smaller** than the node's value, and all in its **right subtree are larger**. The rule turns the tree into a searching machine: to find a value, compare it with the root — smaller, go left; larger, go right; equal, found — discarding half the tree at each step, as binary search discards half a list, but in a structure that can also **grow**.
**Inserting** walks the search path and attaches the new value as a leaf where the path runs out — the rule is never broken. **Deleting** is careful work: a leaf is simply removed; a node with one child is replaced by that child; a node with **two children** is replaced by a value from below (its successor) so the rule survives. The warning the book teaches: the tree's speed depends on its **shape** — insert sorted values and the 'tree' becomes a crooked line, no better than a list.
