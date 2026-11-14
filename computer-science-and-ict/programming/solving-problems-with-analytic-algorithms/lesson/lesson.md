# Solving Problems with Analytic Algorithms

## Do it first

A taxi charges a starting price plus a price per kilometre. Asked the fare for 3 km, then 7 km, then 20 km, you could simulate the meter click by click — or see the shape of the problem once: fare = start + price × distance, and every question becomes one calculation. Seeing that shape is this lesson.

## Sub lesson 1 — What an analytic algorithm is

Some problems carry their answer inside a **relationship**: the wanted quantity depends on the given quantities in a fixed way that can be written as a **formula**. An **analytic algorithm** finds that formula first — it analyses the problem until the relationship stands clear — and then obtains every answer by substitution and calculation. The thinking happens once, up front: model the problem (name the quantities, say how they relate), derive the formula, and the rest is arithmetic. Contrast it with trying cases one by one: analysis replaces searching with knowing.

[Picture — the taxi meter problem drawn twice — on the left a long winding path of clicks and additions, on the right one straight arrow labelled with the fare formula]

## Sub lesson 2 — The analytic way, worked

The method runs in four moves. **Model**: read the problem, name what is given and what is wanted, and state in words how they relate. **Derive**: turn the relation into a formula with letters. **Compute**: put the given values in and calculate, keeping units honest. **Check**: test the formula on an easy case you can verify by hand — if it fails there, the model, not the arithmetic, is wrong. Worked on the taxi: model — fare grows by the per-kilometre price with distance, on top of a fixed start; derive — F = S + P × D; compute — S = 10, P = 2, D = 7 gives F = 24; check — D = 0 must give exactly the starting price, and it does.

[Picture — the four moves as four stepping stones across a stream — Model, Derive, Compute, Check — with the taxi formula written on the Derive stone]

## Say it to your companion

Tell your companion, in your own words: an analytic algorithm first finds the relationship inside a problem and writes it as a formula; then every answer is one substitution and calculation — and the formula is checked on an easy case before it is trusted. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what an analytic algorithm is: solving by deriving the formula that connects givens to the wanted answer. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: name the four moves: model, derive, compute, check. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: work the taxi-fare example through all four moves. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: say why the check uses an easy case, and what a failed check tells you. Do this with a real example of your own and write or say how you know it is right.
