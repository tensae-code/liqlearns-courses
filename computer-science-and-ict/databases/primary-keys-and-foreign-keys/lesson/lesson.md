# Primary keys and foreign keys

## Do it first

Write three rows: **ID 101, Aster** — **ID 102, Aster** — **ID 103, Samuel**. Two students share the name *Aster*. If someone asks for “Aster's record”, which one do they mean? Only one column never repeats: the **ID**. That column has a special job and a special name — this lesson gives it, and then gives the name of the field that carries that ID into another table.

## Sub lesson 1 — Primary keys — the field that never repeats

A **relational database** is a **set of logically related tables**, built with relational DBMS software — an **RDBMS**.

Every table has a **primary key**: a **field whose value is unique for each record**. The book's example is the **student ID** — **no two students can share** one ID, so the ID identifies each student's record exactly, even when names repeat.

[Picture 16910 — Student, Book and Book_Loan, keys marked, links drawn]

## Sub lesson 2 — Foreign keys — the matching field in the other table

A **foreign key** is an **attribute in one table that matches the primary key of a related table**.

Tables are **navigated and joined through foreign keys**: the foreign key carries the primary key's value across the bridge the shared attribute made in the last lesson. Where the primary key identifies, the foreign key refers.

## Sub lesson 3 — The book-loan table — both keys at work

The book's worked set has three tables: **Student**, **Book**, and **Book_Loan**.

Inside Book_Loan stand two foreign keys:

- its **student ID**, matching Student's primary key — it says *who* borrowed;
- its **book ID**, matching Book's primary key — it says *what* was borrowed.

One loan row, followed through its two foreign keys, lights up exactly one student row and exactly one book row. That following — table to table, key to key — is how a relational database answers questions no single table can.

[GIF 16911 — a loan row lights up its student and its book]

## Say it to your companion

Tell your companion what makes a field fit to be a primary key, then trace one loan row through both of its foreign keys, naming the table each key matches.

## Do It Yourself

1. Say why “name” fails as a primary key for a student table, in one sentence.
2. In the Book_Loan table, mark the two foreign keys and write the primary key each one matches.
3. Write the definition of a relational database.
