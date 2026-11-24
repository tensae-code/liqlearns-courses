# Expressions in Access

## Do it first

A database that can only store is a cupboard. Grade 12's Access course reaches the feature that makes it compute: expressions — small formulas living inside queries, forms and reports.

## Sub lesson 1 — The parts of an expression — fields, operators, functions

An **Access expression** is a formula that works out a **value** from the record's data: **[Pret] * [Cantitate]** multiplies two fields — field names stand in **square brackets**; arithmetic and text **operators** (+, −, *, /, & for joining text) combine them; **constants** (numbers, "texts" in quotes, dates in #…#) stand fixed; and built-in **functions** — Sum, Avg, Date, Year, IIf and their kin — do the named jobs. An expression is **evaluated per record**: each row's own fields feed its own result.

In your mind's eye: the parts of an expression — fields, operators, functions.

## Sub lesson 2 — Where expressions live — criteria, calculated fields, controls

Expressions are placed where values are needed. In a query's **criteria row**, an expression is the test a record must pass (>100, Between #2026-01-01# And #2026-12-31#). As a **calculated field**, an expression becomes a new column the table never stored (Total: [Pret]*[Cantitate]). In a form or report **control**, it displays a worked-out value, with **IIf** choosing between answers by a condition. One grammar rules all three homes — learn the formula once, spend it everywhere in the database.

In your mind's eye: where expressions live — criteria, calculated fields, controls.

## Say it to your companion

Tell your companion, in your own words: An **Access expression** is a formula that works out a **value** from the record's data: **[Pret] * [Cantitate]** multiplies two fields — field names stand in **square brackets**; arithmetic and text **operators** (+, −, *, /, & for joining text) combine them; **constants** (numbers, "texts" in quotes, dates in #…#) stand fixed; and built-in **functions** — Sum, Avg, Date, Year, IIf and their kin — do the named jobs. An expression is **evaluated per record**: each row's own fields feed its own result. Expressions are placed where values are needed. In a query's **criteria row**, an expression is the test a record must pass (>100, Between #2026-01-01# And #2026-12-31#). As a **calculated field**, an expression becomes a new column the table never stored (Total: [Pret]*[Cantitate]). In a form or report **control**, it displays a worked-out value, with **IIf** choosing between answers by a condition. One grammar rules all three homes — learn the formula once, spend it everywhere in the database. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A formula that works out a value from the record's data. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In square brackets — [Pret], [Cantitate]. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It joins them — concatenation. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Sum, Avg, IIf (also: Date, Year). Do this with a real example of your own and write or say how you know it is right.
