# Video script — CREATE TABLE — building a table with SQL

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then. Full script — the placements name a walkthrough video for this lesson.

---

We build three tables. Student. Teacher. Grade.

Open Access. Create tab — Query Design. Close Show Table. SQL View.

Type: CREATE TABLE Student — bracket — StudentID, INTEGER, PRIMARY KEY — comma — FirstName, CHAR(30) — no space in the name — close the bracket. Run.

Teacher the same way. Its own key.

Now Grade. It holds two borrowed keys: one REFERENCES Student, one REFERENCES Teacher. Those lines are the relationships.

Check every comma. Check every bracket. A semicolon ends it cleanly.

Three tables standing, linked. That is DDL at work.
