# Data Types in a Database

## Do it first

A school register holds a name, an age, a fee paid and the day a student joined. Four columns, four different kinds of value. Before any table is built, someone must decide what kind of value each column may hold — and refuse. This lesson teaches those decisions.

## Sub lesson 1 — Number types — whole numbers and numbers with parts

A **data type** is the rule given to a column that says what kind of value may live there. The type controls three things: what the column **accepts** (and what it refuses), how the values are **stored**, and how they **sort and calculate**. For numbers, MySQL gives a family of types. **INT** holds whole numbers — ages, quantities, marks, counts: things you count, add and average. A whole-number column refuses a value with a part after the point and refuses words outright. For numbers that do have parts — a price, a weight, a temperature — the types are **DECIMAL** and **FLOAT**. DECIMAL stores the value exactly as written, which is why money is kept in DECIMAL: a fee of 1250.50 stays 1250.50. FLOAT stores a near value quickly and is used for measures where a tiny difference does not matter.

[Picture — a picture of a table drawn as four labelled columns — age, fee, name, joining day — each with its data type written under it]

## Sub lesson 2 — Text types — words, names and longer writing

Text has its own family. **CHAR** holds text of a fixed length that you set — every value is padded to the same length, fitting codes that are always the same size. **VARCHAR** holds text up to a length you set, storing only the length each value actually has — the usual choice for names, addresses and titles. **TEXT** holds long writing with no short limit: remarks, descriptions, a whole paragraph of notes. The test for the text family is simple: if the value is words to be read rather than amounts to be added, it belongs to text — even when the words are made of digits, as the next part shows.

[Picture — a picture of a database refusing a value: the word "twelve" trying to enter an INT age column, stopped by a gate marked with the column's type]

## Sub lesson 3 — Dates, times — and choosing the right type

Dates and times have their own types too: **DATE** holds a day (year, month, day), **TIME** holds a time of day, and **DATETIME** holds a day and a time together. A date in a DATE column can be sorted truly — the earliest day first — and the database can count the days between two dates, which no text column can do. **Choosing** a type follows one rule: ask what the values *are* and what will be *done* with them. The famous case is the **phone number**: it is written in digits, but it is **text**, not a number — nobody adds two phone numbers or averages them, and a number column would strip off a leading zero and ruin the number. Give a column the type of the thing it holds, and the database itself will guard the gate, refusing values that do not belong.

[Picture — a picture of a phone number written two ways: as a number, its first zero missing, and as text, complete]

## Say it to your companion

Tell your companion, in your own words: a data type is the rule that says what a column may hold — INT for whole numbers, DECIMAL and FLOAT for numbers with parts, CHAR, VARCHAR and TEXT for words and writing, DATE, TIME and DATETIME for days and times — and a phone number is text, because it is never calculated with. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a data type controls in a column — what it accepts, how values are stored, how they sort and calculate. Do this with a real example from your own home, school or street, and write or say how you know it is right.
2. Show it, don't just say it: choose between INT, DECIMAL and FLOAT for three values of your own — a count, a price, a measure. Do this with a real example from your own home, school or street, and write or say how you know it is right.
3. Show it, don't just say it: choose between CHAR, VARCHAR and TEXT for a code, a name and a long remark. Do this with a real example from your own home, school or street, and write or say how you know it is right.
4. Show it, don't just say it: explain why a phone number is stored as text, and what a number column would do to it. Do this with a real example from your own home, school or street, and write or say how you know it is right.
