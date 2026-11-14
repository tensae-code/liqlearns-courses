# Data Analysis with Python Tools

## Do it first

The clean table from the last lesson sits in front of you: four hundred pupils, their subjects, their marks. A head teacher asks: which subject fell furthest? Do girls and boys differ? Is the fall in one class or everywhere? Answering by hand would take a week of counting. With Python's tools it takes an afternoon — if you know what questions to ask. This lesson is about the asking.

## Sub lesson 1 — What data analysis asks

Analysis is **questioning a table**. The standard questions recur everywhere: **totals and counts** (how much, how many), **averages** (the typical value), **grouping** (split the data by a column — by class, by subject, by month — and summarise each group), **comparison** (groups against each other, this year against last), and **patterns** (does a value rise, fall, or move with another?). Every finding is one of these questions answered. The craft is choosing the question that matches the decision at stake: 'results fell' is a complaint; 'results fell in mathematics, in Grade 9, in the second term' is a finding someone can act on.

[Picture — a big table with five speech bubbles above it — 'how many in total?', 'what is typical?', 'split it by class', 'this year against last?', 'is it rising or falling?']

## Sub lesson 2 — Doing it with Python tools

Python's data tools (the lesson works with its table-handling libraries) follow a steady rhythm. **Load** the clean table into the program. **Select** the columns and rows the question needs. **Group** by the chosen column and **compute** the summaries — sum, count, average — for each group. **Sort** the results so the biggest fall or the highest group stands first. Then **read**: the output is still just numbers until the analyst states what they mean in words a decision-maker can use. The tool does the counting in seconds; the thinking — which question, which grouping, what the answer means — stays human, and garbage groupings give garbage findings as surely as dirty data did.

[Picture — a table on a screen splitting into coloured groups by class, each group shrinking to its average, the groups lining up tallest to shortest]

## Say it to your companion

Tell your companion, in your own words: analysis questions a table — totals, averages, groupings, comparisons, patterns — and Python tools follow load, select, group, compute, sort, read; the tool counts, but choosing the question and stating the meaning stays human. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: name the standard analysis questions: totals/counts, averages, grouping, comparison, patterns. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: describe the Python rhythm: load, select, group, compute, sort, read. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: explain why the grouping chosen decides what finding is possible. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: turn a vague complaint ('results fell') into an analysable question and state its finding in words. Do this with a real example of your own and write or say how you know it is right.
