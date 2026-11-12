# ALTER TABLE — add, drop and change columns

## Do it first

Your COURSE table is built — but its C_Department is CHAR(15) while DEPARTMENT's D_Number is CHAR(10). The link will not hold. Do you demolish the table and start again? No. There is a command that changes a standing table. Guess its name from the job — then check.

## Sub lesson 1 — Add a column, drop a column

**ALTER TABLE** modifies an existing table. Its shapes in this lesson: **add a column**, **drop a column**, or **change a column's definition**.

```sql
ALTER TABLE COURSE ADD COLUMN Room CHAR(10);
ALTER TABLE COURSE DROP COLUMN Room;
```

The table keeps its records through an add or a drop of an ordinary column — the structure changes around the data.


## Sub lesson 2 — Change a column — fixing the type mismatch

The mismatch: **C_Department CHAR(15)** against **D_Number CHAR(10)**. Two repairs, both ALTER:

1. **Alter the column directly** to the matching type:
```sql
ALTER TABLE COURSE ALTER COLUMN C_Department CHAR(10);
```

2. Or **drop the column and re-add it** with the right type. The direct alter is one statement; the drop-and-re-add is two, and the column's stored values go with the drop — choose the direct alter when the data matters.


## Sub lesson 3 — Add a missed primary key afterwards

A table built without its key can be repaired too — the worked example adds the key to the TEACHER table after creation:

```sql
ALTER TABLE TEACHER ADD PRIMARY KEY (teacher_id);
```

The worked answer set (teacher guide — evidence) uses the same command family to change a column's type, add a column, and add keys after the fact — ALTER is the repair kit for tables already standing.


## Say it to your companion

Tell your companion the three things ALTER TABLE can do, and which repair you would choose for the mismatch — and why.

## Do It Yourself

1. Write ALTER statements to add an Email CHAR(40) column to TEACHER, then drop it.
2. Fix C_Department CHAR(15) with one direct statement.
3. Write the statement that makes teacher_id TEACHER's primary key.
