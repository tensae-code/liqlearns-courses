# DELETE — removing records safely

## Do it first

A student has left the school for good; their record must go. A department is being closed; it must go too — but teachers belong to it. Two removals, two different dangers. Decide the order for the second one before you read: do you remove the department first, or its teachers first? Hold your answer.

## Sub lesson 1 — DELETE removes records — the table stands

**DELETE** removes **records** from a table but **leaves the table structure standing** — the empty table, columns and key intact, ready for new records. It is not DROP TABLE.

```sql
DELETE FROM Student WHERE StudentID = 103;
```

It can target rows by a condition, or remove **all rows** — written with or without the `*` form (`DELETE * FROM Student;` / `DELETE FROM Student;`). It **cannot delete only some fields of a record**: a record goes whole, or not at all.


## Sub lesson 2 — Name the record by its primary key

The caution: **name the record by its primary key** in the WHERE. Other fields may repeat — two students share a name, two teachers share a salary — and a WHERE built on a repeating field can cost the **wrong record**.

The worked answer set (teacher guide — evidence) deletes one record by ID, and separately removes all records — both shapes deliberate, both named exactly.


## Sub lesson 3 — Delete the many side first

In a **one-to-many** relationship, **delete the many-side records before deleting the one-side record they belong to**: to close a department, first delete its **Students, Teachers and Courses** (the many side), then the department.

Deleting from a **child table does not harm its parent** — removing a course never wounds its department. The danger runs the other way: a one-side record removed while many-side records still point at it leaves orphans. Many side first, always.


## Say it to your companion

Tell your companion the order for closing a department, and what orphans if the order is reversed.

## Do It Yourself

1. Write the DELETE for the student with StudentID 103.
2. Write the all-rows DELETE for a practice table, both forms.
3. A WHERE says DELETE FROM Student WHERE FirstName = 'Aster'; and two Asters exist. Explain the danger and rewrite it safely.
