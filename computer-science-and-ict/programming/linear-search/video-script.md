# Video script — Linear Search

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Linear search** checks the items **in order, one at a time**, comparing each with the **target**. The hunt stops the moment an item **matches** — its position is the answer. If the end of the list is reached with no match, the answer is **not found**. The list need **not be in order** — linear search works on any list, because it looks at everything until it succeeds. Its cost is just as plain: in the worst case it checks **every item** — the target last, or absent.
Malaysia's pseudocode runs: set position to 1 and found to false; **repeat** — if the item at position equals the target, set found to true, else move position on by 1 — **until** found is true or position passes the list's end; then report the position or 'not found'. The flowchart draws the same shape: a loop with the comparison as its decision diamond, one exit on a match, one exit at the list's end. The two exits are the lesson's mark: every correct linear search has **both** — a search that can only exit on success is a trap, not an algorithm.
