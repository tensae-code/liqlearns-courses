# Subrange Data Types in Pascal

## Do it first

A day of the month is an integer — but not every integer: 47 is no day's number. Grade 7's last simple Pascal type is the honest slice: a type that says exactly which part of a bigger type it allows.

## Sub lesson 1 — A slice of a type — first..last

A **subrange type** is defined by its **first and last** values: `type TDayNum = 1..31;` — a variable of it holds any integer from 1 to 31 and **no other**. Subranges are cut from **ordinal types** — integer, char, boolean, enumerations: `'A'..'Z'` is a subrange of char, `Mon..Fri` of the day enumeration. Declaration of a variable is as usual: `var dn: TDayNum;`. The slice is a promise written into the type: the data's real limits, stated once, in the open.

In your mind's eye: a slice of a type — first..last.

## Sub lesson 2 — The guard at the border — range checking

A subrange's protection is **range checking**: assign a value outside the slice — `dn := 32;` — and with range checks on, the program **stops with an error at that line** instead of carrying a poisoned value onward. Without the subrange, 32 would sit in an ordinary integer silently and corrupt a calendar three procedures later, unfindable. That is the type's whole argument: **errors are cheapest where they are made**, and a subrange makes the type system stand guard exactly there.

In your mind's eye: the guard at the border — range checking.

## Say it to your companion

Tell your companion, in your own words: A **subrange type** is defined by its **first and last** values: `type TDayNum = 1..31;` — a variable of it holds any integer from 1 to 31 and **no other**. Subranges are cut from **ordinal types** — integer, char, boolean, enumerations: `'A'..'Z'` is a subrange of char, `Mon..Fri` of the day enumeration. Declaration of a variable is as usual: `var dn: TDayNum;`. The slice is a promise written into the type: the data's real limits, stated once, in the open. A subrange's protection is **range checking**: assign a value outside the slice — `dn := 32;` — and with range checks on, the program **stops with an error at that line** instead of carrying a poisoned value onward. Without the subrange, 32 would sit in an ordinary integer silently and corrupt a calendar three procedures later, unfindable. That is the type's whole argument: **errors are cheapest where they are made**, and a subrange makes the type system stand guard exactly there. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: By its first and last values — type TDayNum = 1..31;. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Ordinal types — integer, char, boolean, enumerations. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 'A'..'Z'. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The data's real limits — the promise the type makes. Do this with a real example of your own and write or say how you know it is right.
