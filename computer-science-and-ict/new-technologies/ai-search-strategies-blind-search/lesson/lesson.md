# AI Search Strategies — Blind Search

## Do it first

Imagine searching a dark library with no catalogue, by a fixed walking rule. That is blind search — this lesson learns its rules and their honest costs.

## Sub lesson 1 — What blind search is

**Blind search** (uninformed search) explores the search tree using only the problem's own information — no hint about how near the goal is. Its strategies differ by the order of visiting: **breadth-first** expands level by level (every node at one depth before any deeper), **depth-first** dives down one branch to its end before backtracking. Both are complete on finite trees in their own ways; both can waste ages in branches a glance at the goal would have pruned.

[Picture — What blind search is]

## Sub lesson 2 — Costs and uses — when blindness is honest

Breadth-first guarantees the **shallowest** goal but must **remember the whole frontier** — its space cost explodes. Depth-first remembers only its path — cheap in space, but it may dive past the goal's level forever on an infinite branch. Jordan teaches blind search first because it is the baseline every smarter strategy must beat, and because some problems genuinely offer no guidance to be smart with.

[Picture — Costs and uses — when blindness is honest]

## Say it to your companion

Tell your companion, in your own words: **Blind search** (uninformed search) explores the search tree using only the problem's own information — no hint about how near the goal is. Its strategies differ by the order of visiting: **breadth-first** expands level by level (every node at one depth before any deeper), **depth-first** dives down one branch to its end before backtracking. Both are complete on finite trees in their own ways; both can waste ages in branches a glance at the goal would have pruned. Breadth-first guarantees the **shallowest** goal but must **remember the whole frontier** — its space cost explodes. Depth-first remembers only its path — cheap in space, but it may dive past the goal's level forever on an infinite branch. Jordan teaches blind search first because it is the baseline every smarter strategy must beat, and because some problems genuinely offer no guidance to be smart with. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Only the problem's own — no hint of the goal's nearness. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Level by level — every node at one depth before deeper. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Dives down one branch to its end, then backtracks. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Uninformed search. Do this with a real example of your own and write or say how you know it is right.
