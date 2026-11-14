# Video script — Mapping an ERD to a Relational Schema

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The straight rules come first: every **entity** in the ERD becomes a **table**; every **attribute** of the entity becomes a **column** of that table; the entity's **key attribute** becomes the table's **primary key**. A **multivalued attribute** (a pupil's phone numbers) cannot be a column — it becomes a **table of its own**, holding the key and one value per record. After this step every box and oval of the diagram has a home in the schema, or a stated reason why not.
Relationships map by their **cardinality**. A **one-to-many** relationship is carried by a **foreign key**: the key of the 'one' side is placed as a column in the 'many' side's table (ClassID inside the Pupil table). A **many-to-many** relationship cannot be a single column — it becomes a **new table** holding both sides' keys as its composite key, plus the relationship's own attributes (an Enrolment table: PupilID, SubjectID, mark). Malaysia's check closes the mapping: every relationship in the ERD must be traceable in the schema — as a foreign key or as a table — or the mapping is not finished.
