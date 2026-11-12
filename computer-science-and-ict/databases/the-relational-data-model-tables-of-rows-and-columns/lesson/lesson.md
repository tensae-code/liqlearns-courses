# The relational data model — tables of rows and columns

## Do it first

Draw a grid with five columns: **ID, name, sex, grade, address**. Fill in two students of your own invention, one per row. Now put your finger on **one whole row**: that is everything about one student. Then run your finger down **one whole column**: that is one fact-kind about every student. Row and column have proper names in this model — the lesson gives them, twice each.

## Sub lesson 1 — Relations — tables with rows and columns

In the **relational data model**, data is represented as **two-dimensional tables** called **relations**.

Every part of a relation has two names — learn both, the books use both:

- A **row** is a **record**, also called a **tuple**. It holds **one unique instance** — one student, one book, one city.
- A **column** is an **attribute**, also called a **field**. It describes one property, for every row.

[Picture 16908 — one relation, a record and a field highlighted]

## Sub lesson 2 — The worked student relation — and linking relations

The book's worked relation is the grid from Do it first: **Student**, with columns **ID, name, sex, grade and address**, one row per student.

A whole relational model is **a collection of such relations**, together with **their attributes and their relationships**. Relations do not float apart: **a shared attribute placed in one relation links it to another** — the same attribute appearing in both tables is the bridge between them. The next lesson gives those bridge fields their special names: primary keys and foreign keys.

## Sub lesson 3 — The Country–City worked join (teacher guide — evidence)

> **Teacher evidence — the join, fully worked.** The student book sets this activity; the fully worked answer exists only in the teacher guide, so this part is labelled evidence.

The guide works the **Country** and **City** tables end to end: it **identifies the linking attribute** — the shared attribute that joins the two tables — **counts the fields**, **picks out the Kenyan cities**, and prints the result as **one joined country–city–population table: nine cities across Ethiopia, Egypt, Kenya and Sudan, with their population figures**.

[Picture 16909 — Country, City, and the joined table]

That joined table is what “retrieving across tables” means — and the last Access lesson in this title makes you build exactly this kind of join yourself, by dragging a key.

## Sub lesson 4 — Grade 12 — the RDBMS frame, and fields and records in Ethiopian examples

**Grade 12 growth.** The definition, in its fuller form: a **Relational Database Management System (RDBMS)** is **software used to create, maintain and provide controlled access to a relational database**, where data is stored in **two-dimensional tables** — **each column a field/attribute, each row a record/tuple holding one data value per column**.

The frame example is a **student** entity described by the attributes **student id, name, age, grade level and sex** — five attributes, one row per student.

Filled-in Ethiopian example sets (teacher guide — evidence) make the words concrete. Single field values across types: **a book title, an email address, a sales date, a body temperature, a weight, a cost of material in birr, an expiry date, an opening hour**. A **patient** described by typed fields: name (text), address (text), date visited (date), blood pressure (a real number), age (integer). Fields are listed for **Person, Book and Sales** entities, and a record is given as **one full row of a Student table — an ID, a name, an age**.

[Picture 30500 — a relational table: one row a record, one column a field]

## Say it to your companion

Tell your companion the two names for a row and the two names for a column. Then explain, with Country and City, what a linking attribute does (teacher evidence part).

## Do It Yourself

1. Draw the student relation and enter three students; label one tuple and one field.
2. Write what a whole relational model is a collection of.
3. Name the shared attribute that would link a City table to a Country table, and say what the joined table can show (teacher evidence).
