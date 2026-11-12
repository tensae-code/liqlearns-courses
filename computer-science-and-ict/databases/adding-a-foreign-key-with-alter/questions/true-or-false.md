# Adding a foreign key with ALTER — true or false

Say true or false.

**1. (Sub lesson 1)** ADD FOREIGN KEY (C_Department) makes D_Number a foreign key.
**Answer: False** — C_Department is the foreign key; D_Number is the primary key it references.

**2. (Sub lesson 1)** A relationship can be created after both tables already exist.
**Answer: True** — that is exactly what this ALTER does.

**3. (Sub lesson 2)** Adding the foreign key with ALTER rewrites all the records in COURSE.
**Answer: False** — it adds the link (structure), not new record values.

**4. (Sub lesson 2)** One ALTER statement per link is always the only possible form.
**Answer: False** — the guide also gives a combined form for two links.
