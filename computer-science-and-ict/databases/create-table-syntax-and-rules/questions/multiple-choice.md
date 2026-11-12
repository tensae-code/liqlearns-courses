# CREATE TABLE — building a table with SQL — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** In CREATE TABLE, the column list goes —
a) before the table name  b) in parentheses after the table name  c) in a second statement  d) in the FROM clause
**Answer: b) in parentheses after the table name** — name the table, then the parenthesised column list.

**2. (Sub lesson 1)** Each column definition must give —
a) a name only  b) a type only  c) a name and a data type  d) a value
**Answer: c) a name and a data type** — every column needs both.

**3. (Sub lesson 2)** Column definitions inside the parentheses are separated by —
a) full stops  b) semicolons  c) commas  d) spaces only
**Answer: c) commas** — commas separate the definitions.

**4. (Sub lesson 2)** A course name longer than 20 characters stored in TEXT(20) is —
a) rejected with an error  b) stored in full anyway  c) stored cut at 20 characters, spaces counted  d) moved to another field
**Answer: c) stored cut at 20 characters, spaces counted** — a sized field silently keeps only its first N characters.

**5. (Sub lesson 3)** A bank-account number should be stored as —
a) integer, always  b) text, because an integer cannot hold it  c) currency  d) date
**Answer: b) text, because an integer cannot hold it** — the worked sizing answer makes it text for exactly this reason.

**6. (Sub lesson 3)** Which is a fault in a broken CREATE? `CREATE Student (...)`
a) the semicolon  b) the missing word TABLE after CREATE  c) the primary key  d) the column types
**Answer: b) the missing word TABLE after CREATE** — CREATE must be followed by TABLE.
