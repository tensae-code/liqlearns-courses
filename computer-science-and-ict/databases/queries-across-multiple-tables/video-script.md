# Video script — Queries across multiple tables

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

FULL script — the multi-table query walkthrough named in the placement for this lesson (item 40).

---

One table cannot answer every question. The student's name is in one table. The grade is in another. The teacher's name is in a third.

Today the tables answer together.

Open Query Design. The Show Table box appears. Add each table you need — Student. Grade. Teacher. Click Add for each one. Three tables now stand in the window.

But standing side by side is not joined. Access does not yet know how they connect. You show it — with one drag.

Find the primary key of the parent table — the field that identifies each record. Drag it, slowly, onto the matching field in the child table. Let go. A line appears.

That line is the relationship. It says: these fields match; join here. Join every pair of tables your question crosses.

Now pick the fields, from each table in turn. Student name — from Student. Subject and grade — from Grade. Teacher name — from Teacher. Each picked field becomes one column of the answer.

Save the query. Give it a name that says what it answers.

Now view the results. Look at one row: a name from one table, a grade from another, a teacher from a third — one combined answer that no single table held.

That is why the database is called relational. The tables relate — and through the relationships, they answer together.

Your practice: Student and Grade, joined — and then the harder one: only the students scoring above 85 in all subjects.
