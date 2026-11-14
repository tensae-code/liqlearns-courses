# Aggregate Functions in SQL — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does an aggregate function take and return?**
**Answer: A whole column across many records — and one value back**

**2. (Sub lesson 1) What does COUNT(*) count?**
**Answer: Records**

**3. (Sub lesson 1) What do SUM and AVG do?**
**Answer: SUM totals a numeric column; AVG averages it**

**4. (Sub lesson 1) What do MAX and MIN return?**
**Answer: The column's largest and smallest values**

**5. (Sub lesson 1) What does SELECT COUNT(*) FROM Pupil; return?**
**Answer: A single number — the size of the whole table**

**6. (Sub lesson 2) How are aggregates pointed at chosen records?**
**Answer: A WHERE clause selects the records first**

**7. (Sub lesson 2) What does GROUP BY add?**
**Answer: One summary per group — an average for each class**

**8. (Sub lesson 2) What is the honest order of reading?**
**Answer: Records chosen, then grouped, then each group summarised**

**9. (Sub lesson 2) What is the common fault?**
**Answer: Expecting both the summary and the records from one plain SELECT**

**10. (Sub lesson 2) Write the query for the average Maths mark.**
**Answer: SELECT AVG(Mark) FROM Result WHERE Subject = 'Maths';**

