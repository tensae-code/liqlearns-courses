# Creating two linked tables — DEPARTMENT and COURSE — true or false

Say true or false.

**1. (Sub lesson 1)** D_Number is a primary key, so two departments may share one D_Number.
**Answer: False** — a primary key's value is unique for each record.

**2. (Sub lesson 2)** REFERENCES DEPARTMENT(D_Number) names the table and key column C_Department points at.
**Answer: True** — that is what the reference clause says.

**3. (Sub lesson 2)** C_Department and D_Number may have different data types and still link cleanly.
**Answer: False** — their types must match.

**4. (Sub lesson 3)** Adding records before setting up a relationship can produce errors.
**Answer: True** — the book warns exactly this.
