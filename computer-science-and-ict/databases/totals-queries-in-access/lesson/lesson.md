# Totals Queries in Access

## Do it first

Selection queries fetch rows; sometimes the question is not rows but sums. How much per town? How many per class? Grade 12's Access course builds the query that aggregates.

## Sub lesson 1 — Group By and the aggregate functions

A **totals query** (switched on by the Totals button, adding the **Total row** to the grid) works in two moves. Fields marked **Group By** divide the records into **groups** (one per town, per class, per product). Fields carrying an **aggregate function** are then **collapsed** to one value per group: **Sum** totals, **Avg** averages, **Count** counts the records, **Min/Max** take the extremes. The result has **one row per group** — the table's shape after a summarising question.

In your mind's eye: group By and the aggregate functions.

[Picture 46618 — group By and the aggregate functions]

## Sub lesson 2 — Criteria in totals — before and after grouping

Criteria steer a totals query in **two different places**, and the grid's Where marks the difference: a criterion on a detail field with Total = **Where** filters records **before** grouping (only this year's sales enter the sums); a criterion typed under an aggregate column filters **groups after** summing (only towns whose Sum exceeds 10 000 are shown). Confusing the two is the totals query's classic error — the section's careful point: the same box, two different moments in the machine's work.

In your mind's eye: criteria in totals — before and after grouping.

[Picture 46619 — criteria in totals — before and after grouping]

## Say it to your companion

Tell your companion, in your own words: A **totals query** (switched on by the Totals button, adding the **Total row** to the grid) works in two moves. Fields marked **Group By** divide the records into **groups** (one per town, per class, per product). Fields carrying an **aggregate function** are then **collapsed** to one value per group: **Sum** totals, **Avg** averages, **Count** counts the records, **Min/Max** take the extremes. The result has **one row per group** — the table's shape after a summarising question. Criteria steer a totals query in **two different places**, and the grid's Where marks the difference: a criterion on a detail field with Total = **Where** filters records **before** grouping (only this year's sales enter the sums); a criterion typed under an aggregate column filters **groups after** summing (only towns whose Sum exceeds 10 000 are shown). Confusing the two is the totals query's classic error — the section's careful point: the same box, two different moments in the machine's work. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The Totals button — adding the Total row to the grid. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: It divides the records into groups — one group per value. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Sum, Avg, Count, Min and Max. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: One row per group. Do this with a real example of your own and write or say how you know it is right.
