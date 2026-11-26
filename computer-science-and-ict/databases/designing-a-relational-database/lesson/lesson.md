# Designing a Relational Database

## Do it first

Tables are not where a database starts. Malaysia's design lesson walks the road before them: need, entities, attributes, keys, relationships — then tables. In this lesson you design a small relational database on paper, in the book's order.

## Sub lesson 1 — From the need to entities and attributes

Design starts from the **need**: what the database must hold and what questions it must answer. From the need, the designer names the **entities** — the kinds of thing the database is about (Pupil, Book, Loan) — and each entity's **attributes**, the facts kept about it (Pupil: name, class, date of birth). An attribute belongs in the design only if the need asks for it: design is the need, written as structure — every table and column in the finished database should be traceable back to a question it must answer.

In your mind's eye: from the need to entities and attributes.

[Picture 46520 — from the need to entities and attributes]

## Sub lesson 2 — Keys, relationships, and the tables

Each entity is given a **primary key** — the attribute (or added ID) that picks out one record from all others — and the **relationships** between entities are stated with their cardinality (a pupil takes many loans; a loan is of one book). Only then are the **tables** drawn: one table per entity, attributes as columns, keys in place, and **foreign keys** carrying the relationships. Malaysia's order is the lesson: tables drawn before entities and keys are understood are not a design but a guess that the data will later pay for.

In your mind's eye: keys, relationships, and the tables.

[Picture 46521 — keys, relationships, and the tables]

## Say it to your companion

Tell your companion, in your own words: Design starts from the **need**: what the database must hold and what questions it must answer. From the need, the designer names the **entities** — the kinds of thing the database is about (Pupil, Book, Loan) — and each entity's **attributes**, the facts kept about it (Pupil: name, class, date of birth). An attribute belongs in the design only if the need asks for it: design is the need, written as structure — every table and column in the finished database should be traceable back to a question it must answer. Each entity is given a **primary key** — the attribute (or added ID) that picks out one record from all others — and the **relationships** between entities are stated with their cardinality (a pupil takes many loans; a loan is of one book). Only then are the **tables** drawn: one table per entity, attributes as columns, keys in place, and **foreign keys** carrying the relationships. Malaysia's order is the lesson: tables drawn before entities and keys are understood are not a design but a guess that the data will later pay for. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: From the need — what the database must hold and what questions it must answer. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The kinds of thing the database is about — Pupil, Book, Loan. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The facts kept about an entity — a pupil's name, class, date of birth. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The attribute (or added ID) that picks out one record from all others. Do this with a real example of your own and write or say how you know it is right.
