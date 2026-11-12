# INSERT — adding a record to a table

## Do it first

Your COURSE table stands empty. A new course arrives: 30 contact hours, Databases, about SQL, department 105, code CS101. Write those five facts in the table's column order. You have just drafted an INSERT — this lesson gives it its exact written shape, two ways.

## Sub lesson 1 — Form 1 — values for all fields, in table order

**INSERT** adds new records to a table. **Form 1** gives **values for all fields, in the table's order**:

```sql
INSERT INTO COURSE VALUES (30, 'Databases', 'SQL basics', '105', 'CS101');
```

No column list — so the values must march in exactly the order the table's columns stand. One value out of place lands in the wrong column.


## Sub lesson 2 — Form 2 — named columns, then their values

**Form 2** names the **chosen columns** first, then their values in the same order:

```sql
INSERT INTO DEPARTMENT (D_Name, D_Number, D_Location)
VALUES ('Computing', '105', 'Main campus');
```

Form 2 can name all the columns or only some — the next lesson works the partial case. When the column list is present, the values answer the named columns, not the table's raw order.


## Sub lesson 3 — The value rules

Each value must **match its column's data type** — no text into a numeric field.

**String values are quoted** with single or double quotes; **numeric values are not quoted**. In the form-1 example above, '105' is quoted because C_Department is a string type — while 30, the contact hours, stands bare as an integer. The worked diagnosis set (teacher guide — evidence) adds the failure shapes to avoid: a keyword written with no space, field and value counts that do not match, field names supplied where values belong.


## Say it to your companion

Tell your companion the two forms, and read one INSERT aloud value by value, naming the column each value lands in.

## Do It Yourself

1. Write form 1 to add a Networks course: 45 hours, 'Networks', 'Routing', '105', 'CS102'.
2. Rewrite it in form 2 naming only C_Code, C_Name, Contact_Hr.
3. Spot the fault: INSERT INTO COURSE VALUES ('thirty', 'Databases', …) for an integer first field.
