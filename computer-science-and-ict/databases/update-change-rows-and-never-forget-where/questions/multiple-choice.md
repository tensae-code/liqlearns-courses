# UPDATE — change rows, and never forget WHERE — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** UPDATE does what to rows?
a) adds new rows  b) removes rows  c) changes values in existing rows  d) creates the table
**Answer: c) changes values in existing rows** — no rows are added or removed.

**2. (Sub lesson 1)** In the raise, SET Salary = 15000 with WHERE Salary < 10000 changes —
a) all teachers  b) only teachers below 10,000  c) only the first teacher  d) no teachers
**Answer: b) only teachers below 10,000** — WHERE chooses the rows.

**3. (Sub lesson 2)** To change all female teachers at once, you —
a) run one UPDATE per teacher  b) widen the WHERE to Sex = 'F' in one statement  c) drop and rebuild the table  d) use SELECT
**Answer: b) widen the WHERE to Sex = 'F' in one statement** — one statement, group-wide WHERE.

**4. (Sub lesson 2)** To change exactly one student, the WHERE should name —
a) their name, which may repeat  b) their primary key value  c) their sex  d) their class
**Answer: b) their primary key value** — the key identifies one record exactly.

**5. (Sub lesson 3)** An UPDATE with no WHERE —
a) fails to run  b) changes only key rows  c) updates every row in the table  d) updates nothing
**Answer: c) updates every row in the table** — that is the book's warning.

**6. (Sub lesson 3)** The guide's no-condition UPDATE setting every student's grade level is —
a) always an accident  b) right only when every row truly is the intent  c) a SELECT  d) impossible
**Answer: b) right only when every row truly is the intent** — deliberate all-rows changes exist — intent is the test.
