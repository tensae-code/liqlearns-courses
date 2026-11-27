# The Char Type in Pascal and C++

## Do it first

A single character is a type of its own in both languages. Grade 10 aligns them: char is a character, a code number, and an ordinal value all at once.

## Sub lesson 1 — One character, written and stored

The **char** type holds **exactly one character** — a letter, a digit-character, a mark, a space. It is written in **apostrophes in Pascal** ('A') and in **apostrophes in C++** too ('A') — but in C++ a double-quoted "A" is a *string of length 1*, a different type from the char 'A': the quotes are a type distinction, not a style. Inside, the character is stored as its **code number** in the machine's code table (ASCII and its successors) — storage Grade 7's encoding lessons built.

In your mind's eye: one character, written and stored.

[Picture 47814 — one character, written and stored]

## Sub lesson 2 — Chars are ordinal — order and arithmetic by code

Because a char is a code number, char is an **ordinal type**: characters **compare** by code ('A' < 'B'), **succ and pred** step along the table (succ('A') = 'B'), **ord** gives the code, **chr** turns a code back into its character. Digits are characters too — '7' is the character with code 55, **not** the number 7 — and turning a digit-character into its numeric value is a small computation (ord('7') − ord('0')) every text-processing program performs. Case lives in the table as well: capitals and smalls stand a fixed distance apart.

In your mind's eye: chars are ordinal — order and arithmetic by code.

[Picture 47815 — chars are ordinal — order and arithmetic by code]

## Say it to your companion

Tell your companion, in your own words: The **char** type holds **exactly one character** — a letter, a digit-character, a mark, a space. It is written in **apostrophes in Pascal** ('A') and in **apostrophes in C++** too ('A') — but in C++ a double-quoted "A" is a *string of length 1*, a different type from the char 'A': the quotes are a type distinction, not a style. Inside, the character is stored as its **code number** in the machine's code table (ASCII and its successors) — storage Grade 7's encoding lessons built. Because a char is a code number, char is an **ordinal type**: characters **compare** by code ('A' < 'B'), **succ and pred** step along the table (succ('A') = 'B'), **ord** gives the code, **chr** turns a code back into its character. Digits are characters too — '7' is the character with code 55, **not** the number 7 — and turning a digit-character into its numeric value is a small computation (ord('7') − ord('0')) every text-processing program performs. Case lives in the table as well: capitals and smalls stand a fixed distance apart. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Exactly one character — letter, digit-character, mark or space. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In apostrophes in both — 'A'. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A string of length 1 — a different type from the char 'A'. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: As its code number in the code table. Do this with a real example of your own and write or say how you know it is right.
