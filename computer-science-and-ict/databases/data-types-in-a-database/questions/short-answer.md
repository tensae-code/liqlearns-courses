# Data Types in a Database — short answer

Answer in a sentence or two, in your own words.

**1. (Sub lesson 1) A shop's table needs a column for the price of each item, prices like 99.99. Which type, and why not INT?**
**Answer:** DECIMAL. INT holds whole numbers only and would lose the .99 part; DECIMAL stores the price exactly as written.

**2. (Sub lesson 2) A school code is always exactly four characters long, like "G10A". Which text type fits best, and why?**
**Answer:** CHAR with length 4. CHAR holds fixed-length text, and every value here is the same fixed length.

**3. (Sub lesson 3) A library stores the day each book was borrowed in a text column, and its "oldest loan first" list comes out wrong. Why, and what fixes it?**
**Answer:** Text sorts character by character, not day by day, so the order is wrong. Storing the day in a DATE column lets the database sort truly and count days between dates.
