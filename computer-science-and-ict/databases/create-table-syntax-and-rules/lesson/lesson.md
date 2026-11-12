# CREATE TABLE — building a table with SQL

## Do it first

On paper, design a table for a bookshop's books: title, author, price, year. Write each field with the type it needs. Hold that plan — in this lesson you turn exactly such a plan into one written command that builds the table for real.

## Sub lesson 1 — The general form

**CREATE TABLE** creates a new table. Its general form: **name the table**, then **in parentheses list each column with its data type**, optionally marking one column **[Primary Key]**, and optionally making a column a **reference** to another table's key column with **REFERENCES**.

```sql
CREATE TABLE Student (
  StudentID INTEGER PRIMARY KEY,
  FirstName CHAR(30),
  Age INTEGER,
  Sex CHAR(1)
);
```

Read it aloud part by part: the command, the table's name, then the column list — each column a name and a type.


## Sub lesson 2 — The rules that keep it valid

Every column needs a **name and a data type**; the definitions are separated by **commas** inside the opening and closing parentheses.

**Different DBMSs may name types differently or size them differently** — check the documentation of the system in front of you.

A sized character field **silently keeps only its first N characters**: a long course name put into a **TEXT(20)** field is stored cut at 20 characters, spaces counted. Size a field for the longest real value it must hold.

Two working tips from the answer keys: never put a space in a field name — write **FirstName**, not **First Name** — or it generates an error; and ending a statement with a **semicolon is optional but good practice** for clarity.


## Sub lesson 3 — Worked builds and broken SQL (teacher guide — evidence)

The worked answer set builds three linked tables — **Student**, **Teacher** and **Grade** — each with its primary key, with Grade carrying foreign keys to the other two. The method is always the same: judge each value's nature first, then choose its type.

Sizing types from real values: a bank-account number is made **text**, because an integer cannot hold it; an employee ID uses a **counter/autonumber**; text fields are sized from the longest real value, with headroom.

Diagnosing broken CREATE statements — three faults to learn to spot: a **missing comma** between columns with a wrong closing brace; the **missing word TABLE** after CREATE; and a **misspelt REFERENCES** with a missing bracket. When Access refuses a statement, hunt these shapes first.


## Say it to your companion

Tell your companion the general form of CREATE TABLE, then read your own statement aloud and let them check every comma.

## Do It Yourself

1. Write CREATE TABLE for a Book table: BookID (integer, primary key), Title CHAR(50), Price CURRENCY.
2. A statement fails. It reads `CREATE Student (StudentID INTEGER FirstName CHAR(30))`. Find its faults.
3. Explain why a bank-account number is stored as text, not integer.
