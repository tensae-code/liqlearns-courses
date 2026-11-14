# Video script — Aggregate Functions — Count and Average with GROUP BY

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **aggregate function** takes **many rows and returns one value**: **COUNT** returns how many rows there are; **AVERAGE (AVG)** returns their mean. The question changes shape — the answer is no longer a row of the table but a fact **about** the table: the course's examples are a head-count and a price's average, the two questions every store of records eventually gets asked.
**GROUP BY** splits the table into **groups** that share a value, and the aggregate is computed **once per group**: COUNT the students **in each class** — one count per class, not one count overall; the landmarks **grouped by region**, with their **average entry price** per region. Read a grouped query in two beats: the grouping names the crowds, the aggregate asks each crowd its question.
