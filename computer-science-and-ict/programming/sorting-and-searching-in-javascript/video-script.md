# Video script — Sorting and Searching in JavaScript

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A JavaScript **sort** works on an **array** with nested loops. **Bubble sort** in code is the paper method written down: an outer loop for passes, an inner loop comparing array[j] with array[j+1], and a swap through a temporary variable (let t = a[j]; a[j] = a[j+1]; a[j+1] = t;). **Selection sort** searches each pass for the **smallest remaining** value and swaps it into place — the search-inside-sort weaving, in code. JavaScript also has a built-in sort method, but Malaysia codes the methods by hand first: the built-in is trusted only after its hand-written ancestors are understood.
**Binary search** in JavaScript tracks low, high and mid over the array's indexes, looping while low <= high, comparing array[mid] with the target and halving the field exactly as the pseudocode did. The code returns the **index** where the target was found, or −1 for not found — the convention JavaScript programs use. The lesson's point closes the strand: pseudocode, flowchart and JavaScript are three writings of one algorithm; Malaysia moves between them to prove the algorithm is the thinking, and the language only its clothing.
