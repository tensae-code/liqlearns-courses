# Video script — The Char Type in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **char** type holds **exactly one character** — a letter, a digit-character, a mark, a space. It is written in **apostrophes in Pascal** ('A') and in **apostrophes in C++** too ('A') — but in C++ a double-quoted "A" is a *string of length 1*, a different type from the char 'A': the quotes are a type distinction, not a style. Inside, the character is stored as its **code number** in the machine's code table (ASCII and its successors) — storage Grade 7's encoding lessons built.
Because a char is a code number, char is an **ordinal type**: characters **compare** by code ('A' < 'B'), **succ and pred** step along the table (succ('A') = 'B'), **ord** gives the code, **chr** turns a code back into its character. Digits are characters too — '7' is the character with code 55, **not** the number 7 — and turning a digit-character into its numeric value is a small computation (ord('7') − ord('0')) every text-processing program performs. Case lives in the table as well: capitals and smalls stand a fixed distance apart.
