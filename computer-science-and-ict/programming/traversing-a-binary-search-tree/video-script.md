# Video script — Traversing a Binary Search Tree

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **traversal** visits every node of a tree in a fixed order, defined recursively on the root and its subtrees. **Inorder**: walk the left subtree, **visit the root**, walk the right subtree. **Preorder**: visit the root **first**, then left, then right. **Postorder**: visit the root **last**, after both subtrees. The three walks are one recursion with the visit moved — Vietnam's specialist book teaches them together on the search tree, where the difference stops being notation and becomes information.
On a **binary search tree**, the inorder walk has a gift: because every left subtree holds smaller values and every right subtree larger ones, inorder visits the values **in sorted order** — the tree can be **read out sorted** without any sorting at all, which is why the book calls the BST a structure for 'sorting and searching' together. Preorder and postorder earn their keep elsewhere: preorder copies a tree's shape, postorder evaluates expressions and safely deletes — children before the parent that holds them.
