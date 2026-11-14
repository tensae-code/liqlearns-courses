# Traversing a Binary Search Tree

## Do it first

traversing a binary search tree — walking every node in inorder, preorder and postorder, and why the inorder walk reads the values out already sorted (Vietnam Grade 12 specialist, CS)

## Sub lesson 1 — Three walks — the visit comes before, between, or after

A **traversal** visits every node of a tree in a fixed order, defined recursively on the root and its subtrees. **Inorder**: walk the left subtree, **visit the root**, walk the right subtree. **Preorder**: visit the root **first**, then left, then right. **Postorder**: visit the root **last**, after both subtrees. The three walks are one recursion with the visit moved — Vietnam's specialist book teaches them together on the search tree, where the difference stops being notation and becomes information.

[Picture — Three walks — the visit comes before, between, or after]

## Sub lesson 2 — Inorder reads sorted — the search tree pays its promise

On a **binary search tree**, the inorder walk has a gift: because every left subtree holds smaller values and every right subtree larger ones, inorder visits the values **in sorted order** — the tree can be **read out sorted** without any sorting at all, which is why the book calls the BST a structure for 'sorting and searching' together. Preorder and postorder earn their keep elsewhere: preorder copies a tree's shape, postorder evaluates expressions and safely deletes — children before the parent that holds them.

[Picture — Inorder reads sorted — the search tree pays its promise]

## Say it to your companion

Tell your companion, in your own words: A **traversal** visits every node of a tree in a fixed order, defined recursively on the root and its subtrees. **Inorder**: walk the left subtree, **visit the root**, walk the right subtree. **Preorder**: visit the root **first**, then left, then right. **Postorder**: visit the root **last**, after both subtrees. The three walks are one recursion with the visit moved — Vietnam's specialist book teaches them together on the search tree, where the difference stops being notation and becomes information. On a **binary search tree**, the inorder walk has a gift: because every left subtree holds smaller values and every right subtree larger ones, inorder visits the values **in sorted order** — the tree can be **read out sorted** without any sorting at all, which is why the book calls the BST a structure for 'sorting and searching' together. Preorder and postorder earn their keep elsewhere: preorder copies a tree's shape, postorder evaluates expressions and safely deletes — children before the parent that holds them. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Visiting every node of a tree in a fixed, recursive order Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Left subtree, root, right subtree Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Root first, then left subtree, then right subtree Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Left subtree, right subtree, root last Do this with a real example of your own and write or say how you know it is right.
