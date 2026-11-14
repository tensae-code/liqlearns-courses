# Collecting and Analysing Data With Python

## Do it first

The unit's theory ends; the practice begins at the file. This lesson loads real data into Python and looks at all of it — the analyst's first honest act.

## Sub lesson 1 — Loading — the file becomes a table

Python analysis begins by **loading a data file** — a CSV or similar — into a table structure (with the data library, a DataFrame): the file's rows become the table's rows, its first line the column names. Loading is checked, not assumed: the shape (rows × columns), the column names and types, and the first and last rows are inspected, because a file silently misread — a shifted column, a swallowed header — poisons every later number while looking like success.

[Picture — Loading — the file becomes a table]

## Sub lesson 2 — Displaying in full — meeting the whole data

Jordan insists on **displaying the data in full** at the start: the whole table printed or scrolled, not a sample — so the analyst's eye meets the missing values, the strange entry, the column that is all one value, before any statistic hides them inside an average. Only after the full look do the unit's later tools (statistics, charts) earn their turn. The habit is the lesson: in Python the commands are short, so the discipline must be deliberate — load, look at everything, then analyse.

[Picture — Displaying in full — meeting the whole data]

## Say it to your companion

Tell your companion, in your own words: Python analysis begins by **loading a data file** — a CSV or similar — into a table structure (with the data library, a DataFrame): the file's rows become the table's rows, its first line the column names. Loading is checked, not assumed: the shape (rows × columns), the column names and types, and the first and last rows are inspected, because a file silently misread — a shifted column, a swallowed header — poisons every later number while looking like success. Jordan insists on **displaying the data in full** at the start: the whole table printed or scrolled, not a sample — so the analyst's eye meets the missing values, the strange entry, the column that is all one value, before any statistic hides them inside an average. Only after the full look do the unit's later tools (statistics, charts) earn their turn. The habit is the lesson: in Python the commands are short, so the discipline must be deliberate — load, look at everything, then analyse. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A table — rows as rows, first line as column names. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A DataFrame (with the data library). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The shape, the column names and types, the first and last rows. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Poisons every later number while looking like success. Do this with a real example of your own and write or say how you know it is right.
