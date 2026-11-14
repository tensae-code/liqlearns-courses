# Video script — Set Types in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **set** is a collection of values of one **ordinal base type**, in which each value is either **in or out** — present at most once, in no order. Pascal writes a set type as `set of <base>` — `type TDays = set of TDay;` — and a set value in brackets: `[Mon, Wed, Fri]`, the empty set `[]`. A variable of the type can hold **any** sub-collection of the base — for a 7-day base, 2⁷ = 128 possible sets. Membership is the only question a set answers, and it answers it in one act.
Sets combine by their mathematics: **+** is union (in either), **−** is difference (in the first, not the second), ∗ is intersection (in both), and comparisons test inclusion (<= means 'is a subset of'). The **in** operator asks the membership question: `if Wed in openDays then …`. Sets suit closed vocabularies — letters present, options chosen, days open — wherever a program asks 'which of these?' rather than 'how many, in what order?'. C++ has no built-in set type; the work is done by library classes — the concept again outliving its clothing.
