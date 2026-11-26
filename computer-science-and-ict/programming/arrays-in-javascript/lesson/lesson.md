# Arrays in JavaScript

## Do it first

Five marks, thirty names, a term of temperatures: a script needs one name for the whole collection. Malaysia's JavaScript chapter gives it the array. In this lesson you build, read, loop and change JavaScript arrays.

## Sub lesson 1 — Building and reaching — indexes from zero

A JavaScript **array** holds **many values under one name**, in order: let marks = [70, 85, 60, 92];. Each value is reached by its **index** — its position counted **from 0**: marks[0] is 70, marks[1] is 85. The array's **length** (marks.length) counts its values, so the last index is always length − 1. An index outside the array answers **undefined** — JavaScript does not stop the script, which makes index discipline the programmer's own duty: indexes run 0 to length − 1, never 1 to length.

In your mind's eye: building and reaching — indexes from zero.

[Picture 46724 — building and reaching — indexes from zero]

## Sub lesson 2 — Looping and changing

Arrays are worked **by loop**: a for loop running i from 0 to length − 1 visits every value in order — the shape behind totalling, searching and printing a list. Arrays **change**: a value is replaced by assignment (marks[2] = 65;), new values are added at the end with **push**, and removed from the end with **pop**. Malaysia's scripts put array and loop together for the page's real work — a class's marks totalled, a list of names printed, a highest mark found — the array is the script's memory of many, the loop its way of visiting them all.

In your mind's eye: looping and changing.

[Picture 46725 — looping and changing]

## Say it to your companion

Tell your companion, in your own words: A JavaScript **array** holds **many values under one name**, in order: let marks = [70, 85, 60, 92];. Each value is reached by its **index** — its position counted **from 0**: marks[0] is 70, marks[1] is 85. The array's **length** (marks.length) counts its values, so the last index is always length − 1. An index outside the array answers **undefined** — JavaScript does not stop the script, which makes index discipline the programmer's own duty: indexes run 0 to length − 1, never 1 to length. Arrays are worked **by loop**: a for loop running i from 0 to length − 1 visits every value in order — the shape behind totalling, searching and printing a list. Arrays **change**: a value is replaced by assignment (marks[2] = 65;), new values are added at the end with **push**, and removed from the end with **pop**. Malaysia's scripts put array and loop together for the page's real work — a class's marks totalled, a list of names printed, a highest mark found — the array is the script's memory of many, the loop its way of visiting them all. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Many values under one name, in order. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: From 0 — marks[0] is the first value. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 60. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: By a for loop running i from 0 to length − 1. Do this with a real example of your own and write or say how you know it is right.
