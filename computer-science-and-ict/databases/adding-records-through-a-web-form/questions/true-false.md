# Adding Records Through a Web Form — the Add_Term Page — true-false

Say whether each statement is true or false.

**1. (Sub lesson 1) True or false: the answer to "What does the Add_Term page do?" is: Takes a term typed into a web form and stores it as a new record in the MySQL database**
**Answer: True**

**2. (Sub lesson 1) True or false: the answer to "What is the form's job?" is: So what the visitor sends is already shaped like what the database can hold**
**Answer: False** — Gathering and naming — each field's name tells the receiving page which value is which

**3. (Sub lesson 1) True or false: the answer to "Why should form field lengths match the table's columns?" is: So what the visitor sends is already shaped like what the database can hold**
**Answer: True**

**4. (Sub lesson 1) True or false: the answer to "What does the PHP page do first with the sent values?" is: Checking — present, sane, and safe to store**
**Answer: False** — Reads each value by its field name

**5. (Sub lesson 1) True or false: the answer to "What comes between reading and storing?" is: Checking — present, sane, and safe to store**
**Answer: True**

**6. (Sub lesson 2) True or false: the answer to "Which operation adds the new record?" is: Whether the term was added — or not added, and why**
**Answer: False** — INSERT — adding one new record to the dictionary table

**7. (Sub lesson 2) True or false: the answer to "What must the page answer the visitor?" is: Whether the term was added — or not added, and why**
**Answer: True**

**8. (Sub lesson 2) True or false: the answer to "What happens if a field name differs between form and page?" is: An empty or bad term gets stored**
**Answer: False** — The value arrives as nothing

**9. (Sub lesson 2) True or false: the answer to "What fault follows a skipped check?" is: An empty or bad term gets stored**
**Answer: True**

**10. (Sub lesson 2) True or false: the answer to "How does the circle close when the page works?" is: Takes a term typed into a web form and stores it as a new record in the MySQL database**
**Answer: False** — The next visitor searching the dictionary finds the term this visitor added
