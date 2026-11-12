# Queries across multiple tables — short answer

Answer in a sentence or two.

**1. (Sub lesson 1)** Why must all three tables — Student, Grade, Teacher — be added for the book's example?
**Answer:** The answer's fields live in all three: name in Student, subject and grade in Grade, teacher name in Teacher; a field cannot be picked from a table that is not there.

**2. (Sub lesson 2)** What does the join line mean, in the language of the keys lesson?
**Answer:** It is the foreign-key link made visible: the child's matching field refers to the parent's primary key, so rows join where those values match.

**3. (Sub lesson 3)** List the book example's four display fields with the table each comes from.
**Answer:** Student name — Student; subject — Grade; grade — Grade; teacher name — Teacher.

**4. (Sub lesson 4)** Write the join listing course names with their semesters.
**Answer:** SELECT COURSE.C_Name, CourseOffering.Semester FROM COURSE, CourseOffering WHERE COURSE.C_Code = CourseOffering.Code;

**5. (Sub lesson 4)** Name the six project steps briefly.
**Answer:** Choose a real problem; identify entities and attributes; identify relationships; implement the tables in Access; insert at least three records per table; modify a table by adding a column — and write queries to select records.
