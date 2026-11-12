# INSERT — adding a record to a table — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write form 1 adding a course row: 45, 'Networks', 'Routing', '105', 'CS102'.
**Answer:** INSERT INTO COURSE VALUES (45, 'Networks', 'Routing', '105', 'CS102');

**2. (Sub lesson 2)** Write form 2 naming D_Number and D_Name for department '107', 'Biology'.
**Answer:** INSERT INTO DEPARTMENT (D_Number, D_Name) VALUES ('107', 'Biology');

**3. (Sub lesson 3)** Why is '105' quoted in the COURSE insert but 45 is not?
**Answer:** '105' belongs to a string-typed field; 45 is a numeric value, and numbers are not quoted.
