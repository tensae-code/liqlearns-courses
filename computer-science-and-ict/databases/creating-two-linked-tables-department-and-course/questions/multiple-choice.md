# Creating two linked tables — DEPARTMENT and COURSE — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** DEPARTMENT's primary key is —
a) D_Name  b) D_Location  c) D_Number  d) C_Code
**Answer: c) D_Number** — D_Number is marked PRIMARY KEY.

**2. (Sub lesson 1)** D_Number's data type is —
a) INTEGER  b) CHAR(10)  c) TEXT  d) CURRENCY
**Answer: b) CHAR(10)** — CHAR(10) — the type COURSE must match.

**3. (Sub lesson 2)** C_Department becomes a foreign key by —
a) its name alone  b) matching D_Number's type and REFERENCES DEPARTMENT(D_Number)  c) being first in the list  d) holding numbers only
**Answer: b) matching D_Number's type and REFERENCES DEPARTMENT(D_Number)** — both moves together make the link.

**4. (Sub lesson 2)** COURSE's own primary key is —
a) C_Name  b) Contact_Hr  c) C_Code  d) C_Department
**Answer: c) C_Code** — C_Code is marked PRIMARY KEY.

**5. (Sub lesson 3)** Data should be added to these tables —
a) before the relationship, to save time  b) only after the relationship is set up  c) never  d) into DEPARTMENT only
**Answer: b) only after the relationship is set up** — records entered first that break the requirement produce errors.

**6. (Sub lesson 3)** If C_Department were CHAR(15) against D_Number CHAR(10), the link —
a) works better  b) is a type mismatch and must be fixed to match  c) changes D_Number  d) is ignored
**Answer: b) is a type mismatch and must be fixed to match** — foreign and primary key types must match.
