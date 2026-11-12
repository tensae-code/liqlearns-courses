# ORDER BY — ascending and descending results

## Do it first

The head teacher wants the salary list two ways for two meetings: lowest-paid first (to argue for raises), then highest-paid first (to check the top). Same rows, same table — two orders. If sorting changed the table itself, the second meeting could not have its order. Decide: does sorting move the stored rows, or only the list you are shown?

## Sub lesson 1 — Ascending — the default

**ORDER BY** sorts the **output** of a query by a named field — **alphabetically or numerically**. **Ascending is the default**: ASC may be written or left empty.

```sql
SELECT TeacherName, Salary FROM Teacher ORDER BY Salary;
```

The first worked sort takes the teachers **by salary, ascending** — lowest first.


## Sub lesson 2 — Descending — DESC

Add **DESC** and the same field sorts the other way — the second worked sort takes the teachers **by salary, descending**, highest first:

```sql
SELECT TeacherName, Salary FROM Teacher ORDER BY Salary DESC;
```

One word flips the whole list. ASC and DESC are the two directions; there is no third. The worked answer set (teacher guide — evidence) sorts in both directions over names, sex, temperature and visit date — the direction choice belongs to the question being asked, every time.


## Sub lesson 3 — Order lives in the output only

The closing note: **record and column order inside a table itself does not matter** — ordering is a property of the **query output only**.

Run the ascending query, then the descending one: the table underneath never moved. Tomorrow's query can sort by name instead, and nothing stored has to change. Sort for the reader in front of you.


## Say it to your companion

Tell your companion which direction you would choose for a 'who earns least?' report and a 'top earners' report.

## Do It Yourself

1. Write teachers by salary ascending, then descending.
2. Write students by name alphabetically using ORDER BY.
3. Explain to a partner why running the DESC query does not disturb the ASC query's table.
