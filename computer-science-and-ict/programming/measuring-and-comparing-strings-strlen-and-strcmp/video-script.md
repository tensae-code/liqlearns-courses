# Video script — Measuring and Comparing Strings — strlen and strcmp

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

`strlen(s)` **returns the length** of a string — the count of characters **before** the null (so 'Bangla' measures 6 though it occupies 7 rooms). `strcmp(a, b)` **compares** two strings letter by letter and returns **0 if they are equal**, a negative value if a comes first in dictionary order, positive if after — comparison in one call, where the beginner's `a == b` compares only addresses and lies. Both live in **<string.h>**, borrowed by include as every toolbox is.
`strcat(a, b)` **joins**: it appends b (and its terminator) onto a's end — a must have room for the grown length plus '\0', or the join writes into foreign memory. `strcpy(a, b)` **copies** b over a, terminator included. The four functions share one moral, the strings lesson's edge discipline grown into a toolbox: C trusts the programmer with sizes, rooms and terminators — the functions do exactly what they are told, at exactly the addresses they are given, and checking that the rooms suffice is the caller's job, never the function's.
