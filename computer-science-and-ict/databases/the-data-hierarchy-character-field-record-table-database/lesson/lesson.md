# The Data Hierarchy — Character, Field, Record, Table, Database

## Do it first

Take one real record — a school report card, a clinic card, an identity card. Look at the smallest thing on it: one single letter of a name. Now look at the whole name. Now look at everything the card says about that one person. Now picture the drawer holding a card like it for every pupil in the school. Keep those four sizes in mind — the lesson gives each size its name.

## Sub lesson 1 — The ladder — character, field, record, table

Data is not stored as one heap. It is organised as a **hierarchy** — a ladder where each level is built from the level below. The smallest piece is a **character**: one letter, one digit or one symbol, like the letter K or the digit 7. (Under the character sits the bit, the 0 or 1 the machine actually stores — the data-representation lessons cover that rung.)

Characters together make a **field**: one single fact. "Amina" is the characters A-m-i-n-a standing in the Name field; "1042" stands in the Admission Number field. A field has a name and holds one kind of fact, never a mixture.

All the fields about one person or thing make a **record**: Amina's name, admission number, class and date of birth together are Amina's record. All the records of the same kind, kept together in rows and columns, make a **table** — the pupils table holds one record per pupil, one field per column.

In your mind's eye: one school record card with callouts zooming in: one letter circled as a character, the whole name underlined as a field, the whole card framed as a record.

## Sub lesson 2 — The top of the ladder — the database, and why the ladder matters

The top rung is the **database** itself: not one table but a collection of **related tables**, kept together and looked after by a database management system. A school's database holds a pupils table, a teachers table and a fees table — related because a fee record points at a pupil, and a class record points at a teacher.

Why build the ladder at all? Because it is how the work gets done. You type **character** by character into a **field**; the program finds, sorts and prints **record** by record; you organise a whole **table** at a time; and the **database** keeps the tables consistent with each other. Every database lesson after this one — data types, keys, queries, forms — is really about one rung of this ladder.

The ladder also warns you: put two facts in one field ("Amina, Class 4" in the Name field) and the program can no longer sort by class or search by name cleanly. One field, one fact — that discipline starts here. Kenya's Form 2 database unit teaches the hierarchy as its own step, right before learners create a database in Access.

In your mind's eye: three labelled tables.

## Say it to your companion

Tell your companion, in your own words: Data inside a database is organised as a ladder: a character is one letter or digit; characters together make a field (one fact, like a name); fields about one person or thing make a record; records of the same kind make a table; and related tables together make the database — each level is built out of the level below it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: name the levels of the data hierarchy in order, from character up to database. Do this with a real example of your own, and write or say how you know it is right.
2. Show it, don't just say it: break one real example (a student's school record) into its characters, fields, records, table and database. Do this with a real example of your own, and write or say how you know it is right.
3. Show it, don't just say it: say what is stored at each level and give an example of each. Do this with a real example of your own, and write or say how you know it is right.
4. Show it, don't just say it: explain why the levels matter: a database program searches and updates data level by level. Do this with a real example of your own, and write or say how you know it is right.
