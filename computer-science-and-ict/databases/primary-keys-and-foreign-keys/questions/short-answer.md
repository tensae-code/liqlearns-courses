# Primary keys and foreign keys — short answer

Answer in a sentence or two.

**1. (Sub lesson 1)** Why does “name” fail as a student table's primary key, but “student ID” succeed?
**Answer:** Names repeat — two students can share one — while the ID's value is unique for each record.

**2. (Sub lesson 2)** Define a foreign key.
**Answer:** An attribute in one table that matches the primary key of a related table.

**3. (Sub lesson 3)** What two questions does one Book_Loan row answer through its foreign keys?
**Answer:** Who borrowed (through its student ID, matching Student) and what was borrowed (through its book ID, matching Book).
