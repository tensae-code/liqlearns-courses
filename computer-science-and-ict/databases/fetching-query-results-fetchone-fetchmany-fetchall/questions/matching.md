# Fetching Query Results — fetchone, fetchmany, fetchall — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) Where do a SELECT's results wait?** → **On the cursor — the query's answer, held by the database side**

**2. (Sub lesson 1) What does fetching do?** → **Moves rows from the cursor into the program**

**3. (Sub lesson 1) Until a row is fetched, whose is it?** → **Not the program's — the query was asked but nothing was heard**

**4. (Sub lesson 1) What does fetchone take?** → **The next one row**

**5. (Sub lesson 1) When is fetchone right?** → **For questions with a single answer**

**6. (Sub lesson 2) What does fetchmany take?** → **The next counted rows — answers taken in mouthfuls**

**7. (Sub lesson 2) What does fetchall take?** → **Every remaining row at once, as a list**

**8. (Sub lesson 2) When is fetchall dangerous?** → **On a very large store — a million rows held at once**

**9. (Sub lesson 2) What is choosing the fetch, really?** → **Choosing how the program will hold the answer**

**10. (Sub lesson 2) Which book teaches this?** → **Kuwait Grade 11 Information Technology Term 1, Unit 1 Lesson 5**
