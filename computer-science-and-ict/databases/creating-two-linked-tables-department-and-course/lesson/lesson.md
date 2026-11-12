# Creating two linked tables — DEPARTMENT and COURSE

## Do it first

A college has departments, and every course belongs to one department. On paper, list what you must know about a department (its name, its number, where it sits) and about a course (its name, its hours, which department runs it). That last course fact — *which department* — is the bridge. This lesson builds both tables with the bridge inside the second one.

## Sub lesson 1 — DEPARTMENT — the one side

```sql
CREATE TABLE DEPARTMENT (
  D_Name CHAR(30),
  D_Number CHAR(10) PRIMARY KEY,
  D_Location CHAR(20)
);
```

**D_Number** is the department's primary key — the value every link will point at. Note its type: **CHAR(10)**. Remember it; the next table must match it.


## Sub lesson 2 — COURSE — with the foreign key inside

```sql
CREATE TABLE COURSE (
  Contact_Hr INTEGER,
  C_Name CHAR(30),
  C_Description TEXT,
  C_Department CHAR(10),
  C_Code CHAR(10) PRIMARY KEY,
  FOREIGN KEY (C_Department) REFERENCES DEPARTMENT(D_Number)
);
```

**C_Department** becomes a foreign key by two moves together: it is given **the same data type as D_Number — CHAR(10)** — and it is followed by **REFERENCES DEPARTMENT(D_Number)**. Type match plus the reference: both are needed.


## Sub lesson 3 — Set the relationship before the data

Do **not** add data to a table before its relationship is set up. Records entered first that break the requirement will produce errors when the link is enforced.

Order of work: create DEPARTMENT, create COURSE with its reference, then — in the lessons after this one — fill them.


## Say it to your companion

Tell your companion which column in COURSE is the foreign key, and the two moves that made it one.

## Do It Yourself

1. Write both CREATE statements from memory, then check them against the lesson.
2. Say what breaks if C_Department is CHAR(15) while D_Number is CHAR(10).
3. Explain why records are not inserted before the relationship exists.
