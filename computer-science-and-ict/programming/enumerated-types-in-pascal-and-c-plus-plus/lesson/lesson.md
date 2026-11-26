# Enumerated Types in Pascal and C++

## Do it first

Grade 7's enumerated type returns wearing C++ dress. The idea survives the crossing; the discipline around it differs — and the difference is the lesson.

## Sub lesson 1 — The same idea — a named set of values

An **enumerated type** defines a value set by **naming its members**: Pascal writes `type TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);`; C++ writes `enum TDay {Mon, Tue, Wed, Thu, Fri, Sat, Sun};`. Underneath, the members **are numbered from 0 in order** in both languages — the names are the programmer's reading of stored integers. Variables of the type hold one member, members compare by their hidden numbers, and the set stays closed: no value outside the list can enter.

In your mind's eye: the same idea — a named set of values.

[Picture 47074 — the same idea — a named set of values]

## Sub lesson 2 — Where the pair differs — strictness and scope

Pascal keeps the type **strict**: a TDay variable takes only TDay members, and its ord/succ/pred behave as Grade 7 taught. Classic C++ **enum** is **looser**: members leak into the surrounding scope as plain integers, mix freely with int arithmetic, and two enums' same-named members collide — freedoms the newer `enum class` was invented to withdraw. The section's lesson is the pair's in miniature: **the concept is shared; the protection is a language choice**, and knowing both tells you what your compiler will and will not catch.

In your mind's eye: where the pair differs — strictness and scope.

[Picture 47075 — where the pair differs — strictness and scope]

## Say it to your companion

Tell your companion, in your own words: An **enumerated type** defines a value set by **naming its members**: Pascal writes `type TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);`; C++ writes `enum TDay {Mon, Tue, Wed, Thu, Fri, Sat, Sun};`. Underneath, the members **are numbered from 0 in order** in both languages — the names are the programmer's reading of stored integers. Variables of the type hold one member, members compare by their hidden numbers, and the set stays closed: no value outside the list can enter. Pascal keeps the type **strict**: a TDay variable takes only TDay members, and its ord/succ/pred behave as Grade 7 taught. Classic C++ **enum** is **looser**: members leak into the surrounding scope as plain integers, mix freely with int arithmetic, and two enums' same-named members collide — freedoms the newer `enum class` was invented to withdraw. The section's lesson is the pair's in miniature: **the concept is shared; the protection is a language choice**, and knowing both tells you what your compiler will and will not catch. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Pascal: type TDay = (Mon, …, Sun); C++: enum TDay {Mon, …, Sun};. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Integers numbered from 0 in order. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: By their hidden numbers. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — the set stays closed. Do this with a real example of your own and write or say how you know it is right.
