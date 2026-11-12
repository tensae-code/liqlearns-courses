# The database approach and the DBMS

## Do it first

Draw three layers, one above the other. At the bottom write **the database — all the data, in one place**. In the middle write **DBMS**. At the top write **applications and users**. Now a top-layer program asks: *“Which students are in Grade 11?”* Draw an arrow down for the question and an arrow back up for the answer. That round trip — down as a query, up as matching data — is this lesson.

## Sub lesson 1 — One shared collection — the database

The **database approach** answers the file problems directly: instead of every department keeping its own files, **all of an organisation's logically related data lives in one shared collection** — a **database**.

One collection, shared by everyone who needs it. There is one copy of the employee record, not an HR copy and a Finance copy drifting apart.

[Picture 16901 — the stack: database, DBMS, applications]

## Sub lesson 2 — The DBMS — the software in the middle

The database is managed by software called a **DBMS** — a **Database Management System**. The DBMS:

- **adds** new data,
- **modifies** data that changes,
- **deletes** data no longer needed,
- **retrieves** data that is asked for.

The DBMS is the **interface** — the layer in between — **between the database and its users and programs**. No program touches the data directly. An application sends a **query** — a request for data — to the DBMS, and **the DBMS returns the matching data**.

[GIF 16902 — a query goes down the stack, the answer comes back]

## Sub lesson 3 — The four advantages over files

Against the file approach, the database approach brings four named advantages:

1. **Data independence** — one database serves all users; the data stands on its own, not tied inside one program's file structure.
2. **Data sharing** — many users reach the one central store.
3. **Avoided redundancy** — the data is stored once, so copies cannot drift apart.
4. **Improved security** — only **authorised users** can access or change the data, under the DBMS's control.

> **Tip:** the next lessons open this stack up — first how the data inside is modelled (entities and attributes), then how it is stored as tables, and finally how to build it yourself in Access.

## Sub lesson 4 — Grade 12 — database versus DBMS, and the NoSQL challenge (teacher guide — evidence)

**Grade 12 growth (teacher guide — evidence).** Clear the standing confusion directly: **a database is the schema designed with a DBMS to store data; the DBMS is the software tool used to maintain it.** The data and the tool are not the same thing — one is the stored, organised collection, the other is the program that runs it.

The wider tool landscape beyond Access: **MySQL, Oracle, MS SQL Server and MariaDB** are the guide's named RDBMS tools. The guide also lists **MongoDB** here — an error: MongoDB is a NoSQL system (flagged in sources).

The challenge for strong pupils: the **general limitation of an RDBMS in the era of big data — its schema is not flexible enough** — and **other models, such as NoSQL, address exactly that**. The unit's practical prerequisite is also the guide's: a computer with **MS Access installed, 2013 or later** assumed for its activities.

[Picture 30508 — database versus DBMS, and the NoSQL point]

## Say it to your companion

Tell your companion what the DBMS does, all four jobs. Then trace one query: who sends it, who receives it, what travels back. Finish with the four advantages, one sentence each.

## Do It Yourself

1. Draw the three-layer stack from memory and label every layer.
2. Write one query a school office might send to its database, and say what matching data should come back.
3. Match each file-approach problem (duplication, inconsistency, no sharing) to the database advantage that answers it.
