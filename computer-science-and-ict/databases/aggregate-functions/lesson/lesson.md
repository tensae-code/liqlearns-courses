# Aggregate Functions in SQL

## Do it first

Most SQL questions ask for records. Some ask for one number about all the records: how many, how much in total, what average. Malaysia's advanced SQL chapter gives those questions their own functions. In this lesson you summarise with COUNT, SUM, AVG, MAX and MIN.

## Sub lesson 1 — Five functions, one answer each

An **aggregate function** takes a **whole column across many records** and returns **one value**. **COUNT** counts records (COUNT(*) counts records; COUNT(column) counts its non-empty values). **SUM** totals a numeric column; **AVG** averages it; **MAX** and **MIN** return its largest and smallest values. Written in a SELECT, the aggregate replaces the record list: SELECT COUNT(*) FROM Pupil; answers a single number — the size of the whole table — not a page of rows.

In your mind's eye: five functions, one answer each.

[Picture 46457 — five functions, one answer each]

## Sub lesson 2 — Aggregates with conditions and groups

Aggregates answer about **chosen records** when a WHERE clause selects them first (SELECT AVG(Mark) FROM Result WHERE Subject = 'Maths';), and about **each group separately** with **GROUP BY** (SELECT Class, AVG(Mark) FROM Result GROUP BY Class; gives one average per class). Malaysia's order of reading keeps the machine's order honest: the records are chosen, then grouped, then each group is summarised. The common fault is expecting both the summary and the records from one plain SELECT — an aggregate query returns summaries; the records stay in the table.

In your mind's eye: aggregates with conditions and groups.

[Picture 46458 — aggregates with conditions and groups]

## Say it to your companion

Tell your companion, in your own words: An **aggregate function** takes a **whole column across many records** and returns **one value**. **COUNT** counts records (COUNT(*) counts records; COUNT(column) counts its non-empty values). **SUM** totals a numeric column; **AVG** averages it; **MAX** and **MIN** return its largest and smallest values. Written in a SELECT, the aggregate replaces the record list: SELECT COUNT(*) FROM Pupil; answers a single number — the size of the whole table — not a page of rows. Aggregates answer about **chosen records** when a WHERE clause selects them first (SELECT AVG(Mark) FROM Result WHERE Subject = 'Maths';), and about **each group separately** with **GROUP BY** (SELECT Class, AVG(Mark) FROM Result GROUP BY Class; gives one average per class). Malaysia's order of reading keeps the machine's order honest: the records are chosen, then grouped, then each group is summarised. The common fault is expecting both the summary and the records from one plain SELECT — an aggregate query returns summaries; the records stay in the table. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A whole column across many records — and one value back. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Records. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: SUM totals a numeric column; AVG averages it. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A WHERE clause selects the records first. Do this with a real example of your own and write or say how you know it is right.
