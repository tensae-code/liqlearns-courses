# Creating a table and entering records in Access

## Do it first

Open the database you made for your school. Before you click anything, write the **Student** table's plan on paper: the field names down the left, and beside each one its **data type** — text for names, number for grades. That paper plan is the whole of the first half of this lesson: Table Design is where the plan gets typed in. The second half is filling the table with real records.

## Sub lesson 1 — Create the design — fields and data types

The book's order for creating a table:

1. **Open the database.**
2. **Click Table Design on the Create menu.**
3. **Enter the field names.**
4. **Set each field's data type** — **text, number, date/time, currency, and so on**.

The data type is not decoration — **the type is itself a check**: **a Text field will not accept a number**. Choose the type that matches the data, and Access guards the column for you.

Two field rules hold for every table: **field names must be unique in a table**, and **a table needs at least two fields**.

[Picture 16914 — the Design-view field list beside the filled table]

## Sub lesson 2 — Save, name — and set the primary key

5. **Save and name the table.**

While you are still in Design view, set the table's **primary key** (the unique field from the keys lesson): **select the field in Design view and click the Primary Key button**. For the Student table, that is the student ID field — the one whose value no two records may share.

## Sub lesson 3 — Enter the records — Datasheet View

Design view builds the table; **Datasheet View** fills it:

1. **Open the table in Datasheet View.**
2. **Type the values record by record** — one row per student, each value in its field's column.

[GIF 16915 — Design view to Datasheet view, and the first record typed]

The book's practice: in a **database named after your school**, build the **Student**, **Teacher** and **Grade** tables this way — design each in Table Design, set its key, then enter its records.

## Sub lesson 4 — Grade 12 — matching types to fields, and the Access SQL type set in detail

**Grade 12 growth.** Every field gets a **name and a data type** — the kind of value it will store. The matching, worked field by field: a **residence id as a four-digit number**, a **first name as text**; and in the sample table — **age to integer, name to text, price to real/currency, date of birth to date, height to integer or real, grade level to integer, and telephone number to text**. A telephone number is text even though it is made of digits: you never add two phone numbers together, and its leading zero must survive.

Access offers **text, integer, real, date, currency and yes/no** types when a table is created — and in SQL the common Access set in detail:

- **CHAR** — text or text-and-number combinations not used in calculation, **up to 255 characters**; CHAR(20) limits to 20.
- **TEXT** — lengthy text, up to **63,999 characters**.
- **INTEGER / INT** — long integers, **−2,147,483,648 to 2,147,483,647**; no size is set by the user.
- **DATETIME** — dates (**years 100–9999**, written dd-mm-yyyy or yyyy-mm-dd) and times (hh:mm or hh:mm:ss).
- **CURRENCY** — monetary values used in calculations, 8 bytes.
- **COUNTER** — a unique sequential or random number Access assigns to each new record, 4 bytes.
- **Yes/No** — two-value fields (Yes/No, True/False, On/Off), 1 bit.

[Picture 30501 — fields tagged with their data types]

[Picture 30502 — the Access SQL data types chart]

## Say it to your companion

Walk your companion through the whole rhythm without touching the computer: design, types, key, save, datasheet, records. They check your order against the lesson; then swap.

## Do It Yourself

1. Create the Student table in Table Design with at least four fields and their types, from memory of the order.
2. Set its primary key and say which field you chose and why.
3. Enter five records in Datasheet view.
4. Write the two field rules and the type-as-check rule in your own words.
