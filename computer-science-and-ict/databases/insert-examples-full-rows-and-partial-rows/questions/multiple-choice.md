# INSERT examples — full rows and partial rows — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** In the full COURSE insert, '105' is quoted because —
a) it is the largest value  b) its field is a string type  c) it is a key  d) all codes are quoted
**Answer: b) its field is a string type** — quotes follow the field's type.

**2. (Sub lesson 1)** The last value, 'CS101', lands in —
a) C_Name  b) C_Department  c) C_Code, the primary key  d) Contact_Hr
**Answer: c) C_Code, the primary key** — form 1 follows the table's order; C_Code stands last.

**3. (Sub lesson 2)** In form 2, matching is governed by —
a) the table's raw order only  b) the order of the column list you wrote  c) alphabetical order  d) the key first always
**Answer: b) the order of the column list you wrote** — values answer your named list in its order.

**4. (Sub lesson 3)** C_Description omitted from the column list means the new record's description is —
a) an error  b) filled with the previous record's text  c) left blank (or given a default)  d) set to the course code
**Answer: c) left blank (or given a default)** — unmentioned fields are left blank or defaulted.

**5. (Sub lesson 3)** Omitting a field in form 2 is —
a) never allowed  b) allowed for ordinary fields; the record is still created  c) the same as deleting the field  d) a DROP
**Answer: b) allowed for ordinary fields; the record is still created** — the record is created with that cell blank.

**6. (Sub lesson 3)** All unmentioned fields in a partial insert —
a) copy the row above  b) behave the same way: blank or default  c) reject the insert  d) become keys
**Answer: b) behave the same way: blank or default** — the book states this for every unmentioned field.
