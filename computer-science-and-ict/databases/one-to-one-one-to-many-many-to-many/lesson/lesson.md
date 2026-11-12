# One-to-one, one-to-many, many-to-many

## Do it first

Take two things: a **country** and its **capital city**. Ask two questions. *One country — how many capital cities does it have in this model?* One. *One capital city — how many countries does it belong to?* One. One and one. Now take a **department** and its **students**: one department, how many students? Many. That difference — the counting — is this whole lesson.

## Sub lesson 1 — One-to-one

**One-to-one:** one instance on one side links to **exactly one** instance on the other side.

The book's example: a **country** and its **capital city**. One country has one capital city; one capital city is the capital of one country.

Count it both ways before you name it: one → one. That double count is the test.

[Picture 16904 — the three relationship types, one diagram each]

## Sub lesson 2 — One-to-many

**One-to-many:** one instance on one side links to **many** instances on the other side.

The book's example: one **department** has many **students**. Count both ways: one department → many students; one student → (in this model) one department.

The “many” side is where the crowd is. Most relationships you will model are this type.

## Sub lesson 3 — Many-to-many

**Many-to-many:** instances on **both** sides link to many on the other side.

The book's example: an **employee works on many projects**, and **a project has many employees**. Count both ways and both counts are “many”.

> **Tip:** when you test a pair, always count in both directions — a relationship that looks one-to-many one way may be many-to-many when you turn it around (students and subjects are the classic trap: one student takes many subjects, and one subject is taken by many students).

## Sub lesson 4 — Grade 12 — building relationships by dragging: the Relationships window

**Grade 12 growth.** Relationships can also be built **graphically**, without SQL. In the book's order:

1. **Database Tools tab → Relationships group → Relationships.** 2. In the **Show Table** pop-up, **add the tables/queries** and **Close**. 3. **Drag a field — typically the primary key — from one table onto the common field (the foreign key) in the other**, using **Ctrl** to drag several fields.

The diagram marks the **one side “1”** and the **many side “∞”** — **Department to Teacher is one-to-many**: one department, many teachers. Linked tables must **share a common key item with matching primary/foreign key data types**, and — the standing rule — **data should not be added before relationships are set up**.

[Picture 30509 — the Relationships window: 1 to ∞]

[GIF 30532 — a primary key dragged onto a foreign key; the link line appears]

## Say it to your companion

Quiz your companion: you name a pair of entities, they count both ways and name the type. Use the book's three examples first, then one pair of your own.

## Do It Yourself

1. Name the type: a school and its head teacher (one each way, in this model).
2. Name the type: one library book (one copy) and the one pupil who has borrowed it right now — then say how the count changes if the model tracks every loan ever.
3. Write the two counts for employees and projects, and name the type.
