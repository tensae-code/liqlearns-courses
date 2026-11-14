# Inserting Elements and Computations in Arrays

## Do it first

An array declared is an array empty. This lesson fills it properly, keeps count of what is really in it, and computes over the filled part only.

## Sub lesson 1 — Entering elements with a live count

Elements are **entered** one by one — typed in a **fill loop** (cin >> a[i]) or assigned from the program — while a counter **n** records **how many elements are live**. Capacity and count are different numbers: the array may hold 100 and contain 7. Every later walk uses **n**, not the capacity, as its limit.

[Picture — entering elements with a live count]

## Sub lesson 2 — Computations over the filled part

With the array filled, **basic computations** walk the live elements: the **sum**, the **average** (sum divided by n — the live count, not the capacity), each element transformed (doubled into a second array, say). The classic fault is dividing by capacity or walking into the unfilled tail where garbage values wait; the live-count discipline prevents both.

[Picture — computations over the filled part]

## Say it to your companion

Tell your companion, in your own words: New values enter an array by being read or assigned into elements in order — a fill loop with a count of how many elements are live — and computations over the filled part (totals, averages, transformations) then walk exactly those live elements, never the array's empty tail. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A counter, n. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: No — the array may hold 100 and contain 7. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The sum divided by the live count n. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Dividing by the capacity instead of n. Do this with a real example of your own and write or say how you know it is right.
