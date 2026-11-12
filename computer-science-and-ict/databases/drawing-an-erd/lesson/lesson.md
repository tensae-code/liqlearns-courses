# Drawing an ERD

## Do it first

Draw a **rectangle** and write **STUDENT** inside it. Around it draw four **ellipses** — ovals — and write in them: **student ID**, **name**, **age**, **address**. Join each ellipse to the rectangle. Now draw a second rectangle: **BOOK**, with three ellipses: **book ID**, **title**, **publication year**. Last, draw **one line** between STUDENT and BOOK and write **borrows** on the line. You have just drawn an ERD. The lesson names each shape and checks your drawing against the rules.

## Sub lesson 1 — The three shapes

An **Entity Relationship Diagram — an ERD** — is the popular visual way to draw a data model. It uses exactly **three components**:

- **Entities** are drawn as **rectangles**, with the entity name inside.
- **Attributes** are drawn as **ellipses** (ovals), with the attribute name inside.
- **Relationships** are drawn as **lines joining entities**, with the **relationship name written on the line**.

Three shapes. If you can draw those, you can draw any model in this unit.

[GIF 16906 — an ERD building itself: rectangle, ellipses, joining line]

## Sub lesson 2 — The worked example — student borrows book

The book's worked example is the drawing from Do it first:

- **STUDENT** (rectangle) with attributes **student ID, name, age, address** (ellipses).
- **BOOK** (rectangle) with attributes **book ID, title, publication year** (ellipses).
- A line between them, named **borrows**.

[Picture 16905 — the student–borrows–book ERD]

Check yours against it: two rectangles, seven ellipses, one labelled line. Then the book's practice task: draw a **teacher–schedule** ERD the same way — find the entities first.

## Sub lesson 3 — Solving a case study (teacher guide — evidence)

> **Teacher evidence — a case solved in full.** The student book sets a case; the solved model exists only in the teacher guide, so this part is labelled evidence, not pupil-taught text.

The case's three entities are **Product**, **Customer** and **Order**, each carrying its own attribute list. The diagram must carry these three relationship rules:

1. A **customer makes one or many orders**.
2. An **order is for one or more products**.
3. A **product may have no order, or belong to only one order**.

[Picture 16907 — the solved Product–Customer–Order ERD, rules captioned]

The solving order matters, and it is the guide's walkthrough order: **find the entities first, then the attributes, then the relationships.**

## Say it to your companion

Show your companion your student–borrows–book drawing and name every shape as you point to it. Then cover the solved case picture and state its three relationship rules from memory; your companion checks them.

## Do It Yourself

1. Draw the student–borrows–book ERD from memory, then count: 2 rectangles, 7 ellipses, 1 labelled line.
2. Draw the teacher–schedule ERD (the book's practice task).
3. For the Product–Customer–Order case, write the three entities and the three relationship rules without looking (teacher evidence).
