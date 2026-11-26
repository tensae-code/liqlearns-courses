# Binary Trees

## Do it first

binary trees — the tree where every node has at most two children, left and right, and the ways of walking it (Vietnam Grade 12 specialist, CS)

## Sub lesson 1 — At most two children — left and right

A **binary tree** (cây nhị phân) is a tree where every node has **at most two children**, and the two places have names — **left child** and **right child** — so a node with only a left child is a different tree from the same node with only a right one. A node with no children is a **leaf**; a child place left empty is an **empty subtree**, and empty subtrees count in the structure. Vietnam's data-structures book begins here, because the searches and traversals that follow all stand on this two-place discipline.

In your mind's eye: at most two children — left and right.

[Picture 46768 — at most two children — left and right]

## Sub lesson 2 — Holding a binary tree — links and arrays

A program holds a binary tree two ways. By **links**: each node stores its value and references to its left and right children (nothing where a child is absent). By **array**: the root sits at index 1, and the children of the node at index *i* sit at **2i** and **2i+1** — neat for complete trees, wasteful for crooked ones. The tree's measures come with it: its **height** (the longest root-to-leaf path) decides how much work a walk down it can cost.

In your mind's eye: holding a binary tree — links and arrays.

[Picture 46769 — holding a binary tree — links and arrays]

## Say it to your companion

Tell your companion, in your own words: A **binary tree** (cây nhị phân) is a tree where every node has **at most two children**, and the two places have names — **left child** and **right child** — so a node with only a left child is a different tree from the same node with only a right one. A node with no children is a **leaf**; a child place left empty is an **empty subtree**, and empty subtrees count in the structure. Vietnam's data-structures book begins here, because the searches and traversals that follow all stand on this two-place discipline. A program holds a binary tree two ways. By **links**: each node stores its value and references to its left and right children (nothing where a child is absent). By **array**: the root sits at index 1, and the children of the node at index *i* sit at **2i** and **2i+1** — neat for complete trees, wasteful for crooked ones. The tree's measures come with it: its **height** (the longest root-to-leaf path) decides how much work a walk down it can cost. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: At most two Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Left child and right child Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — the places have names, so the trees differ Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A node with no children Do this with a real example of your own and write or say how you know it is right.
