# ALTER TABLE — add, drop and change columns — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** ALTER TABLE is used to —
a) query records  b) modify an existing table's structure  c) delete all records  d) open Access
**Answer: b) modify an existing table's structure** — it adds, drops and changes columns on a standing table.

**2. (Sub lesson 1)** To add a Room column to COURSE you write —
a) INSERT COLUMN  b) ALTER TABLE COURSE ADD COLUMN Room CHAR(10)  c) CREATE COLUMN  d) SELECT ADD
**Answer: b) ALTER TABLE COURSE ADD COLUMN Room CHAR(10)** — ADD COLUMN under ALTER TABLE.

**3. (Sub lesson 2)** C_Department is CHAR(15), D_Number is CHAR(10). The one-statement fix is —
a) DROP TABLE COURSE  b) ALTER TABLE COURSE ALTER COLUMN C_Department CHAR(10)  c) DELETE FROM COURSE  d) UPDATE COURSE
**Answer: b) ALTER TABLE COURSE ALTER COLUMN C_Department CHAR(10)** — alter the column directly to the matching type.

**4. (Sub lesson 2)** Dropping and re-adding a filled column —
a) keeps its values  b) loses the column's stored values  c) doubles the values  d) locks the table
**Answer: b) loses the column's stored values** — the values are dropped with the column.

**5. (Sub lesson 3)** TEACHER was created with no key. To add one you write —
a) ALTER TABLE TEACHER ADD PRIMARY KEY (teacher_id)  b) INSERT PRIMARY KEY  c) CREATE KEY TEACHER  d) SELECT PRIMARY
**Answer: a) ALTER TABLE TEACHER ADD PRIMARY KEY (teacher_id)** — ALTER can add a missed primary key afterwards.

**6. (Sub lesson 3)** After ALTER adds a primary key, a duplicate key value —
a) is accepted silently  b) is refused, because a primary key is unique  c) deletes the table  d) becomes a foreign key
**Answer: b) is refused, because a primary key is unique** — uniqueness is the primary key's rule.
