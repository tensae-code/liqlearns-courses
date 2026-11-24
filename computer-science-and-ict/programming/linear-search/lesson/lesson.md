# Linear Search

## Do it first

The simplest honest search: start at the first item, check it, move to the next. Malaysia's algorithms chapter formalises it in pseudocode and flowchart. In this lesson you work linear search exactly — and learn when its simplicity is its strength.

## Sub lesson 1 — One by one, from the start

**Linear search** checks the items **in order, one at a time**, comparing each with the **target**. The hunt stops the moment an item **matches** — its position is the answer. If the end of the list is reached with no match, the answer is **not found**. The list need **not be in order** — linear search works on any list, because it looks at everything until it succeeds. Its cost is just as plain: in the worst case it checks **every item** — the target last, or absent.

In your mind's eye: one by one, from the start.

## Sub lesson 2 — Linear search in pseudocode and flowchart

Malaysia's pseudocode runs: set position to 1 and found to false; **repeat** — if the item at position equals the target, set found to true, else move position on by 1 — **until** found is true or position passes the list's end; then report the position or 'not found'. The flowchart draws the same shape: a loop with the comparison as its decision diamond, one exit on a match, one exit at the list's end. The two exits are the lesson's mark: every correct linear search has **both** — a search that can only exit on success is a trap, not an algorithm.

In your mind's eye: linear search in pseudocode and flowchart.

## Say it to your companion

Tell your companion, in your own words: **Linear search** checks the items **in order, one at a time**, comparing each with the **target**. The hunt stops the moment an item **matches** — its position is the answer. If the end of the list is reached with no match, the answer is **not found**. The list need **not be in order** — linear search works on any list, because it looks at everything until it succeeds. Its cost is just as plain: in the worst case it checks **every item** — the target last, or absent. Malaysia's pseudocode runs: set position to 1 and found to false; **repeat** — if the item at position equals the target, set found to true, else move position on by 1 — **until** found is true or position passes the list's end; then report the position or 'not found'. The flowchart draws the same shape: a loop with the comparison as its decision diamond, one exit on a match, one exit at the list's end. The two exits are the lesson's mark: every correct linear search has **both** — a search that can only exit on success is a trap, not an algorithm. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: In order, one item at a time, comparing each with the target. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The moment an item matches — or the list ends. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Not found. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Position (starting at 1) and found (starting false). Do this with a real example of your own and write or say how you know it is right.
