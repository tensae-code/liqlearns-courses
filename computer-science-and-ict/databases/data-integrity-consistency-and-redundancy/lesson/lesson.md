# Data Integrity, Consistency and Redundancy

## Do it first

A school keeps a pupil's address in four places; she moves, one place is updated, and the database now disagrees with itself. Malaysia's database chapter opens with the three words that name that trouble. In this lesson you learn integrity, consistency and redundancy — and why a database is designed against all three faults.

## Sub lesson 1 — Integrity and consistency — data you can trust

**Data integrity** means the data is **correct and complete** — true values, entered under rules (a mark between 0 and 100, a date that exists), not corrupted or half-saved. **Data consistency** means the database **never disagrees with itself**: the same fact, wherever it is read, reads the same. A pupil's class changed in the class list must be the same class in the marks list. Integrity guards each value; consistency guards the agreement between values.

In your mind's eye: integrity and consistency — data you can trust.

[Picture 46491 — integrity and consistency — data you can trust]

## Sub lesson 2 — Redundancy — the stored copy that breeds disagreement

**Redundancy** is storing the **same fact in more than one place**. It wastes storage, but its deeper harm is that the copies can **drift apart** — update one, miss another, and consistency is broken by the design itself. Malaysia's design answer follows: store each fact **once**, in its own table, and let other tables **refer** to it by a key rather than copy it. Some copying is sometimes accepted knowingly for speed — but as a chosen trade, never as an accident of design.

In your mind's eye: redundancy — the stored copy that breeds disagreement.

[Picture 46492 — redundancy — the stored copy that breeds disagreement]

## Say it to your companion

Tell your companion, in your own words: **Data integrity** means the data is **correct and complete** — true values, entered under rules (a mark between 0 and 100, a date that exists), not corrupted or half-saved. **Data consistency** means the database **never disagrees with itself**: the same fact, wherever it is read, reads the same. A pupil's class changed in the class list must be the same class in the marks list. Integrity guards each value; consistency guards the agreement between values. **Redundancy** is storing the **same fact in more than one place**. It wastes storage, but its deeper harm is that the copies can **drift apart** — update one, miss another, and consistency is broken by the design itself. Malaysia's design answer follows: store each fact **once**, in its own table, and let other tables **refer** to it by a key rather than copy it. Some copying is sometimes accepted knowingly for speed — but as a chosen trade, never as an accident of design. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The data is correct and complete — true values entered under rules. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A mark between 0 and 100 (also: a date that exists). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The database never disagrees with itself — the same fact reads the same everywhere. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Storing the same fact in more than one place. Do this with a real example of your own and write or say how you know it is right.
