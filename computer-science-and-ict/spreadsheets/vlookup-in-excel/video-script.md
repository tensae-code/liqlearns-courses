# Video script — VLOOKUP in Excel

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**VLOOKUP(lookup_value, table, column, exact)** searches the **first column** of a table for the lookup value, walks across that row, and returns the value in the stated **column**. It is the spreadsheet's join: any two tables sharing a key (a pupil number, a product code) can lend each other their columns. The V is **vertical** — the search runs down a column; its sibling HLOOKUP runs across a row, and the book's data lesson needs the vertical one because records live in rows.
The fourth argument is the lesson's conscience: **FALSE demands an exact match** (the code must be found, or the formula reports #N/A — an honest failure), while TRUE accepts the nearest — right for tax bands, catastrophic for names. The standing faults: lookup values in the table's first column **only** (a table arranged otherwise cannot be searched), duplicates returning the **first** match silently, and numbers stored as text failing to meet their twins. Jordan teaches VLOOKUP with its faults attached because a lookup that fails silently invents data — and #N/A, loudly, is the analyst's friend.
