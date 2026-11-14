# Video script — Designing a Relational Database

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Design starts from the **need**: what the database must hold and what questions it must answer. From the need, the designer names the **entities** — the kinds of thing the database is about (Pupil, Book, Loan) — and each entity's **attributes**, the facts kept about it (Pupil: name, class, date of birth). An attribute belongs in the design only if the need asks for it: design is the need, written as structure — every table and column in the finished database should be traceable back to a question it must answer.
Each entity is given a **primary key** — the attribute (or added ID) that picks out one record from all others — and the **relationships** between entities are stated with their cardinality (a pupil takes many loans; a loan is of one book). Only then are the **tables** drawn: one table per entity, attributes as columns, keys in place, and **foreign keys** carrying the relationships. Malaysia's order is the lesson: tables drawn before entities and keys are understood are not a design but a guess that the data will later pay for.
