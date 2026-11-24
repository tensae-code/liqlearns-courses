# VLOOKUP in Excel

## Do it first

The marks sheet has pupil numbers; the names live in another table. Joining them by hand is an afternoon; VLOOKUP does it in a formula. This lesson learns the lookup.

## Sub lesson 1 — What VLOOKUP does

**VLOOKUP(lookup_value, table, column, exact)** searches the **first column** of a table for the lookup value, walks across that row, and returns the value in the stated **column**. It is the spreadsheet's join: any two tables sharing a key (a pupil number, a product code) can lend each other their columns. The V is **vertical** — the search runs down a column; its sibling HLOOKUP runs across a row, and the book's data lesson needs the vertical one because records live in rows.

In your mind's eye: what VLOOKUP does.

## Sub lesson 2 — Exactness and the lookup's faults

The fourth argument is the lesson's conscience: **FALSE demands an exact match** (the code must be found, or the formula reports #N/A — an honest failure), while TRUE accepts the nearest — right for tax bands, catastrophic for names. The standing faults: lookup values in the table's first column **only** (a table arranged otherwise cannot be searched), duplicates returning the **first** match silently, and numbers stored as text failing to meet their twins. Jordan teaches VLOOKUP with its faults attached because a lookup that fails silently invents data — and #N/A, loudly, is the analyst's friend.

In your mind's eye: exactness and the lookup's faults.

## Say it to your companion

Tell your companion, in your own words: **VLOOKUP(lookup_value, table, column, exact)** searches the **first column** of a table for the lookup value, walks across that row, and returns the value in the stated **column**. It is the spreadsheet's join: any two tables sharing a key (a pupil number, a product code) can lend each other their columns. The V is **vertical** — the search runs down a column; its sibling HLOOKUP runs across a row, and the book's data lesson needs the vertical one because records live in rows. The fourth argument is the lesson's conscience: **FALSE demands an exact match** (the code must be found, or the formula reports #N/A — an honest failure), while TRUE accepts the nearest — right for tax bands, catastrophic for names. The standing faults: lookup values in the table's first column **only** (a table arranged otherwise cannot be searched), duplicates returning the **first** match silently, and numbers stored as text failing to meet their twins. Jordan teaches VLOOKUP with its faults attached because a lookup that fails silently invents data — and #N/A, loudly, is the analyst's friend. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The first column of a table, for the lookup value. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The value in the stated column of the found row. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The spreadsheet's join — tables lending columns through a shared key. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Vertical — the search runs down a column. Do this with a real example of your own and write or say how you know it is right.
