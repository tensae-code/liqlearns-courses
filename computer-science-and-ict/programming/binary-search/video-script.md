# Video script — Binary Search

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Binary search** works only on an **ordered list**. Check the **middle** item: if it is the target, the hunt ends. If the target is **smaller**, it can only live in the **left half** — the right half is discarded whole. If **larger**, the left half is discarded. The surviving half is searched the same way — new middle, new halving — until the target is found or the field shrinks to **nothing**, which answers 'not found'. Each check halves the field: 1,000 items need at most about 10 checks, against linear search's 1,000.
The pseudocode tracks **low** and **high** — the ends of the surviving field — and repeats while low ≤ high: middle = (low + high) ÷ 2 (whole number); if the middle item is the target, report it and stop; if the target is smaller, set high = middle − 1; else set low = middle + 1. The flowchart's shape is a loop with a **three-way decision** at its heart. Malaysia's warning is drawn with it: run binary search on an **unordered** list and it will throw away the half that holds the target — the method's speed is bought entirely by the order it demands.
