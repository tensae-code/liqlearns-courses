# Filtering by date, AND, OR and BETWEEN — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** SaleDate >= #2020-03-15# keeps a sale dated 15 March 2020 —
a) no, >= excludes its date  b) yes — >= includes the start date  c) only if it is large  d) only on weekdays
**Answer: b) yes — >= includes the start date** — >= is 'on and after'.

**2. (Sub lesson 1)** Dates in WHERE compare —
a) alphabetically  b) chronologically — later is greater  c) by amount  d) randomly
**Answer: b) chronologically — later is greater** — time order is the comparison.

**3. (Sub lesson 2)** Sales after 1 May 2020 AND over 12,000 matched how many records in the worked table?
a) four  b) one  c) all  d) none
**Answer: b) one** — AND narrows — one record met both.

**4. (Sub lesson 2)** Amount < 1000 OR Amount > 15000 matched —
a) one record  b) no records  c) four records  d) only the 15,000 row
**Answer: c) four records** — OR widens — four records met either side.

**5. (Sub lesson 3)** BETWEEN #2020-03-01# AND #2020-03-31# keeps sales on —
a) 1 March only  b) 31 March only  c) both 1 and 31 March  d) neither end
**Answer: c) both 1 and 31 March** — both endpoints are included.

**6. (Sub lesson 3)** BETWEEN x AND y is the same as —
a) value < x OR value > y  b) value >= x AND value <= y  c) value = x only  d) value > x AND value < y
**Answer: b) value >= x AND value <= y** — the inclusive range as two comparisons.
