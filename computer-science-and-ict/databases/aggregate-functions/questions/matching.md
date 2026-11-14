# Aggregate Functions in SQL — matching

Match each question on the left with its answer on the right. Write the letter beside each number.

1. (Sub lesson 1) What does an aggregate function take and return?
2. (Sub lesson 1) What does COUNT(*) count?
3. (Sub lesson 1) What do SUM and AVG do?
4. (Sub lesson 1) What do MAX and MIN return?
5. (Sub lesson 1) What does SELECT COUNT(*) FROM Pupil; return?
6. (Sub lesson 2) How are aggregates pointed at chosen records?
7. (Sub lesson 2) What does GROUP BY add?
8. (Sub lesson 2) What is the honest order of reading?
9. (Sub lesson 2) What is the common fault?
10. (Sub lesson 2) Write the query for the average Maths mark.

a) Records
b) The column's largest and smallest values
c) A whole column across many records — and one value back
d) A single number — the size of the whole table
e) SUM totals a numeric column; AVG averages it
f) One summary per group — an average for each class
g) Expecting both the summary and the records from one plain SELECT
h) A WHERE clause selects the records first
i) SELECT AVG(Mark) FROM Result WHERE Subject = 'Maths';
j) Records chosen, then grouped, then each group summarised

**Answer key:** 1–c, 2–a, 3–e, 4–b, 5–d, 6–h, 7–f, 8–j, 9–g, 10–i
