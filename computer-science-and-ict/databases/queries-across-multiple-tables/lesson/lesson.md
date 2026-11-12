# Queries across multiple tables

## Do it first

One question, four facts: a student's **name**, their **subject**, their **grade**, and their **teacher's name**. Look at your tables: the name lives in **Student**, subject and grade live in **Grade**, the teacher's name lives in **Teacher**. No single table can answer. But the tables are **related** — that is the whole point of a relational database. This lesson joins them inside one query: the answer is assembled across tables, field by field.

## Sub lesson 1 — Add each table

The book's order, first steps:

1. **Open Query Design.**
2. **Add each table with Show Table and the Add button.**

Every table the answer needs must stand in the design window — for the book's example, **Student**, **Grade** and **Teacher**. A field cannot be picked from a table that is not there.

[Picture 16920 — three tables joined, one combined result below]

## Sub lesson 2 — Drag the key — establish the relationship

3. **Establish the relationship by dragging**: take the **primary-key field of the parent table** and **drag it onto the matching field of the child table**.

That drag is the skill of this lesson. The line it draws is the foreign-key link from the keys lesson, made visible: it tells Access *these two fields match — join the tables here*.

[GIF 16921 — the key-drag that makes the join line]

## Sub lesson 3 — Pick fields from each table, save, view

4. **Select the display fields from each table.** The book's example takes **student name from Student**, **subject and grade from Grade**, **teacher name from Teacher** — one answer row assembled from three tables.
5. **Save the query with a name.**
6. **View the combined results.**

The book's practice selects across **Student and Grade** — including the combined question with a criterion from the lesson before this one: **students scoring above 85 in all subjects**. One query, two tables, fields from each, a condition on top: that is the relational database's power, in your hands.

## Say it to your companion

Walk your companion through the order without the computer: add, drag, pick, save, view. They stop you at the drag and ask: which field, from which table, onto what — and what does the line mean?

## Do It Yourself

1. Build the Student–Grade–Teacher combined query and save it with a name.
2. Write which table each of the four example fields comes from.
3. Build the above-85 practice query across Student and Grade.
4. Explain, in two sentences, why this is called a *relational* database.
