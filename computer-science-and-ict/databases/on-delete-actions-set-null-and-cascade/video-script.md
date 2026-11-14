# Video script — ON DELETE Actions — SET NULL and CASCADE

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**ON DELETE SET NULL** answers a parent's deletion by **emptying the children's foreign key**: the child rows **stay** — a student remains a student — but their link now points at **nothing (NULL)**, honestly unassigned until a new parent is given. It fits children whose existence does not depend on the parent: the record is real, only its belonging is ended.
**ON DELETE CASCADE** answers with the opposite mercy: the children are **deleted with the parent** — right where a child is meaningless alone (an order's lines without the order). The remaining alternatives refuse or restrict the deletion while children exist. The lesson's discipline is that the fate is **chosen when the table is created**, written into its FOREIGN KEY declaration — not improvised on the day a parent must go.
