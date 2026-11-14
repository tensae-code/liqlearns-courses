# Video script — Strings in C — Character Arrays and the Null Character

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In C, a **string** is an **array of char**: `char word[10];` holds a row of characters, each in its numbered room, reached by the array's indexing. The book lays the word **'Bangla'** out in its storage table — B in room 0, a in 1, n in 2, and so on — because a C string is nothing more mystical than this: letters in rooms, in order. Declared with a literal, `char country[] = "Bangla";`, the compiler builds the row for you — and quietly adds one more room, for the character of the next part.
Every C string ends with the **null character, '\0'** — a character whose code is **zero**, invisible, unprintable, and load-bearing: it is how every C string function knows **where the text stops**. 'Bangla' occupies **seven rooms, not six** — six letters and the terminator. An array sized exactly for its letters has **no room for '\0'** and is not yet a string — functions reading it march past its end into foreign memory, the array lesson's edge fault in its most famous form. Size for the terminator, always: letters + 1.
