# DROP TABLE — and why it cannot be undone

## Do it first

Two commands sound alike: one empties a drawer, the other throws the drawer itself into the fire. DELETE does the first (a later lesson); DROP TABLE does the second. Before you read on, say which one you could undo by re-typing a CREATE — and which loss no command can repair.

## Sub lesson 1 — The command and its example

**DROP TABLE** deletes a table already created:

```sql
DROP TABLE COURSE;
```

The table goes entirely — its columns, its key, its relationships, and every record in it. The worked answer set (teacher guide — evidence) creates a School table and then drops it the same way: a table built for practice can be removed with one line.


## Sub lesson 2 — The caution — read it twice

The caution is explicit: **delete a table that holds records and you cannot get it back.** There is no undo and no recycle bin for a dropped table.

Before any DROP, ask three questions: Does it hold records? Are they needed anywhere else? Is this truly the table I mean? If any answer gives pause, stop.

Dropping the *wrong* thing is the classic accident of this command — which is why this lesson's whole second half is one warning.


## Say it to your companion

Tell your companion what DROP TABLE removes, and why you would pause before running it on a filled table.

## Do It Yourself

1. Write the DROP that removes a practice table named School.
2. List everything lost when a filled COURSE table is dropped.
3. Say the difference between dropping a table and deleting its records.
