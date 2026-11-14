# Solving Problems by Enumeration

## Do it first

You have forgotten the last digit of a friend's phone number. There is no formula for a forgotten digit — but there are only ten possibilities, and you can try them in order: 0, 1, 2 … until the right voice answers. When the possibilities are few and each is easy to test, trying them all is not a weakness. It is a method, and it has a name.

## Sub lesson 1 — What enumeration is

**Enumeration** means listing all the candidates and testing them one by one. An enumeration algorithm has three parts: a way to **generate** every candidate without repeats or gaps (usually in a fixed order — counting order is the favourite); a **test** that checks each candidate against all the problem's conditions; and a **collection** step that keeps the candidates that pass. Because every candidate is tested, enumeration cannot miss a solution that exists inside the list — its certainty is its beauty. Its textbook home is problems with no known formula, or where finding one is harder than searching.

[Picture — a sieve over a bowl: a stream of numbered candidate cards pouring in the top, most falling away, two golden cards caught in the mesh]

## Sub lesson 2 — Doing it well — order, and the size of the list

Good enumeration is **orderly**: generate candidates in a system (all two-digit combinations from 00 upward, all triples in counting order) so none is repeated and none skipped — disorder is how solutions get missed. And good enumeration watches the **size of the list**: ten forgotten digits finish in minutes; a forgotten six-digit code is a million candidates, and a long password is more candidates than a lifetime holds. That explosion is enumeration's limit — the method is certain, but certainty costs time, so the craft is to shrink the list first with anything the problem tells you (a digit known here, a condition that halves the list there) before the testing begins.

[Picture — a counter of candidates climbing — 10, then 1,000, then 1,000,000, then a number too long for the screen]

## Say it to your companion

Tell your companion, in your own words: enumeration lists every candidate in an orderly way, tests each against all the conditions, and keeps those that pass — it cannot miss a solution inside the list, but the list must stay small enough to finish. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what enumeration is, and name its three parts: generate, test, collect. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: explain why orderly generation matters (no repeats, no gaps, no missed solution). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: explain enumeration's limit: the candidate list can explode in size. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: shrink a candidate list using a condition from the problem before enumerating. Do this with a real example of your own and write or say how you know it is right.
