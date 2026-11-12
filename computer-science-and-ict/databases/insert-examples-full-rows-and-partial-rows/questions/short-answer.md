# INSERT examples — full rows and partial rows — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write the partial COURSE insert from the lesson (no description).
**Answer:** INSERT INTO COURSE (C_Code, C_Name, Contact_Hr, C_Department) VALUES ('CS102', 'Networks', 45, '105');

**2. (Sub lesson 2)** What will C_Description hold in that new record?
**Answer:** Nothing — it is left blank (or given a default).

**3. (Sub lesson 3)** Why is '105' quoted while 45 is not, in the same statement?
**Answer:** C_Department is a string-typed field; Contact_Hr is numeric.
