# UPDATE — change rows, and never forget WHERE

## Do it first

A school raises pay: every teacher earning under 10,000 birr goes to 15,000. The Teacher table stands filled. You may write ONE statement. Write down, before any syntax: which column changes, to what, and — the dangerous part — exactly which rows it should touch. If your sentence cannot say 'only those rows', it is not safe yet.

## Sub lesson 1 — The form — SET and WHERE

**UPDATE** changes values in **existing rows** — it adds no rows and removes none. Its form: name the table, **SET** one or more columns to new values, and let a **WHERE** condition choose the rows:

```sql
UPDATE Teacher
SET Salary = 15000
WHERE Salary < 10000;
```

That is the book's worked raise: **every teacher salary below 10,000 is raised to 15,000** — the rows above the line are untouched, because WHERE did not choose them.


## Sub lesson 2 — Widening the WHERE — one statement, many rows

One statement can change a whole chosen group: to update **all female teachers' salary** in one statement, widen the WHERE to the group:

```sql
UPDATE Teacher
SET Salary = 16000
WHERE Sex = 'F';
```

The worked answer set (teacher guide — evidence) runs the same shape on single named records too — one student, one teacher, changed by their key in the WHERE. The pattern never changes: SET says *what becomes true*, WHERE says *for whom*.


## Sub lesson 3 — The warning — no WHERE means every row

Omit WHERE, and the update touches **every row in the table**. The book warns by example; the guide's answer set shows the deliberate use — an UPDATE with no condition setting **every student's grade level at once** — which is right only when *every* really is the intent.

So the habit: before running any UPDATE, read its WHERE aloud. If there is none, stop and ask whether every row in the table should truly change.


## Say it to your companion

Tell your companion what happens to the Teacher table if the raise statement loses its WHERE line.

## Do It Yourself

1. Write the UPDATE that sets every female teacher's salary to 16,000.
2. Write an UPDATE changing one student's grade level, choosing the row by StudentID.
3. A statement reads UPDATE Teacher SET Salary = 15000; with no WHERE. Predict its result, row by row.
