# Python Tuples — Immutable Sequences

## Do it first

After the list comes its sterner sibling: the collection that refuses to change. Kuwait's data-structures course teaches the tuple beside the list because the difference between them is a design decision programmers make daily. This lesson is that difference.

## Sub lesson 1 — A tuple — a list that cannot change

A **tuple** holds values **in order**, like a list — but written in **round brackets** and **immutable**: after creation, no item can be changed, added or removed. Indexing and counting work as they did for lists, so reading a tuple is familiar; only the writing is forbidden. An attempt to change one is an error the program raises, not a quiet failure — Python defends the tuple's fixedness loudly.

In your mind's eye: a tuple — a list that cannot change.

[Picture 47531 — a tuple — a list that cannot change]

## Sub lesson 2 — When fixedness is right

Immutability is a **feature chosen on purpose**: a tuple holds data that **must not change** while the program runs — the days of the week, a point's coordinates (x, y), a record's fixed fields — where an accidental change would be a bug the program could not see. The course's rule of choice: a **list** for a collection the program will **build and change**; a **tuple** for a collection whose changing would be a **mistake**. Same order, same indexing — opposite promises.

In your mind's eye: when fixedness is right.

[Picture 47532 — when fixedness is right]

## Say it to your companion

Tell your companion, in your own words: A **tuple** holds values **in order**, like a list — but written in **round brackets** and **immutable**: after creation, no item can be changed, added or removed. Indexing and counting work as they did for lists, so reading a tuple is familiar; only the writing is forbidden. An attempt to change one is an error the program raises, not a quiet failure — Python defends the tuple's fixedness loudly. Immutability is a **feature chosen on purpose**: a tuple holds data that **must not change** while the program runs — the days of the week, a point's coordinates (x, y), a record's fixed fields — where an accidental change would be a bug the program could not see. The course's rule of choice: a **list** for a collection the program will **build and change**; a **tuple** for a collection whose changing would be a **mistake**. Same order, same indexing — opposite promises. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: An ordered collection, written in round brackets, that cannot be changed after creation. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Changing, adding and removing items. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Yes — reading is as for lists; only writing is forbidden. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Python raises an error — loudly, not quietly. Do this with a real example of your own and write or say how you know it is right.
