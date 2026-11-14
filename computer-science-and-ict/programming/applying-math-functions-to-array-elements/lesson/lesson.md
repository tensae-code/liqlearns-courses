# Applying Math Functions to Array Elements

## Do it first

You have the toolbox (cmath) and the row of values (the array). This lesson runs the toolbox down the row.

## Sub lesson 1 — One function, every element

The pattern is the familiar walk with a function inside: **b[i] = sqrt(a[i]);** fills a second array with roots; printing **pow(a[i], 2)** shows squares without storing them. Domain care travels with the function: sqrt of a **negative** element is not a real number, so a careful program tests before it transforms.

[Picture — one function, every element]

## Sub lesson 2 — Transforms, then facts about transforms

Transformed arrays feed the usual walks — total the **absolute values**, find the largest **square**, count the elements whose **rounded** value passes a mark. Each job is a composition: transform inside the walk that totals, crowns or counts. The section's discipline is order: know whether the function applies **per element** (one pass) or needs an **array-wide fact first** (two passes).

[Picture — transforms, then facts about transforms]

## Say it to your companion

Tell your companion, in your own words: Library math functions and arrays combine element by element: a loop applies a cmath function — sqrt, pow, abs, rounding — to each element and stores or prints the results, turning a whole column of values in one walk; functions needing whole-array facts (like a mean) still take two passes. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: b[i] = sqrt(a[i]); inside the walk. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: No negative elements — test before transforming. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Totalling the absolute values (any composed job from the lesson). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A whole-array value like the mean. Do this with a real example of your own and write or say how you know it is right.
