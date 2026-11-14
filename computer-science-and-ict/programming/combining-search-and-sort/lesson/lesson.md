# Combining Search and Sort

## Do it first

The chapter's methods are stronger together than apart. Malaysia combines them: sort first, then search the ordered list with binary search. In this lesson you build that combination — and judge when its extra work pays.

## Sub lesson 1 — Sort first, then search

The combined algorithm runs in **two stages**: a **sort stage** (any correct sort — bubble or bucket by the data) puts the list in order, then a **search stage** — **binary search** — works the ordered list, halving to the target. The stages are joined by the sort's guarantee: binary search's one demand (order) is exactly what the first stage supplies. In pseudocode the combination is simply the two algorithms written one after the other, the sorted list handed from the first to the second.

[Picture — Sort first, then search]

## Sub lesson 2 — When the combination pays

Sorting is **work done once**; searching is work done **per question**. The combination pays when **many searches** follow — the sort's cost is shared across all of them, and each search then costs halving-work instead of whole-list work. For a **single** search, the combination usually loses: sorting a whole list to answer one question costs more than one linear search. Malaysia's judgement rule: count the questions first — one question, search the list as it stands; a season of questions, sort once and halve every time.

[Picture — When the combination pays]

## Say it to your companion

Tell your companion, in your own words: The combined algorithm runs in **two stages**: a **sort stage** (any correct sort — bubble or bucket by the data) puts the list in order, then a **search stage** — **binary search** — works the ordered list, halving to the target. The stages are joined by the sort's guarantee: binary search's one demand (order) is exactly what the first stage supplies. In pseudocode the combination is simply the two algorithms written one after the other, the sorted list handed from the first to the second. Sorting is **work done once**; searching is work done **per question**. The combination pays when **many searches** follow — the sort's cost is shared across all of them, and each search then costs halving-work instead of whole-list work. For a **single** search, the combination usually loses: sorting a whole list to answer one question costs more than one linear search. Malaysia's judgement rule: count the questions first — one question, search the list as it stands; a season of questions, sort once and halve every time. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Sort the list, then binary-search it. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The sort's guarantee — binary search demands order, and the sort supplies it. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Binary search — the ordered list is what it needs. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: When many searches follow one sort. Do this with a real example of your own and write or say how you know it is right.
