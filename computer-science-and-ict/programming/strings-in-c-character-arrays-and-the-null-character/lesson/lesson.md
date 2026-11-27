# Strings in C — Character Arrays and the Null Character

## Do it first

Python hands you a string type. C — the mid-level language that hides nothing — hands you an array and a promise: characters in a row, and one special invisible character standing at the end saying 'the text stops here'. Forget the promise and C's strings misbehave in ways this lesson exists to prevent.

## Sub lesson 1 — A string is a char array — the 'Bangla' table

In C, a **string** is an **array of char**: `char word[10];` holds a row of characters, each in its numbered room, reached by the array's indexing. The book lays the word **'Bangla'** out in its storage table — B in room 0, a in 1, n in 2, and so on — because a C string is nothing more mystical than this: letters in rooms, in order. Declared with a literal, `char country[] = "Bangla";`, the compiler builds the row for you — and quietly adds one more room, for the character of the next part.

In your mind's eye: a string is a char array — the 'Bangla' table.

[Picture 47743 — a string is a char array — the 'Bangla' table]

## Sub lesson 2 — The null character — where the string ends

Every C string ends with the **null character, '\0'** — a character whose code is **zero**, invisible, unprintable, and load-bearing: it is how every C string function knows **where the text stops**. 'Bangla' occupies **seven rooms, not six** — six letters and the terminator. An array sized exactly for its letters has **no room for '\0'** and is not yet a string — functions reading it march past its end into foreign memory, the array lesson's edge fault in its most famous form. Size for the terminator, always: letters + 1.

In your mind's eye: the null character — where the string ends.

[Picture 47744 — the null character — where the string ends]

## Say it to your companion

Tell your companion, in your own words: In C, a **string** is an **array of char**: `char word[10];` holds a row of characters, each in its numbered room, reached by the array's indexing. The book lays the word **'Bangla'** out in its storage table — B in room 0, a in 1, n in 2, and so on — because a C string is nothing more mystical than this: letters in rooms, in order. Declared with a literal, `char country[] = "Bangla";`, the compiler builds the row for you — and quietly adds one more room, for the character of the next part. Every C string ends with the **null character, '\0'** — a character whose code is **zero**, invisible, unprintable, and load-bearing: it is how every C string function knows **where the text stops**. 'Bangla' occupies **seven rooms, not six** — six letters and the terminator. An array sized exactly for its letters has **no room for '\0'** and is not yet a string — functions reading it march past its end into foreign memory, the array lesson's edge fault in its most famous form. Size for the terminator, always: letters + 1. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: An array of char. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In room 0. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The compiler. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: One character. Do this with a real example of your own and write or say how you know it is right.
