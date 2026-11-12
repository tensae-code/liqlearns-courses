# UPDATE — change rows, and never forget WHERE — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write the book's raise statement.
**Answer:** UPDATE Teacher SET Salary = 15000 WHERE Salary < 10000;

**2. (Sub lesson 2)** Write an UPDATE setting grade level 12 for the student with StudentID 103.
**Answer:** UPDATE Student SET GradeLevel = 12 WHERE StudentID = 103;

**3. (Sub lesson 3)** What single missing line makes an UPDATE dangerous, and why?
**Answer:** The WHERE line — without it, every row in the table is updated.
