# ORDER BY — ascending and descending results — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write teachers by salary, highest first.
**Answer:** SELECT TeacherName, Salary FROM Teacher ORDER BY Salary DESC;

**2. (Sub lesson 2)** Write students by name alphabetically, shortest form.
**Answer:** SELECT * FROM Student ORDER BY FirstName;

**3. (Sub lesson 3)** In one sentence: where does ordering live?
**Answer:** In the query's output only — the table itself is unchanged.
