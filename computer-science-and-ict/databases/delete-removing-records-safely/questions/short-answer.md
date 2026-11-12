# DELETE — removing records safely — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write the DELETE for StudentID 103.
**Answer:** DELETE FROM Student WHERE StudentID = 103;

**2. (Sub lesson 2)** Write both all-rows forms for the Student table.
**Answer:** DELETE * FROM Student; / DELETE FROM Student;

**3. (Sub lesson 3)** State the deletion order for closing a department, and why.
**Answer:** Delete its many-side records (students, teachers, courses) first, then the department — so no records are left pointing at a removed parent.
