# Filtering by date, AND, OR and BETWEEN — short answer

Answer in a word, a line of SQL, or one short sentence.

**1. (Sub lesson 1)** Write the query for sales on and after 15 March 2020.
**Answer:** SELECT * FROM Sales WHERE SaleDate >= #2020-03-15#;

**2. (Sub lesson 2)** Write the AND query: after 1 May 2020 and amount over 12,000.
**Answer:** SELECT * FROM Sales WHERE SaleDate > #2020-05-01# AND Amount > 12000;

**3. (Sub lesson 3)** Write the BETWEEN query for sales in March 2020.
**Answer:** SELECT * FROM Sales WHERE SaleDate BETWEEN #2020-03-01# AND #2020-03-31#;
