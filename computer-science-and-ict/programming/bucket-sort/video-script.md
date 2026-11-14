# Video script — Bucket Sort

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Bucket sort** begins with **buckets**: ranges that cover the values — for marks out of 100, buckets 0–9, 10–19, …, 90–100. Every value is **placed in the bucket its size belongs to** — 37 into the 30s bucket, 8 into the 0s bucket. No comparisons between values happen in this step; the value's own size names its bucket. Scattering works when the ranges are known in advance and the values spread across them — a list of ages, marks or prices fits; a list with no known range does not.
Inside each bucket, the few values are put **in order** (by a simple sort — the buckets are small, so even bubble sort is quick there). Then the buckets are **gathered in bucket order** — all of the 0s bucket, then all of the 10s, and so on — and the gathered line is the sorted list. Malaysia pairs bucket sort with bubble sort to make the contrast explicit: bubble sort moves values by comparing neighbours; bucket sort moves them by knowing where values of each size belong.
