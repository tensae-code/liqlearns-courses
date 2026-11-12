# File-based data management — separate files, duplicated data

## Do it first

Draw two boxes: **Human Resources** and **Finance**. In each box write the same employee: name **Aster**, address **Bole, Addis Ababa**. Now Aster moves house. Change the address in the HR box only. Look at your two boxes: the same person now has two different addresses, and nothing in either box warns you. Hold that picture — it is the whole problem this lesson names.

## Sub lesson 1 — Separate files, each with its own program

In the **file-based approach**, data is stored in **separate files**. There are **no explicit relationships** between the files — nothing inside one file points to anything inside another.

Each file is managed by **its own application program**, and **each department keeps its own files**: HR keeps the employee file, Finance keeps its own copy of employee details for pay, and so on.

The files and their programs are tied together tightly. **Changing the data can mean changing the program** — and **changing the program can mean changing the file structure** underneath it. The data does not stand on its own; it lives inside the shape one program expects.

[Picture 16900 — two departments, two copies of one record, disagreeing]

## Sub lesson 2 — Duplication — copies that drift apart

Because every department keeps its own files, **the same data is stored again and again**. The book's example: **employee records held in both HR and Finance**.

The copies are **never linked**. When one copy is updated and the other is not, the copies **drift out of step**. The data is now:

- **Inconsistent** — the copies disagree, and there is no way to tell from the files which one is right.
- **Redundant** — the same facts are stored more than once, taking space and effort for no new information.

Duplication is not a careless mistake in this approach — it is built into how the approach works.

## Sub lesson 3 — The whole organisation's data — and its security

Each file answers only its own department's questions. When a manager asks a question that crosses departments, **pulling together the whole organisation's data is very difficult** — the files were never made to join.

> **Teacher evidence — a third limitation.** With data scattered across separately owned files and programs, putting it under **one organisation-wide security procedure** is **difficult and expensive** (teacher guide — evidence, labelled in sources; the student book names duplication and inconsistency, the guide adds this one).

These problems — duplication, inconsistency, and data that will not come together — are what **forced the database approach into being**. That approach is the next lesson.

## Say it to your companion

Tell your companion how the file-based approach stores data, then run the Aster example: where is her record kept, what changed, and why do the copies now disagree? Finish with the third limitation: why is one security procedure for the whole organisation hard here?

## Do It Yourself

1. Draw the HR and Finance boxes from Do it first and label, on your drawing, the three problems: duplicated, inconsistent, hard to pull together.
2. Write one question a manager might ask that needs data from two departments at once — and say why the separate files make it hard to answer.
3. In two sentences, say what forced a new approach into being.
