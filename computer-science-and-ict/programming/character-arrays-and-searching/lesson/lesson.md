# Character Arrays and Searching

## Do it first

Before there were string objects, text was an array like any other — with one special last element. This lesson reads text the array way and hunts through it.

## Sub lesson 1 — Text as a char array

**char word[10] = "Skopje";** stores the letters in elements 0–5 and then the **null terminator '\0'** in element 6 — the mark every text routine watches for. The array's declared size is its **capacity**; the text's **length** is the count up to the terminator, which a simple walk can measure. Spaces are characters too and take elements of their own.

[Picture — text as a char array]

## Sub lesson 2 — Searching the characters

**Searching** walks the array comparing each element with the target: stop with **found** (and its position) on a match, or stop at the **terminator** with not-found. The same walk counts occurrences (do not stop at the first match — count and continue) or tests membership. Case matters: 'A' and 'a' are different characters with different codes, so searches must say which they mean.

[Picture — searching the characters]

## Say it to your companion

Tell your companion, in your own words: Text in old-style C++ is an array of characters ending with a special zero character ('\0') that marks the end; programs walk that array like any other, and searching text means comparing characters one by one until the wanted character is found or the terminator ends the hunt. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The null terminator, '\0'. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Capacity is the declared size; length counts up to the terminator. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: On a match — reporting the position. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: It counts and continues instead of stopping at the first match. Do this with a real example of your own and write or say how you know it is right.
