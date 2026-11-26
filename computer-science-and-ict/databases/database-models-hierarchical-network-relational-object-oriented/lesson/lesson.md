# Database Models — Hierarchical, Network, Relational, Object-Oriented

## Do it first

Before tables there were trees. Malaysia's database chapter lines up four models for organising a database and compares how each one joins its data. In this lesson you meet the four — and why the relational model, the chapter's own, won its place.

## Sub lesson 1 — Hierarchical and network — the linked-record models

The **hierarchical model** organises records as a **tree**: each record has one **parent** and may have many **children** (a school → classes → pupils). It is fast down its paths but rigid — a pupil in two classes has no honest place in one tree. The **network model** loosens the tree into a **web**: a record may have **several parents**, joined by named links, so many-to-many facts fit — at the cost of a structure only programmers can navigate, record by record.

In your mind's eye: hierarchical and network — the linked-record models.

[Picture 46498 — hierarchical and network — the linked-record models]

## Sub lesson 2 — Relational and object-oriented — tables and objects

The **relational model** stores data in **tables** of rows and columns, joined not by stored links but by **matching values** — keys — worked out when a question is asked. It is the model of this whole course: simple to see, flexible to question. The **object-oriented model** stores **objects** — data together with the actions that belong to it (a Pupil object that holds its marks and can print its own report) — suiting programs built from objects, at the cost of a smaller, more specialised world of tools. Malaysia's comparison ends where its course stands: relational, because school and business data is tabular, shared, and questioned in ways no tree foresaw.

In your mind's eye: relational and object-oriented — tables and objects.

[Picture 46499 — relational and object-oriented — tables and objects]

## Say it to your companion

Tell your companion, in your own words: The **hierarchical model** organises records as a **tree**: each record has one **parent** and may have many **children** (a school → classes → pupils). It is fast down its paths but rigid — a pupil in two classes has no honest place in one tree. The **network model** loosens the tree into a **web**: a record may have **several parents**, joined by named links, so many-to-many facts fit — at the cost of a structure only programmers can navigate, record by record. The **relational model** stores data in **tables** of rows and columns, joined not by stored links but by **matching values** — keys — worked out when a question is asked. It is the model of this whole course: simple to see, flexible to question. The **object-oriented model** stores **objects** — data together with the actions that belong to it (a Pupil object that holds its marks and can print its own report) — suiting programs built from objects, at the cost of a smaller, more specialised world of tools. Malaysia's comparison ends where its course stands: relational, because school and business data is tabular, shared, and questioned in ways no tree foresaw. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Hierarchical, network, relational, object-oriented. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: As a tree — one parent, many children. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A pupil in two classes has no place in a single tree. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: By matching values — keys — worked out when a question is asked, not by stored links. Do this with a real example of your own and write or say how you know it is right.
