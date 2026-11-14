# Video script — Creating a Database in SQLite with SQLiteAdministrator

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**SQLite** is a **database management system** that stores the whole database — tables, records, everything — in **a single file** on the disk. It is **free software**, needs no server and no administrator account, which is why a school can run it anywhere. **SQLiteAdministrator** is the **graphical tool** for working with it: databases are opened, created and edited through its windows instead of typed commands. Cuba teaches the pair explicitly as preparation: the database made here is the one later programming in LiveCode will use.
The creation order is the database's own structure, outside in: **create the new database file** and name it; inside it, **create each table** the data needs; inside each table, define its **fields** — name and type for each column the records will carry; then **save**, and the file exists holding empty tables ready for records. A field defined wrongly here is paid for by every record after it, so the design — what tables, what fields — is settled before the first table is made.
