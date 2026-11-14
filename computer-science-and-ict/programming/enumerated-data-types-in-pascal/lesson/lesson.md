# Enumerated Data Types in Pascal

## Do it first

Some data is not numbers at all: a day of the week is one of seven named things. Grade 7's Pascal course reaches the type the programmer builds themselves — by enumerating, listing, its values.

## Sub lesson 1 — Defining a type by listing its values

An **enumerated type** is defined by **listing its values in brackets**: `type TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);` — the type has exactly those values and no others. A variable of the type holds one of them: `var d: TDay; d := Wed;`. The values are **names, not texts**: they are not strings in apostrophes, and the compiler checks them — assigning `d := Holiday` is an error the moment it is written, protection no number code (1=Mon, 2=Tue…) can give.

[Picture — Defining a type by listing its values]

## Sub lesson 2 — Order from the list — ord, succ, pred

The list's order is not decoration: it gives the values an **order**. The functions **succ** and **pred** give the next and previous value (succ(Wed) = Thu), and **ord** gives a value's position counted from 0 (ord(Mon) = 0). So enumerated values can be compared (Sat > Fri is true), stepped through in loops, and counted — the manners of numbers, with the meanings of names. Enumerations suit closed lists of the world: months, suits, directions, school grades — sets that do not grow.

[Picture — Order from the list — ord, succ, pred]

## Say it to your companion

Tell your companion, in your own words: An **enumerated type** is defined by **listing its values in brackets**: `type TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);` — the type has exactly those values and no others. A variable of the type holds one of them: `var d: TDay; d := Wed;`. The values are **names, not texts**: they are not strings in apostrophes, and the compiler checks them — assigning `d := Holiday` is an error the moment it is written, protection no number code (1=Mon, 2=Tue…) can give. The list's order is not decoration: it gives the values an **order**. The functions **succ** and **pred** give the next and previous value (succ(Wed) = Thu), and **ord** gives a value's position counted from 0 (ord(Mon) = 0). So enumerated values can be compared (Sat > Fri is true), stepped through in loops, and counted — the manners of numbers, with the meanings of names. Enumerations suit closed lists of the world: months, suits, directions, school grades — sets that do not grow. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: By listing its values in brackets in a type definition. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Mon, Tue, Wed, Thu, Fri, Sat, Sun — the type TDay. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — they are names, not texts in apostrophes. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The compiler checks assignments — a value outside the list is an error at once. Do this with a real example of your own and write or say how you know it is right.
