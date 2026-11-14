# Defining New Data Types in Pascal and C++

## Do it first

A program about school marks should not think in raw integers. Grade 10's types chapter culminates in the programmer's own definitions: new types, named for the problem, built from the language's stock.

## Sub lesson 1 — type and typedef — naming a construction

A **type definition** gives a **name** to a type construction, once, for the whole program. Pascal gathers definitions in a **type** section: `type TMark = 1..10; TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);` — after which TMark and TDay are used exactly like integer or real. C++ spells the same act **typedef** (or the newer **using**): `typedef int TMark;` — weaker than Pascal's (an alias, not a guarded new kind), a difference in protection the pair has met before. Either way: define once, use everywhere.

[Picture — type and typedef — naming a construction]

## Sub lesson 2 — Why define types — the program in the problem's words

The reasons compound. **Readability**: `var m: TMark` says more than `var m: integer`. **Protection**: a TMark variable inherits the subrange's guard — a mark of 47 is caught by the type. **Change in one place**: if marks become 1..12, one definition changes and the program follows. And **honesty of design**: the definitions at a program's head are its data's manifesto — read them and you know what world the program models. Types defined well are documentation the compiler checks.

[Picture — Why define types — the program in the problem's words]

## Say it to your companion

Tell your companion, in your own words: A **type definition** gives a **name** to a type construction, once, for the whole program. Pascal gathers definitions in a **type** section: `type TMark = 1..10; TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);` — after which TMark and TDay are used exactly like integer or real. C++ spells the same act **typedef** (or the newer **using**): `typedef int TMark;` — weaker than Pascal's (an alias, not a guarded new kind), a difference in protection the pair has met before. Either way: define once, use everywhere. The reasons compound. **Readability**: `var m: TMark` says more than `var m: integer`. **Protection**: a TMark variable inherits the subrange's guard — a mark of 47 is caught by the type. **Change in one place**: if marks become 1..12, one definition changes and the program follows. And **honesty of design**: the definitions at a program's head are its data's manifesto — read them and you know what world the program models. Types defined well are documentation the compiler checks. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: It gives a name to a type construction, once, for the whole program. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In a type section before the variables. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: typedef (or the newer using). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: It makes an alias, not a guarded new kind. Do this with a real example of your own and write or say how you know it is right.
