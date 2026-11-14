# Aggregate Functions in SQL — true-false

Say whether each statement is true or false.

**1. (Sub lesson 1) True or false: the answer to "What does an aggregate function take and return?" is: A whole column across many records — and one value back**
**Answer: True**

**2. (Sub lesson 1) True or false: the answer to "What does COUNT(*) count?" is: SUM totals a numeric column; AVG averages it**
**Answer: False** — Records

**3. (Sub lesson 1) True or false: the answer to "What do SUM and AVG do?" is: SUM totals a numeric column; AVG averages it**
**Answer: True**

**4. (Sub lesson 1) True or false: the answer to "What do MAX and MIN return?" is: A single number — the size of the whole table**
**Answer: False** — The column's largest and smallest values

**5. (Sub lesson 1) True or false: the answer to "What does SELECT COUNT(*) FROM Pupil; return?" is: A single number — the size of the whole table**
**Answer: True**

**6. (Sub lesson 2) True or false: the answer to "How are aggregates pointed at chosen records?" is: One summary per group — an average for each class**
**Answer: False** — A WHERE clause selects the records first

**7. (Sub lesson 2) True or false: the answer to "What does GROUP BY add?" is: One summary per group — an average for each class**
**Answer: True**

**8. (Sub lesson 2) True or false: the answer to "What is the honest order of reading?" is: Expecting both the summary and the records from one plain SELECT**
**Answer: False** — Records chosen, then grouped, then each group summarised

**9. (Sub lesson 2) True or false: the answer to "What is the common fault?" is: Expecting both the summary and the records from one plain SELECT**
**Answer: True**

**10. (Sub lesson 2) True or false: the answer to "Write the query for the average Maths mark." is: A whole column across many records — and one value back**
**Answer: False** — SELECT AVG(Mark) FROM Result WHERE Subject = 'Maths';

