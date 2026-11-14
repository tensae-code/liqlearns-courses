# Local and Global Variables in Functions

## Do it first

Some names belong to one room of the house; others belong to the whole house. This lesson is about which variables live where — and what breaks when they are mixed up.

## Sub lesson 1 — Local — private to the function

Variables declared **inside** a function (and its parameters) are **local**: each call gets its **own fresh copies**, no other function can see or change them, and they **stop existing** when the function returns. That privacy is a feature — functions cannot accidentally wreck each other's working values, which is why most variables should be local.

[Picture — local — private to the function]

## Sub lesson 2 — Global — shared by everyone

A **global** variable is declared **outside** every function and lives for the **whole run**: every function can read and **change** it, so a change made anywhere shows up everywhere — convenient for true whole-program data, dangerous as a habit, because any bug can come from any function. If a local variable shares a global's **name**, inside that function the name means the **local** one (the global is shadowed).

[Picture — global — shared by everyone]

## Say it to your companion

Tell your companion, in your own words: A local variable is declared inside a function and lives only there — invisible outside, born at the call and gone at the return — while a global variable is declared outside all functions and can be read and changed by every function in the file; the same name in both places means the local one wins inside its function. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Inside a function. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: No — it is invisible outside its function. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Outside all functions. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Every function. Do this with a real example of your own and write or say how you know it is right.
