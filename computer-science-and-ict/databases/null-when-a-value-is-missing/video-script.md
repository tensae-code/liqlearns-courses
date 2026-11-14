# Video script — Null — When a Value Is Missing

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Null** means **no value is stored** — the value is unknown, or the field does not apply to this record. Null is not **zero** (zero is a real amount) and not an **empty string** (that is a real, if short, text): a salary of 0 says the person earns nothing; a salary of null says we do not know, or the question does not arise. Queries must respect the difference: counting records with a value skips the nulls, and a comparison with null never comes out true — unknown compared to anything is still unknown.
One field may never hold the blank: the **primary key**. The key's whole job is to identify the record — the National ID of the companion lesson — and a record whose identifier is missing cannot be found, joined or told apart from another blank. So the DBMS enforces **entity integrity**: every primary key value exists and is unique. When you design a table, you decide field by field which may be null — a phone may be missing; an identity may not — and that decision is part of the table's honesty about the world.
