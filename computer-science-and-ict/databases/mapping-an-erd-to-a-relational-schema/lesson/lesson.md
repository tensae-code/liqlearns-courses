# Mapping an ERD to a Relational Schema

## Do it first

An ERD is a picture; a schema is the buildable design. Malaysia's advanced database chapter teaches the mapping between them as a craft of its own. In this lesson you turn a diagram into tables — rule by rule.

## Sub lesson 1 — Entities and attributes — the straight mapping

The straight rules come first: every **entity** in the ERD becomes a **table**; every **attribute** of the entity becomes a **column** of that table; the entity's **key attribute** becomes the table's **primary key**. A **multivalued attribute** (a pupil's phone numbers) cannot be a column — it becomes a **table of its own**, holding the key and one value per record. After this step every box and oval of the diagram has a home in the schema, or a stated reason why not.

In your mind's eye: entities and attributes — the straight mapping.

[Picture 46556 — entities and attributes — the straight mapping]

## Sub lesson 2 — Relationships — foreign keys and new tables

Relationships map by their **cardinality**. A **one-to-many** relationship is carried by a **foreign key**: the key of the 'one' side is placed as a column in the 'many' side's table (ClassID inside the Pupil table). A **many-to-many** relationship cannot be a single column — it becomes a **new table** holding both sides' keys as its composite key, plus the relationship's own attributes (an Enrolment table: PupilID, SubjectID, mark). Malaysia's check closes the mapping: every relationship in the ERD must be traceable in the schema — as a foreign key or as a table — or the mapping is not finished.

In your mind's eye: relationships — foreign keys and new tables.

[Picture 46557 — relationships — foreign keys and new tables]

## Say it to your companion

Tell your companion, in your own words: The straight rules come first: every **entity** in the ERD becomes a **table**; every **attribute** of the entity becomes a **column** of that table; the entity's **key attribute** becomes the table's **primary key**. A **multivalued attribute** (a pupil's phone numbers) cannot be a column — it becomes a **table of its own**, holding the key and one value per record. After this step every box and oval of the diagram has a home in the schema, or a stated reason why not. Relationships map by their **cardinality**. A **one-to-many** relationship is carried by a **foreign key**: the key of the 'one' side is placed as a column in the 'many' side's table (ClassID inside the Pupil table). A **many-to-many** relationship cannot be a single column — it becomes a **new table** holding both sides' keys as its composite key, plus the relationship's own attributes (an Enrolment table: PupilID, SubjectID, mark). Malaysia's check closes the mapping: every relationship in the ERD must be traceable in the schema — as a foreign key or as a table — or the mapping is not finished. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A table. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A column of its entity's table. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The table's primary key. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: By a foreign key — the 'one' side's key placed in the 'many' side's table. Do this with a real example of your own and write or say how you know it is right.
