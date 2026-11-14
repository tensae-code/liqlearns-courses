# ON UPDATE CASCADE — Keeping Related Tables in Step

## Do it first

Related tables make a promise: the child's foreign key names a real parent. What happens when the parent's key changes? Kuwait's relational year answers with a switch and a rule. This lesson is keeping related tables in step when a parent is updated.

## Sub lesson 1 — PRAGMA foreign_keys — the switch that makes rules real

In SQLite, foreign-key rules sleep until woken: the connection must run **PRAGMA foreign_keys = ON** before the database will **enforce** the links between tables. Kuwait teaches the switch by name because without it the course's referential actions are wishes — with it, the database itself refuses orphan children and applies the update rules the tables declare. The switch is per connection: every program that wants the promise kept must turn it on.

[Picture — PRAGMA foreign_keys — the switch that makes rules real]

## Sub lesson 2 — ON UPDATE CASCADE against NO ACTION

A parent table's key can be **updated** — a region's code corrected. **ON UPDATE CASCADE** answers: the change **cascades** — every child's foreign key is updated to match, automatically, so the family stays in step. **NO ACTION** answers the opposite: the update is **refused** while children still point at the old key, protecting the link by blocking the change. Choosing between them is design: cascade where the key is a mere label the children must follow; no action where a change should never slip through silently.

[Picture — ON UPDATE CASCADE against NO ACTION]

## Say it to your companion

Tell your companion, in your own words: In SQLite, foreign-key rules sleep until woken: the connection must run **PRAGMA foreign_keys = ON** before the database will **enforce** the links between tables. Kuwait teaches the switch by name because without it the course's referential actions are wishes — with it, the database itself refuses orphan children and applies the update rules the tables declare. The switch is per connection: every program that wants the promise kept must turn it on. A parent table's key can be **updated** — a region's code corrected. **ON UPDATE CASCADE** answers: the change **cascades** — every child's foreign key is updated to match, automatically, so the family stays in step. **NO ACTION** answers the opposite: the update is **refused** while children still point at the old key, protecting the link by blocking the change. Choosing between them is design: cascade where the key is a mere label the children must follow; no action where a change should never slip through silently. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Switches on the database's enforcement of foreign-key links. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Wishes — the links are declared but not enforced. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Per connection — every program must turn it on. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Updating a parent table's key. Do this with a real example of your own and write or say how you know it is right.
