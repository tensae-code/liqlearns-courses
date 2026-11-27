# Set Types in Pascal

## Do it first

Some data is a handful, not a list: the vowels present in a word, the days a shop opens, the marks a pupil has earned. Pascal — alone among school languages — gives the handful its own type: the set.

## Sub lesson 1 — A set — membership is the whole story

A **set** is a collection of values of one **ordinal base type**, in which each value is either **in or out** — present at most once, in no order. Pascal writes a set type as `set of <base>` — `type TDays = set of TDay;` — and a set value in brackets: `[Mon, Wed, Fri]`, the empty set `[]`. A variable of the type can hold **any** sub-collection of the base — for a 7-day base, 2⁷ = 128 possible sets. Membership is the only question a set answers, and it answers it in one act.

In your mind's eye: a set — membership is the whole story.

[Picture 47669 — a set — membership is the whole story]

## Sub lesson 2 — Working with sets — union, difference, in

Sets combine by their mathematics: **+** is union (in either), **−** is difference (in the first, not the second), ∗ is intersection (in both), and comparisons test inclusion (<= means 'is a subset of'). The **in** operator asks the membership question: `if Wed in openDays then …`. Sets suit closed vocabularies — letters present, options chosen, days open — wherever a program asks 'which of these?' rather than 'how many, in what order?'. C++ has no built-in set type; the work is done by library classes — the concept again outliving its clothing.

In your mind's eye: working with sets — union, difference, in.

[Picture 47670 — working with sets — union, difference, in]

## Say it to your companion

Tell your companion, in your own words: A **set** is a collection of values of one **ordinal base type**, in which each value is either **in or out** — present at most once, in no order. Pascal writes a set type as `set of <base>` — `type TDays = set of TDay;` — and a set value in brackets: `[Mon, Wed, Fri]`, the empty set `[]`. A variable of the type can hold **any** sub-collection of the base — for a 7-day base, 2⁷ = 128 possible sets. Membership is the only question a set answers, and it answers it in one act. Sets combine by their mathematics: **+** is union (in either), **−** is difference (in the first, not the second), ∗ is intersection (in both), and comparisons test inclusion (<= means 'is a subset of'). The **in** operator asks the membership question: `if Wed in openDays then …`. Sets suit closed vocabularies — letters present, options chosen, days open — wherever a program asks 'which of these?' rather than 'how many, in what order?'. C++ has no built-in set type; the work is done by library classes — the concept again outliving its clothing. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A collection of values of one ordinal base type, each present at most once, in no order. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: set of <base type> — type TDays = set of TDay;. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: In brackets — [Mon, Wed, Fri]; the empty set is []. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: 2⁷ = 128 — every sub-collection. Do this with a real example of your own and write or say how you know it is right.
