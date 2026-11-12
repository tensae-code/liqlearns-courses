# SELECT — the parts of a query

## Do it first

Ask a librarian for 'the books'. She will ask back: *Which* books? *From which* shelves? *Only* the ones about what? *In what order* shall I bring them? Four questions — and a query that cannot answer them is not finished. This lesson names the four parts of SQL that answer her.

## Sub lesson 1 — What a complete query must settle

**SELECT** — Data Query Language's command — **retrieves all or a subset of records from one or more tables**. Before its clauses, know the five things a complete query statement must settle:

1. **What data** a table contains. 2. **How data from different sources relate.** 3. **Which fields or calculations produce** the data. 4. **What criteria** the data must match. 5. **Whether and how to sort**.

Every clause you are about to meet exists to settle one of these. A query that skips one has not failed — it has *decided* it by default: no criteria means all rows; no sort means any order.


## Sub lesson 2 — The four clauses — two required, two optional

- **SELECT** — the fields wanted. **Required.**

- **FROM** — the tables holding them. **Required.**

- **WHERE** — the criteria each record must meet. Optional.

- **ORDER BY** — how to sort the results. Optional.

The lessons after this one take the clauses in the order you will use them most: SELECT * for everything, chosen columns with WHERE, richer WHERE, ORDER BY, and finally two tables at once.


## Say it to your companion

Tell your companion the librarian's four questions and the clause that answers each.

## Do It Yourself

1. For the question 'names of Grade 12 students, alphabetically', write what each clause must say.
2. Which clauses may be left out of a valid query, and what happens by default?
3. A query returns rows in a jumbled order. Which unsettled question is that?
