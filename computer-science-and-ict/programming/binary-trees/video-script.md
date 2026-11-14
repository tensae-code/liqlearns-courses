# Video script — Binary Trees

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **binary tree** (cây nhị phân) is a tree where every node has **at most two children**, and the two places have names — **left child** and **right child** — so a node with only a left child is a different tree from the same node with only a right one. A node with no children is a **leaf**; a child place left empty is an **empty subtree**, and empty subtrees count in the structure. Vietnam's data-structures book begins here, because the searches and traversals that follow all stand on this two-place discipline.
A program holds a binary tree two ways. By **links**: each node stores its value and references to its left and right children (nothing where a child is absent). By **array**: the root sits at index 1, and the children of the node at index *i* sit at **2i** and **2i+1** — neat for complete trees, wasteful for crooked ones. The tree's measures come with it: its **height** (the longest root-to-leaf path) decides how much work a walk down it can cost.
