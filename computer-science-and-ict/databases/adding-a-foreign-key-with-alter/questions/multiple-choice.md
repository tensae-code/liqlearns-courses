# Adding a foreign key with ALTER — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** The statement alters which table?
a) DEPARTMENT  b) COURSE — the one holding the foreign key  c) both at once  d) the database itself
**Answer: b) COURSE — the one holding the foreign key** — you alter the table that holds the borrowed key.

**2. (Sub lesson 1)** REFERENCES DEPARTMENT (D_Number) names —
a) a new column  b) the other table and its primary key  c) a value to insert  d) the query to run
**Answer: b) the other table and its primary key** — the target table and its key column.

**3. (Sub lesson 1)** For the ALTER to succeed, C_Department and D_Number must —
a) have the same name  b) share a data type  c) both be primary keys  d) hold the same records
**Answer: b) share a data type** — the matching-type rule still applies.

**4. (Sub lesson 2)** A late foreign key is the right tool when —
a) the tables do not exist yet  b) the tables were created separately and must now link  c) records must be deleted  d) a query is too slow
**Answer: b) the tables were created separately and must now link** — it links standing tables without rebuilding.

**5. (Sub lesson 2)** Grade must link to Student and to Teacher. The answer set gives this as —
a) one combined statement, or two separate ALTERs  b) a single SELECT  c) a DROP and rebuild only  d) impossible
**Answer: a) one combined statement, or two separate ALTERs** — both forms are keyed in the guide.

**6. (Sub lesson 2)** ALTER … ADD FOREIGN KEY changes —
a) the records in both tables  b) the structure — it adds the link  c) the primary key's type  d) nothing at all
**Answer: b) the structure — it adds the link** — it is a DDL structure change.
