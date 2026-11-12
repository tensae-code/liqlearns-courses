# Creating two linked tables — DEPARTMENT and COURSE — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write DEPARTMENT's key line as it appears in its CREATE.
**Answer:** D_Number CHAR(10) PRIMARY KEY

**2. (Sub lesson 2)** Write the foreign-key line for COURSE.
**Answer:** FOREIGN KEY (C_Department) REFERENCES DEPARTMENT(D_Number)

**3. (Sub lesson 3)** In one sentence: why must C_Department be CHAR(10)?
**Answer:** Because the primary key it references, D_Number, is CHAR(10) — the types must match.
