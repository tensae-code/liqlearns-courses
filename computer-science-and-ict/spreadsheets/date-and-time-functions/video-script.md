# Video script — Date and Time Functions in a Spreadsheet

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A spreadsheet stores a **date as a number** — the count of days since its day zero — with the time as the day's **fraction**. That is why dates can be **added, subtracted and compared** like numbers: a deadline minus today is the days remaining, and sorting dates sorts numbers. The display is a costume: the same value can wear `14/11/2026` or `Nov 14` by formatting, while the number underneath does the arithmetic. Vietnam's specialist book teaches this before its functions, because every date function's behaviour follows from it.
The working set: **TODAY()** gives the current date (and **NOW()** the date with the time) — the quotation in the book is dated by it, so it never goes stale in print. **YEAR, MONTH and DAY** pull a date apart; **DATE(y, m, d)** builds one from parts; and plain subtraction — or **DATEDIF** — counts the span between two dates. The discipline: a date typed as **text** ('14 Nov' as letters) is a dead value no function can spend, so dates are entered as dates and only dressed by formatting.
