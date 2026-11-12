# Filtering by date, AND, OR and BETWEEN

## Do it first

The sales book is open. Four hunts: sales *from* 15 March 2020 onward; sales after 1 May *and* over 12,000 birr; sales very small *or* very large; sales *between* two dates. For each hunt, point at the rows of a ten-row list you would keep — before any new keyword is named. Notice hunt one keeps the 15 March row itself. That detail matters.

## Sub lesson 1 — Dates compare in time order

Date values compare in **chronological order** — later dates are simply greater. And **>= includes the start date**: retrieving sales **on and after 15 March 2020** keeps the 15 March sale itself:

```sql
SELECT * FROM Sales WHERE SaleDate >= #2020-03-15#;
```

Say the boundary aloud whenever you write a date filter: *on and after* (>=) or *strictly after* (>) — the two differ by exactly one day's records.


## Sub lesson 2 — AND narrows, OR widens

**AND** demands **both** criteria true: sales **after 1 May 2020 AND amount over 12,000** — in the worked sales table, **one record** matches.

```sql
SELECT * FROM Sales
WHERE SaleDate > #2020-05-01# AND Amount > 12000;
```

**OR** accepts **either**: amount **under 1,000 OR over 15,000** — in the same table, **four records** match.

```sql
SELECT * FROM Sales
WHERE Amount < 1000 OR Amount > 15000;
```

Feel the directions: every AND you add can only shrink the catch; every OR can only grow it.


## Sub lesson 3 — BETWEEN — the inclusive range

**BETWEEN … AND** tests a value against a range with **both endpoints included**:

```sql
SELECT * FROM Sales
WHERE SaleDate BETWEEN #2020-03-01# AND #2020-03-31#;
```

Sales on the 1st and sales on the 31st are both kept — BETWEEN is a closed gate at both ends, which is exactly what month-end and term reports need.


## Say it to your companion

Tell your companion which operator you would use for 'small or large sales', and which for 'recent and large sales' — and why.

## Do It Yourself

1. Write the query for sales on and after 15 March 2020.
2. Write the OR query (under 1,000 or over 15,000) and the AND query (after 1 May 2020 and over 12,000).
3. Rewrite a BETWEEN over March 2020 as two comparisons joined by AND.
