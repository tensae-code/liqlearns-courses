# SELECT * — getting a whole table

## Do it first

You need the whole COURSE table on screen — every column, every row, to check it after the inserts. Typing all five field names is one way. There is a one-character way that means 'all of them'. Guess the character before you turn the page — it is the same star that means 'everything' in other computer places.

## Sub lesson 1 — The asterisk means all columns

```sql
SELECT * FROM COURSE;
```

Writing **SELECT * FROM** a table retrieves **all its records and columns**. The **asterisk means all columns**, and it gives **the same result as listing every field** by name.

The recommendation: use the asterisk when **all fields are wanted** — it is shorter, and it cannot misspell a field it never names.


## Sub lesson 2 — Exact names — the spelling rule

When fields *are* named, the rule is strict: **field names in a SELECT must be spelled exactly as in the table**, or the expected output does not appear.

The worked answer set (teacher guide — evidence) adds why the asterisk is good practice on a **many-column table**: listing every field invites **naming errors** — one wrong name and the query fails or misleads. The star is not laziness; on a wide table it is accuracy.


## Say it to your companion

Tell your companion when you would write * and when you would name fields.

## Do It Yourself

1. Write the query that shows the whole DEPARTMENT table.
2. Predict the result of SELECT * FROM COURSE; — columns and rows.
3. A query names C_Nmae instead of C_Name. What happens, and how would * have avoided it?
