# Video script — Subrange Data Types in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **subrange type** is defined by its **first and last** values: `type TDayNum = 1..31;` — a variable of it holds any integer from 1 to 31 and **no other**. Subranges are cut from **ordinal types** — integer, char, boolean, enumerations: `'A'..'Z'` is a subrange of char, `Mon..Fri` of the day enumeration. Declaration of a variable is as usual: `var dn: TDayNum;`. The slice is a promise written into the type: the data's real limits, stated once, in the open.
A subrange's protection is **range checking**: assign a value outside the slice — `dn := 32;` — and with range checks on, the program **stops with an error at that line** instead of carrying a poisoned value onward. Without the subrange, 32 would sit in an ordinary integer silently and corrupt a calendar three procedures later, unfindable. That is the type's whole argument: **errors are cheapest where they are made**, and a subrange makes the type system stand guard exactly there.
