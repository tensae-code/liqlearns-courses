# Binary Search Trees

## Do it first

binary search trees — a binary tree kept under one rule (smaller to the left, larger to the right of every node), so searching, inserting and deleting all walk one path (Vietnam Grade 12 specialist, CS)

## Sub lesson 1 — The rule — smaller left, larger right

A **binary search tree** (cây tìm kiếm nhị phân) is a binary tree under one discipline: for **every node**, all values in its **left subtree are smaller** than the node's value, and all in its **right subtree are larger**. The rule turns the tree into a searching machine: to find a value, compare it with the root — smaller, go left; larger, go right; equal, found — discarding half the tree at each step, as binary search discards half a list, but in a structure that can also **grow**.

In your mind's eye: the rule — smaller left, larger right.

[Picture 46764 — the rule — smaller left, larger right]

## Sub lesson 2 — Insert, delete, and the shape's warning

**Inserting** walks the search path and attaches the new value as a leaf where the path runs out — the rule is never broken. **Deleting** is careful work: a leaf is simply removed; a node with one child is replaced by that child; a node with **two children** is replaced by a value from below (its successor) so the rule survives. The warning the book teaches: the tree's speed depends on its **shape** — insert sorted values and the 'tree' becomes a crooked line, no better than a list.

In your mind's eye: insert, delete, and the shape's warning.

[Picture 46765 — insert, delete, and the shape's warning]

## Say it to your companion

Tell your companion, in your own words: A **binary search tree** (cây tìm kiếm nhị phân) is a binary tree under one discipline: for **every node**, all values in its **left subtree are smaller** than the node's value, and all in its **right subtree are larger**. The rule turns the tree into a searching machine: to find a value, compare it with the root — smaller, go left; larger, go right; equal, found — discarding half the tree at each step, as binary search discards half a list, but in a structure that can also **grow**. **Inserting** walks the search path and attaches the new value as a leaf where the path runs out — the rule is never broken. **Deleting** is careful work: a leaf is simply removed; a node with one child is replaced by that child; a node with **two children** is replaced by a value from below (its successor) so the rule survives. The warning the book teaches: the tree's speed depends on its **shape** — insert sorted values and the 'tree' becomes a crooked line, no better than a list. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: At every node, the left subtree holds smaller values and the right subtree larger ones Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Compare with the node: smaller goes left, larger goes right, equal is found Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Half the remaining tree Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Grow — new values are inserted into their place in the structure Do this with a real example of your own and write or say how you know it is right.
