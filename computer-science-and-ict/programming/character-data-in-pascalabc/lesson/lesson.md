# Character Data in PascalABC

## Do it first

Type one letter on the keyboard. The computer never saw a letter — it received a number. In this lesson you meet the char type, the code tables behind your keyboard, and the PascalABC tools that turn codes back into characters and characters back into codes.

## Sub lesson 1 — The char type and character codes

A variable of the **char** type holds exactly **one character**: a letter, a digit, a punctuation mark or a space. Inside the computer the character is stored as a **code number**, and a coding table says which number belongs to which character. In **ASCII**, the classic table, the Latin letters, digits and common marks have fixed codes; **national codings** extend the idea so the letters of other alphabets — including the Belarusian and Russian letters the book's readers type — also have codes. Because characters have numbers, they can be compared: a character is 'greater' when its code is greater, which is what puts characters into alphabetical order.

[Picture — one big letter A in a box labelled char, with an arrow down to its code number in a coding table]

## Sub lesson 2 — Procedures and functions for characters

PascalABC gives ready **procedures and functions** for character variables, so a program does not have to work with raw codes by hand. They answer questions like: what is the character for this code, what is the code of this character, is this character a letter or a digit, and what is the same letter in the other case — capital for small, small for capital. The rule for using them is the rule for all such tools: give the function a character (or a code), and it hands back the answer as a value the program can store, print or compare.

[Picture — a two-column coding table — character on the left, code number on the right — with Latin and Belarusian letters in the rows]

## Say it to your companion

Tell your companion, in your own words: In PascalABC a single character is a value of the char type; every character carries a code number — in ASCII and in the national codings — and the language gives procedures and functions that work on character variables through those codes. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: exactly one character. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: it says which code number belongs to which character. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: when its code number is greater. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: change a letter between small and capital. Do this with a real example of your own and write or say how you know it is right.
