# Video script — Maintaining a Database

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Deleting records and objects in Access **does not shrink the file**: the space stays claimed, as gaps — the file **bloats**, slows, and over years can corrupt. **Compact and Repair** is the cure: it **rebuilds the database file** — records recopied in order, gaps dropped, indexes rebuilt, and detected damage repaired where possible. The course's rule makes it a routine, not a rescue: compact **regularly** (weekly in working databases, always after mass deletions), and only ever on a **copy kept safe** until the compacted file proves sound.
The rest of maintenance is standing defence. **Backups**: dated copies of the file, kept apart from the working machine, on a rhythm the data's value sets — the only true repair for corruption, theft or fire. **Splitting**: a working database is divided into a **back-end** (tables only, on the shared place) and **front-ends** (queries, forms, reports on each user's machine), so many users share data without sharing damage. **Protection**: passwords and permissions keep the merely curious and the careless from the tables. Maintenance is unglamorous and decisive: databases rarely die of hard questions — they die **unkept**.
