# Video script — Expressions in Access

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **Access expression** is a formula that works out a **value** from the record's data: **[Pret] * [Cantitate]** multiplies two fields — field names stand in **square brackets**; arithmetic and text **operators** (+, −, *, /, & for joining text) combine them; **constants** (numbers, "texts" in quotes, dates in #…#) stand fixed; and built-in **functions** — Sum, Avg, Date, Year, IIf and their kin — do the named jobs. An expression is **evaluated per record**: each row's own fields feed its own result.
Expressions are placed where values are needed. In a query's **criteria row**, an expression is the test a record must pass (>100, Between #2026-01-01# And #2026-12-31#). As a **calculated field**, an expression becomes a new column the table never stored (Total: [Pret]*[Cantitate]). In a form or report **control**, it displays a worked-out value, with **IIf** choosing between answers by a condition. One grammar rules all three homes — learn the formula once, spend it everywhere in the database.
