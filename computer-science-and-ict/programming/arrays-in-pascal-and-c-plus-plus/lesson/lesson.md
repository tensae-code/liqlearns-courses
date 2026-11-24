# Arrays in Pascal and C++

## Do it first

Thirty pupils, thirty marks, one name. Grade 11's structured-types chapter begins with the array — the workhorse structure of both languages, where the only new idea is the index and everything else is loops.

## Sub lesson 1 — Declaration and elements — the name with an address

An **array** is a fixed row of values **of one type** under **one name**, each reached by its **index**: Pascal declares `var a: array[1..30] of integer;` — index range and element type in the declaration; C++ writes `int a[30];` — size in brackets, indexes running **0..29**. The element `a[i]` is an ordinary variable of the element type: assignable, readable, computable. The index may itself be a **variable or expression** — that single fact is the array's whole power, because a loop can then compute which element to touch.

In your mind's eye: declaration and elements — the name with an address.

## Sub lesson 2 — Working the array — loops, and the border's danger

Almost all array work is a **for loop** walking the index across the whole range: reading in, printing out, summing into an accumulator, searching for a value or the greatest element — the patterns Grade 11 calls array processing. The structure's danger stands at its **borders**: an index outside the declared range touches memory that is not the array's — Pascal's range checking (switched on) catches it; C++ lets it pass silently into corruption. Every array program therefore guards its indexes the way drivers guard a cliff road.

In your mind's eye: working the array — loops, and the border's danger.

## Say it to your companion

Tell your companion, in your own words: An **array** is a fixed row of values **of one type** under **one name**, each reached by its **index**: Pascal declares `var a: array[1..30] of integer;` — index range and element type in the declaration; C++ writes `int a[30];` — size in brackets, indexes running **0..29**. The element `a[i]` is an ordinary variable of the element type: assignable, readable, computable. The index may itself be a **variable or expression** — that single fact is the array's whole power, because a loop can then compute which element to touch. Almost all array work is a **for loop** walking the index across the whole range: reading in, printing out, summing into an accumulator, searching for a value or the greatest element — the patterns Grade 11 calls array processing. The structure's danger stands at its **borders**: an index outside the declared range touches memory that is not the array's — Pascal's range checking (switched on) catches it; C++ lets it pass silently into corruption. Every array program therefore guards its indexes the way drivers guard a cliff road. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A fixed row of values of one type under one name, reached by index. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: var a: array[1..30] of integer;. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: int a[30]; — indexes 0..29. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Yes — of the element type: assignable, readable, computable. Do this with a real example of your own and write or say how you know it is right.
