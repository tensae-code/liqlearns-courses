# Video script — Combining Search and Sort

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The combined algorithm runs in **two stages**: a **sort stage** (any correct sort — bubble or bucket by the data) puts the list in order, then a **search stage** — **binary search** — works the ordered list, halving to the target. The stages are joined by the sort's guarantee: binary search's one demand (order) is exactly what the first stage supplies. In pseudocode the combination is simply the two algorithms written one after the other, the sorted list handed from the first to the second.
Sorting is **work done once**; searching is work done **per question**. The combination pays when **many searches** follow — the sort's cost is shared across all of them, and each search then costs halving-work instead of whole-list work. For a **single** search, the combination usually loses: sorting a whole list to answer one question costs more than one linear search. Malaysia's judgement rule: count the questions first — one question, search the list as it stands; a season of questions, sort once and halve every time.
