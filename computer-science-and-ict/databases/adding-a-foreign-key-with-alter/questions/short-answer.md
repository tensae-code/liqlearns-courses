# Adding a foreign key with ALTER — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write the full ALTER linking COURSE to DEPARTMENT.
**Answer:** ALTER TABLE COURSE ADD FOREIGN KEY (C_Department) REFERENCES DEPARTMENT (D_Number);

**2. (Sub lesson 2)** In that statement, which column is the foreign key?
**Answer:** C_Department.

**3. (Sub lesson 2)** Name the four things the bridge statement names, in order.
**Answer:** The table altered (COURSE), its foreign-key column (C_Department), the referenced table (DEPARTMENT), its key column (D_Number).
