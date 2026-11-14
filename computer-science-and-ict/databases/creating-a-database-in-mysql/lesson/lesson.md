# Creating a Database in MySQL

## Do it first

Egypt's Grade 11 website project needs somewhere real for its dictionary of computer terms to live. After the database idea itself, the book creates the project's database in MySQL — the database server that works beside PHP in the classic school stack — and this lesson teaches that creation as its own skill.

## Sub lesson 1 — MySQL — a database server, not a file

**MySQL** keeps a database on a **server**: a program that holds the data, answers requests from other programs, and guards who may do what. That is the step up from a desktop database file — the project's website and its database are different programs talking to each other, the PHP pages asking, MySQL answering. Creating begins with the **database itself** — a named container for this project's data — made with the server's tools (the book works through the local server stack's control panels), before any table exists: container first, furniture after.

[Picture — MySQL — a database server, not a file]

## Sub lesson 2 — Tables for the dictionary — fields, types, the key

Inside the new database, the project's **table** is created column by column: for the Illustrated Dictionary, the term, its meaning, and its illustration reference — each column given a **type** (text for the term and meaning, a number where a number belongs) and a length that fits real entries. One column is made the **primary key** — the identifier no two terms may share — so every entry can be found, edited and deleted exactly. Egypt teaches creation inside a live project for a reason: every choice (a too-short text field, a missing key) is paid for later by the Add_Term page that must write into this table, so the table is designed from the page's needs backwards.

[Picture — Tables for the dictionary — fields, types, the key]

## Say it to your companion

Tell your companion, in your own words: **MySQL** keeps a database on a **server**: a program that holds the data, answers requests from other programs, and guards who may do what. That is the step up from a desktop database file — the project's website and its database are different programs talking to each other, the PHP pages asking, MySQL answering. Creating begins with the **database itself** — a named container for this project's data — made with the server's tools (the book works through the local server stack's control panels), before any table exists: container first, furniture after. Inside the new database, the project's **table** is created column by column: for the Illustrated Dictionary, the term, its meaning, and its illustration reference — each column given a **type** (text for the term and meaning, a number where a number belongs) and a length that fits real entries. One column is made the **primary key** — the identifier no two terms may share — so every entry can be found, edited and deleted exactly. Egypt teaches creation inside a live project for a reason: every choice (a too-short text field, a missing key) is paid for later by the Add_Term page that must write into this table, so the table is designed from the page's needs backwards. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A database server — a program that holds data and answers other programs' requests. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The website and the database are different programs talking to each other. Do this with a real example of your own and write or say how you know it is right.
6. Show it, don't just say it: So every entry can be found, edited and deleted exactly. Do this with a real example of your own and write or say how you know it is right.
7. Show it, don't just say it: From the Add_Term page's needs, backwards. Do this with a real example of your own and write or say how you know it is right.
