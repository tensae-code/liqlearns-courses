# Video script — Characteristics of a Relational Database — Codd's Rules

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Codd's rules** state what a true RDBMS guarantees. Among their heads: all information is held as **values in tables** — nothing hides in pointers the user cannot see; every value is reachable by **table name, key and column name**; **nulls** are handled systematically (the companion lesson); the catalogue describing the database is itself stored as tables and queryable with the same language; and one **comprehensive language** (SQL) does everything — defining, querying, changing. A system failing the heads may be useful, but it is not fully relational.
The book closes with the **standard RDBMS list** — the systems the world's organisations actually run, from desktop-scale to the engines behind banks and governments, Bangladesh's own NID and passport databases among the companion lesson's examples. The rules matter beyond examinations because they are promises a buyer can test: data independent of the programs that use it, integrity the system itself enforces, and no back doors around the language. Choose a system by Codd's tests and the data will outlive every program written against it.
