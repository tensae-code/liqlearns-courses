# INSERT examples — full rows and partial rows

## Do it first

A form arrives with one box left empty — the course's description was not written yet. The record must still be entered today. Can an INSERT leave a field out — and what will that field hold when you look at the table tomorrow? Decide first; the worked examples answer.

## Sub lesson 1 — The full COURSE record — form 1 worked

```sql
INSERT INTO COURSE VALUES (30, 'Databases', 'SQL basics', '105', 'CS101');
```

Read the values against the columns: **30** is an integer (contact hours), the names are strings, and **'105' is a string because that field is a string type** — the quotes follow the *field*, not the look of the value. 'CS101' fills the key, C_Code, last in the table's order.


## Sub lesson 2 — The DEPARTMENT record — form 2 worked

```sql
INSERT INTO DEPARTMENT (D_Name, D_Number, D_Location)
VALUES ('Computing', '105', 'Main campus');
```

Form 2 with all columns named behaves like form 1 — but the matching is by the names you wrote, so the order you *list* them in governs, and you can list them in a different order from the table's if the values follow your list.


## Sub lesson 3 — The omitted field — what blank means

A second form-2 example leaves **C_Description** out of the column list entirely:

```sql
INSERT INTO COURSE (C_Code, C_Name, Contact_Hr, C_Department)
VALUES ('CS102', 'Networks', 45, '105');
```

The record is created — and **C_Description is simply left blank (or given a default)** in the new record. **All unmentioned fields behave that way.** Leaving a field out is not an error; it is a choice with a visible result: an empty cell where the field stands.


## Say it to your companion

Tell your companion which field in the partial insert is blank in the finished record, and why that is not an error.

## Do It Yourself

1. Write a partial insert for a course with no description yet.
2. Open/view the resulting row (or draw it) and mark the blank cell.
3. Say which fields of DEPARTMENT could be left blank on entry, and which must never be — the key — and why.
