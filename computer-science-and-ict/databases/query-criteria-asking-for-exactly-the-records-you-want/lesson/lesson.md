# Query criteria — asking for exactly the records you want

## Do it first

Write your class list — name and sex for eight pupils. Now the question changes: *“only the **male** students.”* A plain query would show all eight rows. You need the query itself to **filter**: keep a record only if it matches a condition. On paper, write the condition as two parts — the **field** it tests (Sex) and the **value** it must equal (M). Cross out every row that fails it. What is left is exactly what a criteria query shows.

## Sub lesson 1 — The Criteria row — M under Sex

**Criteria** narrow a query to **records that match a condition**. The book's order:

1. **Open Query Design** and **add the table**.
2. **Select the display fields.**
3. **Type the condition in the Criteria row, under the right field.**

The book's example: entering **M** in the Criteria row **under Sex** shows **only male students**. The field above the criterion is what is tested; the criterion is the value a record must match to appear.

[Picture 16918 — the class list narrowing to the matching rows]

[GIF 16919 — the results shrink as the criterion lands]

## Sub lesson 2 — The exact-match warning — and the practice

The warning is exact, and it is the book's own: **the criterion must match the stored data exactly**. If sex is stored as a **single character** — M or F — then typing the **full word** (“Male”) as the criterion **returns nothing**: no stored value equals it, so no record matches.

Before you type a criterion, ask: *how is this value actually stored?* Then type it in that exact form.

The book's practice includes building the **Female_Students** query — the same skill, turned the other way: the criterion that keeps only the female students, in the exact form your table stores it.

## Say it to your companion

Tell your companion where a criterion is typed and what the field above it decides. Then explain why “Male” can return nothing in a table that plainly has male students.

## Do It Yourself

1. Build the query that shows only male students (M under Sex).
2. Build the Female_Students practice query, with the criterion in your table's stored form.
3. Write the exact-match warning in your own words, with the single-character example.
