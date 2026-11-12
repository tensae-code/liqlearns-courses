# Adding a foreign key with ALTER

## Do it first

Both tables are standing — DEPARTMENT, and COURSE with a plain C_Department column that points nowhere. The bridge was not built at creation time. Can it be built now, without touching a single record? Write down what the bridge statement must name: the table, the column, the table it points to, and that table's key. Then compare with the real statement.

## Sub lesson 1 — The statement, part by part

```sql
ALTER TABLE COURSE
ADD FOREIGN KEY (C_Department)
REFERENCES DEPARTMENT (D_Number);
```

Read it as a sentence: *alter COURSE — add a foreign key on (C_Department) — referencing DEPARTMENT's (D_Number)*. The column named first is the foreign key; the column in REFERENCES is the primary key it must match.

The two columns must still share a data type — C_Department and D_Number are both CHAR(10) from the earlier build. ALTER adds the link; it does not forgive a mismatch.


## Sub lesson 2 — When the late link is the right tool

Use it when the tables were created separately — perhaps by different people, or before the relationship was decided — and now must work as one database.

The worked answer set (teacher guide — evidence) links a Grade table to Student and to Teacher exactly this way, given both as one combined statement and as two separate ALTER statements — one link per statement, or the links listed together where the system allows.


## Say it to your companion

Tell your companion the four things the bridge statement names, in order.

## Do It Yourself

1. Write the ALTER that links COURSE to DEPARTMENT.
2. Write, in the same shape, an ALTER linking MarkList's Sid to Students' Sid.
3. Say why this statement fails if C_Department is CHAR(15).
