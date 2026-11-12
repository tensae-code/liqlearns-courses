# DELETE — removing records safely — true or false

Say true or false.

**1. (Sub lesson 1)** DELETE * FROM Student; and DELETE FROM Student; are both all-rows forms.
**Answer: True** — the book gives the removal of all rows with or without the * form.

**2. (Sub lesson 1)** DELETE and DROP TABLE have the same effect.
**Answer: False** — DELETE leaves the structure; DROP removes the table.

**3. (Sub lesson 2)** A WHERE on a repeating field is as safe as one on the primary key.
**Answer: False** — it can match — and delete — the wrong records.

**4. (Sub lesson 3)** Deleting the one-side department first is safe if done quickly.
**Answer: False** — many-side records would be left pointing at a gone parent — orphans.
