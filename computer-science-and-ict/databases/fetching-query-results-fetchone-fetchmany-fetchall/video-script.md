# Video script — Fetching Query Results — fetchone, fetchmany, fetchall

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

When Python runs a SELECT, the results wait on the **cursor** — the query's answer, row by row, held by the database side of the connection. **Fetching** moves rows from the cursor into the program, where variables can hold them, loops can walk them, and prints can show them. Until a row is fetched it is not the program's: the query was asked, but nothing was heard.
The three fetches differ only in appetite. **fetchone** takes the **next one row** — for questions with a single answer. **fetchmany** takes the **next counted rows** — for answers too big to hold at once, taken in mouthfuls. **fetchall** takes **every remaining row** at once, as a list — right for the course's landmark tables, dangerous for a million-row store. Choosing the fetch is choosing how the program will hold the answer, and Kuwait teaches the choice as part of querying, not after it.
