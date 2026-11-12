# Creating a query in Access

## Do it first

A teacher asks: *“Give me just the **name** and **sex** of every student — nothing else.”* The Student table holds much more than that. You do not copy the table and delete columns; you build a **query** — an object that shows a chosen view of the table's data. Decide now which fields the answer needs: name, sex. That choosing, done in a design grid, is this lesson.

## Sub lesson 1 — Open Query Design and add the table

A **query** is an **object that gives a custom view of data from one or more tables** — a way of **searching and compiling exactly the data wanted**. (The book builds queries **graphically**; it defers SQL — the written query language — to later.)

The book's order, first half:

1. **Open the database.**
2. **Click the Create menu.**
3. **Click Query Design.**
4. In the **Show Table** box, **select the table or tables** and **confirm**.

The chosen table now stands in the design window, ready for its fields to be picked.

[Picture 16916 — the Query Design grid above its results]

## Sub lesson 2 — Pick the fields for the Field row

5. **Pick the fields for the Field row.**

The Field row is the choosing place: **only the chosen fields will show** in the answer. For the teacher's question, you pick **name** and **sex** — the grade and address stay in the table, unpicked and unseen. A query shows what you picked, nothing more.

## Sub lesson 3 — See the results — Datasheet View

6. **Switch to Datasheet View to see the results.**

[GIF 16917 — fields picked in the grid, results appearing on the switch]

The results are a live view of the table's data through your chosen fields — change the table, and the query's answer changes with it. The book's practice queries: display **teacher name and specialisation**, and **student name and grade level**.

## Sub lesson 4 — Grade 12 — writing and running SQL in Access: SQL View and Run

**Grade 12 growth.** The graphical query has a written twin. In the book's exact order:

1. **Create tab → Query Design.** 2. **Close the Show Table dialog** that appears. 3. Open the **SQL View dropdown at the left and choose SQL View** — the window where SQL commands (**CREATE, SELECT, UPDATE, INSERT…**) are written.

To **run** a written query: **Design tab → Results group → Run**. Or — **if the query was saved** — **double-click it in the queries view** (the book's example runs a saved query listing male students).

**Access reports errors with a pop-up matched to the error type** — read the pop-up; it names the family of the fault, and the CREATE TABLE lesson's diagnosis drill tells you the shapes to hunt.

[Picture 30505 — the Query Design → SQL View → Run strip]

[GIF 30531 — the click path from Create tab to a running query]

## Say it to your companion

Tell your companion the full order for creating a query, and what the Field row decides. Then have them name a question (“only the names and grades, please”) and state the fields you would pick.

## Do It Yourself

1. Create a query showing student name and sex, following the book's order exactly.
2. Create the teacher name-and-specialisation practice query.
3. Write, in one sentence, what a query is.
4. Say why the unpicked fields do not appear in the results.
