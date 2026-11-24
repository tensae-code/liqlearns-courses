# Aggregate Functions — Count and Average with GROUP BY

## Do it first

Earlier queries fetch rows. This one asks about crowds: not 'show the students' but 'how many in each class?' Kuwait's relational year teaches the aggregate question — one answer per group. This lesson is counting and averaging over groups.

## Sub lesson 1 — Aggregates — one answer from many rows

An **aggregate function** takes **many rows and returns one value**: **COUNT** returns how many rows there are; **AVERAGE (AVG)** returns their mean. The question changes shape — the answer is no longer a row of the table but a fact **about** the table: the course's examples are a head-count and a price's average, the two questions every store of records eventually gets asked.

In your mind's eye: aggregates — one answer from many rows.

## Sub lesson 2 — GROUP BY — one answer per group

**GROUP BY** splits the table into **groups** that share a value, and the aggregate is computed **once per group**: COUNT the students **in each class** — one count per class, not one count overall; the landmarks **grouped by region**, with their **average entry price** per region. Read a grouped query in two beats: the grouping names the crowds, the aggregate asks each crowd its question.

In your mind's eye: gROUP BY — one answer per group.

## Say it to your companion

Tell your companion, in your own words: An **aggregate function** takes **many rows and returns one value**: **COUNT** returns how many rows there are; **AVERAGE (AVG)** returns their mean. The question changes shape — the answer is no longer a row of the table but a fact **about** the table: the course's examples are a head-count and a price's average, the two questions every store of records eventually gets asked. **GROUP BY** splits the table into **groups** that share a value, and the aggregate is computed **once per group**: COUNT the students **in each class** — one count per class, not one count overall; the landmarks **grouped by region**, with their **average entry price** per region. Read a grouped query in two beats: the grouping names the crowds, the aggregate asks each crowd its question. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: One value computed from many rows. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: COUNT: how many rows. AVG: their mean (average). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Counting students in each class; landmarks' average entry price by region. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Splits the table into groups sharing a value, one aggregate per group. Do this with a real example of your own and write or say how you know it is right.
