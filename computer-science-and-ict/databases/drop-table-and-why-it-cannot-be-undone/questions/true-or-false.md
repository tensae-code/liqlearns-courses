# DROP TABLE — and why it cannot be undone — true or false

Say true or false.

**1. (Sub lesson 1)** DROP TABLE leaves an empty table standing, ready for new records.
**Answer: False** — that is DELETE's effect; DROP removes the table itself.

**2. (Sub lesson 1)** DROP TABLE is a DDL command.
**Answer: True** — it defines structure — by removing it.

**3. (Sub lesson 2)** Access asks 'are you sure?' and keeps a backup of every dropped table automatically, in this unit's teaching.
**Answer: False** — the unit teaches no such safety net: the caution is that it cannot be got back.

**4. (Sub lesson 2)** Practising DROP on a table you built only for practice is the safe way to learn it.
**Answer: True** — filled, needed tables are not practice material.
