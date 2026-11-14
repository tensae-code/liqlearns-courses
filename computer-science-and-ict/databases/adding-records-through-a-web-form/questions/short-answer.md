# Adding Records Through a Web Form — the Add_Term Page — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does the Add_Term page do?**
**Answer: Takes a term typed into a web form and stores it as a new record in the MySQL database**

**2. (Sub lesson 1) What is the form's job?**
**Answer: Gathering and naming — each field's name tells the receiving page which value is which**

**3. (Sub lesson 1) Why should form field lengths match the table's columns?**
**Answer: So what the visitor sends is already shaped like what the database can hold**

**4. (Sub lesson 1) What does the PHP page do first with the sent values?**
**Answer: Reads each value by its field name**

**5. (Sub lesson 1) What comes between reading and storing?**
**Answer: Checking — present, sane, and safe to store**

**6. (Sub lesson 2) Which operation adds the new record?**
**Answer: INSERT — adding one new record to the dictionary table**

**7. (Sub lesson 2) What must the page answer the visitor?**
**Answer: Whether the term was added — or not added, and why**

**8. (Sub lesson 2) What happens if a field name differs between form and page?**
**Answer: The value arrives as nothing**

**9. (Sub lesson 2) What fault follows a skipped check?**
**Answer: An empty or bad term gets stored**

**10. (Sub lesson 2) How does the circle close when the page works?**
**Answer: The next visitor searching the dictionary finds the term this visitor added**
