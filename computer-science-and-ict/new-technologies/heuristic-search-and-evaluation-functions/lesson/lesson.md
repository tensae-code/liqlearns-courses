# Heuristic Search and Evaluation Functions

## Do it first

Blind search walks a dark library by rule. Heuristic search carries a lamp: a guess, for every shelf, of how promising it looks. This lesson learns the lamp — and its lies.

## Sub lesson 1 — The heuristic function — an estimate with a name

A **heuristic function h(n)** estimates the cost from a node n to the goal: straight-line distance for a route (whatever the roads do), tiles out of place for a puzzle. A good heuristic is **informed** (it uses the problem's own knowledge), **cheap to compute**, and ideally **admissible** — never overestimating the true cost, so the search it guides stays optimal. Heuristic search orders its frontier by promise, expanding the most hopeful node first.

In your mind's eye: the heuristic function — an estimate with a name.

## Sub lesson 2 — Evaluation functions — judging a node whole

An **evaluation function f(n)** scores a node for expanding: it may join the cost already spent, g(n), with the heuristic estimate, h(n) — f(n) = g(n) + h(n), the shape of the famous A* search — balancing 'how far I've come' against 'how far I seem to go'. Jordan's lesson closes with the craft's warning: a heuristic is a guess with consequences — a lying heuristic doesn't just slow the search, it can walk it confidently away from the goal.

In your mind's eye: evaluation functions — judging a node whole.

## Say it to your companion

Tell your companion, in your own words: A **heuristic function h(n)** estimates the cost from a node n to the goal: straight-line distance for a route (whatever the roads do), tiles out of place for a puzzle. A good heuristic is **informed** (it uses the problem's own knowledge), **cheap to compute**, and ideally **admissible** — never overestimating the true cost, so the search it guides stays optimal. Heuristic search orders its frontier by promise, expanding the most hopeful node first. An **evaluation function f(n)** scores a node for expanding: it may join the cost already spent, g(n), with the heuristic estimate, h(n) — f(n) = g(n) + h(n), the shape of the famous A* search — balancing 'how far I've come' against 'how far I seem to go'. Jordan's lesson closes with the craft's warning: a heuristic is a guess with consequences — a lying heuristic doesn't just slow the search, it can walk it confidently away from the goal. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The cost from node n to the goal. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Straight-line distance, whatever the roads do. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Tiles out of place. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Never overestimating the true cost. Do this with a real example of your own and write or say how you know it is right.
