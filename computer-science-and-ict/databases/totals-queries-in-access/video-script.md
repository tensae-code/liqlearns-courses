# Video script — Totals Queries in Access

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **totals query** (switched on by the Totals button, adding the **Total row** to the grid) works in two moves. Fields marked **Group By** divide the records into **groups** (one per town, per class, per product). Fields carrying an **aggregate function** are then **collapsed** to one value per group: **Sum** totals, **Avg** averages, **Count** counts the records, **Min/Max** take the extremes. The result has **one row per group** — the table's shape after a summarising question.
Criteria steer a totals query in **two different places**, and the grid's Where marks the difference: a criterion on a detail field with Total = **Where** filters records **before** grouping (only this year's sales enter the sums); a criterion typed under an aggregate column filters **groups after** summing (only towns whose Sum exceeds 10 000 are shown). Confusing the two is the totals query's classic error — the section's careful point: the same box, two different moments in the machine's work.
