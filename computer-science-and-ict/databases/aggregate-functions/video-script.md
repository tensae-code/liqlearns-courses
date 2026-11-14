# Video script — Aggregate Functions in SQL

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **aggregate function** takes a **whole column across many records** and returns **one value**. **COUNT** counts records (COUNT(*) counts records; COUNT(column) counts its non-empty values). **SUM** totals a numeric column; **AVG** averages it; **MAX** and **MIN** return its largest and smallest values. Written in a SELECT, the aggregate replaces the record list: SELECT COUNT(*) FROM Pupil; answers a single number — the size of the whole table — not a page of rows.
Aggregates answer about **chosen records** when a WHERE clause selects them first (SELECT AVG(Mark) FROM Result WHERE Subject = 'Maths';), and about **each group separately** with **GROUP BY** (SELECT Class, AVG(Mark) FROM Result GROUP BY Class; gives one average per class). Malaysia's order of reading keeps the machine's order honest: the records are chosen, then grouped, then each group is summarised. The common fault is expecting both the summary and the records from one plain SELECT — an aggregate query returns summaries; the records stay in the table.
