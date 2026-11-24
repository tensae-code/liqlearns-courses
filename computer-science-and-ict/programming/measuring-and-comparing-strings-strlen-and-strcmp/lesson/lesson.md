# Measuring and Comparing Strings — strlen and strcmp

## Do it first

The strings lesson built text as char arrays ending in '\0'. Now the toolbox that promise buys: functions that measure a string without counting, compare two without looping, join and copy without fuss — if, and only if, the terminator stands where it should.

## Sub lesson 1 — strlen and strcmp — measure and compare

`strlen(s)` **returns the length** of a string — the count of characters **before** the null (so 'Bangla' measures 6 though it occupies 7 rooms). `strcmp(a, b)` **compares** two strings letter by letter and returns **0 if they are equal**, a negative value if a comes first in dictionary order, positive if after — comparison in one call, where the beginner's `a == b` compares only addresses and lies. Both live in **<string.h>**, borrowed by include as every toolbox is.

In your mind's eye: strlen and strcmp — measure and compare.

## Sub lesson 2 — strcat and strcpy — join and copy

`strcat(a, b)` **joins**: it appends b (and its terminator) onto a's end — a must have room for the grown length plus '\0', or the join writes into foreign memory. `strcpy(a, b)` **copies** b over a, terminator included. The four functions share one moral, the strings lesson's edge discipline grown into a toolbox: C trusts the programmer with sizes, rooms and terminators — the functions do exactly what they are told, at exactly the addresses they are given, and checking that the rooms suffice is the caller's job, never the function's.

In your mind's eye: strcat and strcpy — join and copy.

## Say it to your companion

Tell your companion, in your own words: `strlen(s)` **returns the length** of a string — the count of characters **before** the null (so 'Bangla' measures 6 though it occupies 7 rooms). `strcmp(a, b)` **compares** two strings letter by letter and returns **0 if they are equal**, a negative value if a comes first in dictionary order, positive if after — comparison in one call, where the beginner's `a == b` compares only addresses and lies. Both live in **<string.h>**, borrowed by include as every toolbox is. `strcat(a, b)` **joins**: it appends b (and its terminator) onto a's end — a must have room for the grown length plus '\0', or the join writes into foreign memory. `strcpy(a, b)` **copies** b over a, terminator included. The four functions share one moral, the strings lesson's edge discipline grown into a toolbox: C trusts the programmer with sizes, rooms and terminators — the functions do exactly what they are told, at exactly the addresses they are given, and checking that the rooms suffice is the caller's job, never the function's. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The count of characters before the null. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: 6. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 0. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The first string comes first in dictionary order. Do this with a real example of your own and write or say how you know it is right.
