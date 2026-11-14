# Video script — Creating a Database in MySQL

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**MySQL** keeps a database on a **server**: a program that holds the data, answers requests from other programs, and guards who may do what. That is the step up from a desktop database file — the project's website and its database are different programs talking to each other, the PHP pages asking, MySQL answering. Creating begins with the **database itself** — a named container for this project's data — made with the server's tools (the book works through the local server stack's control panels), before any table exists: container first, furniture after.
Inside the new database, the project's **table** is created column by column: for the Illustrated Dictionary, the term, its meaning, and its illustration reference — each column given a **type** (text for the term and meaning, a number where a number belongs) and a length that fits real entries. One column is made the **primary key** — the identifier no two terms may share — so every entry can be found, edited and deleted exactly. Egypt teaches creation inside a live project for a reason: every choice (a too-short text field, a missing key) is paid for later by the Add_Term page that must write into this table, so the table is designed from the page's needs backwards.
