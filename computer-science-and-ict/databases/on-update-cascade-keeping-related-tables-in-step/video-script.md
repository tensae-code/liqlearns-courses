# Video script — ON UPDATE CASCADE — Keeping Related Tables in Step

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In SQLite, foreign-key rules sleep until woken: the connection must run **PRAGMA foreign_keys = ON** before the database will **enforce** the links between tables. Kuwait teaches the switch by name because without it the course's referential actions are wishes — with it, the database itself refuses orphan children and applies the update rules the tables declare. The switch is per connection: every program that wants the promise kept must turn it on.
A parent table's key can be **updated** — a region's code corrected. **ON UPDATE CASCADE** answers: the change **cascades** — every child's foreign key is updated to match, automatically, so the family stays in step. **NO ACTION** answers the opposite: the update is **refused** while children still point at the old key, protecting the link by blocking the change. Choosing between them is design: cascade where the key is a mere label the children must follow; no action where a change should never slip through silently.
