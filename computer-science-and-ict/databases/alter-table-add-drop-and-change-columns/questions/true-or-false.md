# ALTER TABLE — add, drop and change columns — true or false

Say true or false.

**1. (Sub lesson 1)** ALTER TABLE deletes the table's records whenever it adds a column.
**Answer: False** — an add changes structure; the records stay.

**2. (Sub lesson 2)** ALTER COLUMN can change a column's data type.
**Answer: True** — that is the direct mismatch repair.

**3. (Sub lesson 2)** Drop-and-re-add and direct ALTER COLUMN are identical in effect on stored values.
**Answer: False** — drop-and-re-add loses the column's values; the direct alter keeps them.

**4. (Sub lesson 3)** A primary key can only be set during CREATE TABLE, never later.
**Answer: False** — ALTER TABLE can add one afterwards, as with TEACHER.
