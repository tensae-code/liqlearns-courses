# Video script — Collecting and Analysing Data With Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Python analysis begins by **loading a data file** — a CSV or similar — into a table structure (with the data library, a DataFrame): the file's rows become the table's rows, its first line the column names. Loading is checked, not assumed: the shape (rows × columns), the column names and types, and the first and last rows are inspected, because a file silently misread — a shifted column, a swallowed header — poisons every later number while looking like success.
Jordan insists on **displaying the data in full** at the start: the whole table printed or scrolled, not a sample — so the analyst's eye meets the missing values, the strange entry, the column that is all one value, before any statistic hides them inside an average. Only after the full look do the unit's later tools (statistics, charts) earn their turn. The habit is the lesson: in Python the commands are short, so the discipline must be deliberate — load, look at everything, then analyse.
