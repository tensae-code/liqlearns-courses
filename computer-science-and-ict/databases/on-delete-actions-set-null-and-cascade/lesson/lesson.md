# ON DELETE Actions — SET NULL and CASCADE

## Do it first

Deleting a parent is the dangerous mirror of updating one: the children still point at it. Kuwait's relational year names what may happen to them — and makes the pupil choose it in advance, in the table's own declaration. This lesson is the delete actions.

## Sub lesson 1 — SET NULL — the child stays, the pointing ends

**ON DELETE SET NULL** answers a parent's deletion by **emptying the children's foreign key**: the child rows **stay** — a student remains a student — but their link now points at **nothing (NULL)**, honestly unassigned until a new parent is given. It fits children whose existence does not depend on the parent: the record is real, only its belonging is ended.

In your mind's eye: sET NULL — the child stays, the pointing ends.

## Sub lesson 2 — CASCADE and the other alternatives — choosing the fate in advance

**ON DELETE CASCADE** answers with the opposite mercy: the children are **deleted with the parent** — right where a child is meaningless alone (an order's lines without the order). The remaining alternatives refuse or restrict the deletion while children exist. The lesson's discipline is that the fate is **chosen when the table is created**, written into its FOREIGN KEY declaration — not improvised on the day a parent must go.

In your mind's eye: cASCADE and the other alternatives — choosing the fate in advance.

## Say it to your companion

Tell your companion, in your own words: **ON DELETE SET NULL** answers a parent's deletion by **emptying the children's foreign key**: the child rows **stay** — a student remains a student — but their link now points at **nothing (NULL)**, honestly unassigned until a new parent is given. It fits children whose existence does not depend on the parent: the record is real, only its belonging is ended. **ON DELETE CASCADE** answers with the opposite mercy: the children are **deleted with the parent** — right where a child is meaningless alone (an order's lines without the order). The remaining alternatives refuse or restrict the deletion while children exist. The lesson's discipline is that the fate is **chosen when the table is created**, written into its FOREIGN KEY declaration — not improvised on the day a parent must go. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: What happens to child rows when their parent is deleted. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Empties their foreign key — the rows stay, pointing at nothing. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Where the child's existence does not depend on the parent. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Deletes the children with the parent. Do this with a real example of your own and write or say how you know it is right.
