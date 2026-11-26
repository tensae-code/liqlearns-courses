# Bucket Sort

## Do it first

Not every sort compares neighbours. Malaysia's second sort scatters the values into labelled buckets — tens in one, twenties in the next — gathers each bucket in order, and reads the buckets through. In this lesson you bucket-sort, and learn the kind of data it suits.

## Sub lesson 1 — Scatter — values into their buckets

**Bucket sort** begins with **buckets**: ranges that cover the values — for marks out of 100, buckets 0–9, 10–19, …, 90–100. Every value is **placed in the bucket its size belongs to** — 37 into the 30s bucket, 8 into the 0s bucket. No comparisons between values happen in this step; the value's own size names its bucket. Scattering works when the ranges are known in advance and the values spread across them — a list of ages, marks or prices fits; a list with no known range does not.

In your mind's eye: scatter — values into their buckets.

[Picture 46785 — scatter — values into their buckets]

## Sub lesson 2 — Order each bucket, then gather

Inside each bucket, the few values are put **in order** (by a simple sort — the buckets are small, so even bubble sort is quick there). Then the buckets are **gathered in bucket order** — all of the 0s bucket, then all of the 10s, and so on — and the gathered line is the sorted list. Malaysia pairs bucket sort with bubble sort to make the contrast explicit: bubble sort moves values by comparing neighbours; bucket sort moves them by knowing where values of each size belong.

In your mind's eye: order each bucket, then gather.

[Picture 46786 — order each bucket, then gather]

## Say it to your companion

Tell your companion, in your own words: **Bucket sort** begins with **buckets**: ranges that cover the values — for marks out of 100, buckets 0–9, 10–19, …, 90–100. Every value is **placed in the bucket its size belongs to** — 37 into the 30s bucket, 8 into the 0s bucket. No comparisons between values happen in this step; the value's own size names its bucket. Scattering works when the ranges are known in advance and the values spread across them — a list of ages, marks or prices fits; a list with no known range does not. Inside each bucket, the few values are put **in order** (by a simple sort — the buckets are small, so even bubble sort is quick there). Then the buckets are **gathered in bucket order** — all of the 0s bucket, then all of the 10s, and so on — and the gathered line is the sorted list. Malaysia pairs bucket sort with bubble sort to make the contrast explicit: bubble sort moves values by comparing neighbours; bucket sort moves them by knowing where values of each size belong. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A range that the values are scattered into — such as 0–9, 10–19 for marks. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: By its own size — 37 goes in the 30s bucket. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — the value's size names its bucket. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Its few values are put in order — by a simple sort. Do this with a real example of your own and write or say how you know it is right.
